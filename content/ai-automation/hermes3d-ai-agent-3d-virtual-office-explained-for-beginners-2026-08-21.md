---
title: "Hermes3D와 AI 에이전트 3D 가상 오피스, 처음 보는 분도 이해되게 다시 풀어보기"
description: "Hermes3D는 AI 에이전트를 3D 가상 오피스 안의 직원처럼 보여주고 관리하려는 오픈소스 UI이며, 실제 일을 하는 본체는 Hermes Agent라는 점을 4060 독자 눈높이로 쉽게 정리한 글입니다."
tags:
  - hermes3d
  - hermes-agent
  - ai-automation
  - mcp
  - multi-agent
created: "2026-08-21"
modified: "2026-08-21"
publish: true
cssclasses:
  - field-note
---

# Hermes3D와 AI 에이전트 3D 가상 오피스, 처음 보는 분도 이해되게 다시 풀어보기

AI 에이전트 이야기를 처음 들으면 보통 두 갈래에서 같이 막힌다. 하나는 `Hermes3D`, `Hermes Agent`, `MCP`, `LLM Provider` 같은 용어가 한꺼번에 쏟아진다는 점이고, 다른 하나는 “그래서 이게 결국 채팅창이랑 뭐가 다른데?”라는 질문이 남는다는 점이다.

이번에 받은 원문은 이걸 꽤 잘 정리해둔 학습 노트다. 다만 처음 보는 분, 특히 4060미들스쿨 회원님들처럼 **용어를 정확히 이해하면서도 너무 급하지 않게 따라가고 싶은 독자**에게는 중간 설명이 조금 더 있으면 훨씬 읽기 쉬워질 수 있다. 그래서 이 글에서는 원문 내용을 하나도 빼지 않고, **쉽게 말하면 무엇인지, 어디가 핵심인지, 왜 흥미로운지**를 사이사이에 덧붙여 다시 풀어보려 한다.

## 먼저 결론

- `Hermes3D`는 AI 에이전트가 실제 사무실에서 일하는 것처럼 보이게 해주는 **3D 관리 화면**에 가깝다.
- 실제로 생각하고 도구를 쓰고 명령을 수행하는 본체는 `Hermes Agent` 쪽이다.
- `MCP`는 Hermes의 본체가 아니라, Hermes Agent가 GitHub, 파일, 데이터베이스 같은 **바깥 도구와 연결되는 표준 연결 방식**으로 이해하면 가장 쉽다.
- 이 생태계의 진짜 흥미로운 점은 “예쁜 3D 화면”보다 **여러 AI 에이전트의 상태, 역할, 진행 상황을 한눈에 관리하는 새로운 인터페이스**를 만들려는 데 있다.
- 따라서 Hermes3D는 단순 장난감보다는 `AI Agent Management UI`, `Spatial UI`, `Observability 화면` 쪽으로 읽는 것이 더 정확하다.

## 1. Hermes3D란?

원문 표현을 그대로 살리면, Hermes3D는 AI 에이전트를 단순한 목록이나 로그 창이 아니라 **3D 가상 오피스 안의 직원처럼 시각화하고 관리하는 오픈소스 프로젝트**다.

참고 저장소는 아래 두 곳이다.

- Hermes3D: <https://github.com/iamlukethedev/Hermes3D>
- Hermes Agent: <https://github.com/NousResearch/hermes-agent>

핵심 개념을 아주 짧게 줄이면 이렇다.

> **Hermes = 실제로 일하는 AI 직원**
> **Hermes3D = 그 직원들이 일하는 모습을 보여주는 3D 사무실**

이 비유가 중요한 이유는, Hermes3D를 처음 보면 3D 그래픽 쪽이 먼저 보이기 때문이다. 그런데 본질은 3D 캐릭터가 아니라, **에이전트 여러 명을 어떻게 더 직관적으로 보고 관리할 것인가**에 있다.

## 2. Hermes3D의 전체 구조

원문에서는 Hermes3D를 크게 두 부분으로 나눠 본다.

### 프론트엔드

- Next.js
- React
- TypeScript
- Three.js
- React Three Fiber
- Drei
- 일부 인터랙션에서 Phaser 활용

이 프론트엔드는 다음 역할을 맡는다.

- 3D 가상 오피스 표현
- AI 에이전트 캐릭터 표현
- 에이전트 상태 시각화
- 작업 진행 상태 표시
- 에이전트와의 대화 UI
- 여러 에이전트의 활동 모니터링

쉽게 말하면 이쪽은 **보여주는 화면**이다. 즉 “누가 지금 일하고 있는지”, “어느 팀이 바쁜지”, “어느 에이전트가 멈췄는지”를 사람이 보기 좋게 바꿔주는 층이다.

### 에이전트 백엔드

- Hermes Agent
- Python
- Agent Runtime
- LLM Providers
- Tool / Skill
- Session / Context 관리
- MCP Client

이쪽은 반대로 **실제로 일을 하는 본체**다.

정리하면 이렇게 보면 된다.

> **프론트엔드: Next.js + React + TypeScript + Three.js**
> **에이전트 백엔드: Hermes Agent + Python + LLM Providers + MCP**

즉 Hermes3D는 “똑똑한 3D 게임”이 아니라, **Hermes Agent라는 실제 AI 작업 엔진 위에 얹는 시각화 인터페이스**에 더 가깝다.

## 3. 전체 동작 구조

원문의 도식은 이 생태계를 이해하는 데 아주 중요하다.

```text
┌──────────────────────────────────────┐
│ Hermes3D Frontend                    │
│                                      │
│ Next.js                             │
│ React                               │
│ TypeScript                          │
│ Three.js / React Three Fiber        │
│                                      │
│ → 3D 가상 오피스                    │
│ → 에이전트 캐릭터                   │
│ → 상태/작업/대화 시각화             │
└──────────────────┬───────────────────┘
                   │
             WebSocket / API
                   │
                   ▼
┌──────────────────────────────────────┐
│ Hermes Agent                         │
│                                      │
│ Python                               │
│ Agent Runtime                        │
│ Tool / Skill 실행                    │
│ Session / Context 관리               │
│ MCP Client                           │
└───────────────┬──────────────────────┘
                │
        ┌───────┼─────────┐
        ▼       ▼         ▼
      OpenAI Anthropic  Gemini
      Codex  Claude     기타 LLM
                │
        └──── MCP Servers ─────┐
                               ▼
                    GitHub / Filesystem
                    DB / API / 서비스
```

이걸 더 쉬운 말로 바꾸면 이렇다.

1. 사람은 Hermes3D 화면을 본다.
2. Hermes3D는 실제 작업 지시를 Hermes Agent에게 넘긴다.
3. Hermes Agent는 필요에 따라 GPT, Claude, Gemini 같은 두뇌를 고른다.
4. Hermes Agent는 파일, GitHub, DB 같은 바깥 도구가 필요하면 MCP를 통해 붙는다.
5. 그 결과를 다시 Hermes3D가 사람이 보기 좋게 보여준다.

결국 위 도식은 “화면”과 “실행 엔진”을 구분해 보는 연습이라고 생각하면 쉽다.

## 4. Hermes3D와 Hermes Agent의 역할 차이

이 부분은 꼭 분리해서 이해하는 게 좋다.

### Hermes3D

Hermes3D는 주로 **사용자 인터페이스와 시각화**를 담당한다.

쉽게 말하면:

> Hermes3D는 AI 에이전트들이 일하는 모습을 보여주는 사무실입니다.

### Hermes Agent

Hermes Agent는 실제 AI 에이전트의 실행을 담당한다.

주요 역할은 아래와 같다.

- LLM 호출
- 작업 계획
- 명령 실행
- 파일 읽기/쓰기
- Tool 사용
- Skill 실행
- MCP 서버 연결
- 세션 관리
- 컨텍스트 관리
- 다른 AI 코딩 에이전트 활용

쉽게 말하면:

> Hermes Agent는 실제로 일을 수행하는 AI 직원입니다.

사람이 조직을 볼 때도 “사무실 인테리어”와 “실제 직원의 일”은 다르다. Hermes3D와 Hermes Agent 관계도 딱 그 정도로 나눠 보면 된다.

## 5. Claude Code와 Codex의 관계

이 부분도 오해가 자주 생긴다.

Hermes3D 자체가 Claude Code나 Codex를 곧바로 3D 백엔드로 쓰는 구조라고 보기보다는, 원문처럼 아래 흐름으로 이해하는 것이 맞다.

```text
Hermes3D
  ↓
Hermes Agent
  ↓
Claude Code / Codex / 기타 도구
```

즉 Hermes3D는 직접 코딩 에이전트가 아니라, **Hermes Agent가 Claude Code나 Codex 같은 외부 AI 코딩 도구를 불러 쓰는 장면을 관리하고 보여줄 수 있는 화면**에 가깝다.

원문 예시는 아래와 같다.

```bash
# Claude Code 환경 가져오기
hermes import-agent claude-code

# Codex 환경 가져오기
hermes import-agent codex
```

여기서 핵심은 “Hermes가 외부 AI 코딩 에이전트에게 일을 위임할 수 있다”는 점이다. 즉 Hermes Agent는 혼자 다 하는 존재라기보다, **다른 에이전트까지 조율하는 관리자**처럼도 움직일 수 있다.

## 6. LLM Providers란?

`LLM Provider`는 말 그대로 “어느 AI 두뇌를 공급받을 것인가”에 대한 층이다.

원문에 나온 예시는 아래와 같다.

- OpenAI
- Anthropic
- Gemini
- OpenRouter
- DeepSeek
- Kimi
- NVIDIA NIM
- 기타 지원 Provider

쉽게 비유하면, Hermes Agent가 직원이라면 `LLM Provider`는 그 직원이 필요할 때 연결해 쓰는 **두뇌 공급처**라고 볼 수 있다.

중요한 점은 Hermes Agent가 특정 모델 하나에 묶여 있지 않다는 것이다. 상황에 따라 다른 모델을 고를 수 있다는 건, 실제 운영에서 꽤 큰 장점이다.

- 글쓰기에는 A 모델
- 코드 수정에는 B 모델
- 빠른 초안에는 C 모델

이런 식의 선택지가 열린다.

## 7. MCP의 역할

원문이 잘 짚은 것처럼, MCP는 Hermes의 백엔드 그 자체가 아니다. **Hermes Agent가 외부 도구와 서비스를 연결할 수 있게 해 주는 표준 인터페이스**라고 보는 편이 맞다.

원문의 정리 구조는 아래와 같다.

```text
Hermes Agent
 │
 ├─ 자체 Tool
 │   ├─ terminal
 │   ├─ read_file
 │   └─ write_file
 │
 └─ MCP
     ├─ GitHub
     ├─ Filesystem
     ├─ Database
     ├─ Notion
     └─ 기타 외부 서비스
```

쉽게 말하면:

- 자체 Tool = 몸에 붙어 있는 기본 도구
- MCP = 바깥 세상과 연결되는 멀티탭

그래서 MCP는 “Hermes를 만드는 부품”이라기보다, **Hermes가 바깥 세상에서 실제 일을 하게 만드는 연결 방식**이라고 보면 가장 덜 헷갈린다.

## 8. 아주 쉽게 비유하기

원문 표는 처음 보는 분에게 특히 유용하다.

| 기술 | 쉬운 비유 |
|---|---|
| Hermes3D | 사무실 |
| Hermes Agent | 직원 |
| LLM | 직원의 두뇌 |
| Tool | 직원이 사용하는 도구 |
| Skill | 직원이 익힌 업무 능력 |
| MCP | 외부 도구를 연결하는 멀티탭 |
| Claude / Codex / Gemini | 선택할 수 있는 여러 종류의 두뇌 |
| Session | 직원이 현재 진행 중인 업무 |
| Context | 직원이 기억하고 있는 업무 내용 |

이 표를 기억해두면, 이후 비슷한 도구를 볼 때도 바로 이해가 빨라진다. 특히 `Tool`, `Skill`, `MCP`를 구분하는 데 도움이 된다.

## 9. 기존 AI 에이전트 관리 방식과 차이

원문이 말하는 문제의식은 아주 현실적이다. 예전에는 여러 AI 에이전트를 쓸 때 보통 터미널을 여러 개 켜두고 상태를 따로따로 보는 경우가 많았다.

```text
Terminal 1 → Claude Code
Terminal 2 → Codex
Terminal 3 → Agent A
Terminal 4 → Agent B

로그...
로그...
로그...
로그...
```

이 방식의 단점은 한눈에 안 들어온다는 점이다.

Hermes3D가 지향하는 방식은 이걸 공간적으로 바꾸는 것이다.

```text
┌────────────── AI Company ──────────────┐

  개발팀          QA팀          조사팀

  Claude         Codex         Research
    ↓              ↓              ↓
 코드 작성       코드 리뷰       자료 조사

 사용자는 3D 사무실에서
 에이전트의 상태를 확인
└────────────────────────────────────────┘
```

즉 Hermes3D는 단순히 예쁘게 보이게 하려는 게 아니라, **“여러 에이전트의 역할과 상태를 한눈에 보게 하자”**는 문제의식에서 출발한다고 보는 편이 맞다.

## 10. Hermes3D가 흥미로운 이유

원문은 Hermes3D가 귀여운 3D 캐릭터 프로젝트가 아니라고 강조한다. 이 부분이 중요하다.

한 화면에 연결하려는 것은 결국 아래 묶음이다.

```text
LLM
 +
Agent Runtime
 +
Tool
 +
Skill
 +
MCP
 +
Multi-Agent
 +
3D UI
```

즉 Hermes3D는 단순 시각 효과보다, **AI Agent Management UI** 혹은 **Spatial AI Agent Interface**라는 더 큰 흐름 안에서 봐야 한다.

쉽게 말하면 “AI 직원들을 진짜 회사처럼 다루는 관리 화면”을 만들려는 시도라고 할 수 있다.

## 11. AI Agent Observability 관점

`Observability`라는 단어가 어렵게 느껴질 수 있는데, 여기서는 그냥 “에이전트가 지금 어떻게 돌아가고 있는지 잘 보이게 만드는 능력” 정도로 받아들이면 된다.

기존 Agent Observability 도구가 보통 보여주는 것은 아래와 같다.

- 현재 실행 중인 에이전트
- 작업 상태
- 로그
- Tool 호출
- 오류
- 토큰 사용량
- 세션
- 실행 결과

Hermes3D는 이런 정보를 카드나 표가 아니라 **공간적인 인터페이스(Spatial UI)** 로 표현하려는 접근이다.

즉 원문 표현을 그대로 살리면:

```text
Dashboard UI
 ↓
Spatial UI
```

로 바꾸는 시도다.

이건 단순히 “보기 좋다”의 문제가 아니다. 여러 에이전트가 동시에 돌 때는, 사람이 더 빨리 상태를 파악할 수 있는 인터페이스가 실제 생산성에도 영향을 줄 수 있다.

## 12. 활용 아이디어

원문은 Hermes3D를 실제 AI 개발팀처럼 구성하는 재미있는 실습 예도 제시한다.

예를 들어:

```text
기획자 : Hermes Agent
개발자 : Codex
리뷰어 : Claude Code
조사원 : Research Agent
QA : Testing Agent
```

그리고 전체 흐름은 아래처럼 잡을 수 있다.

```text
사용자
 ↓
Hermes3D
 ↓
기획 Agent
 ↓
Codex
 ↓
Claude Code 리뷰
 ↓
QA Agent 테스트
 ↓
결과 확인
```

이 구조는 아래 개념을 함께 학습하기에 좋은 사례가 된다.

- AI Agent
- Multi-Agent
- Agent Orchestration
- MCP
- Tool
- Skill
- LLM Provider
- CLI Agent
- Agent Observability
- Spatial UI

즉 Hermes3D는 “예쁜 데모 화면”을 넘어서, **AI 조직도를 실제로 눈앞에 펼쳐놓는 학습 재료**로도 가치가 있다.

## 13. 핵심 한 줄 정리

원문의 핵심 문장은 아래 한 줄로 잘 정리된다.

> **Hermes3D는 Hermes Agent를 중심으로 여러 AI 모델, Tool, Skill, MCP, Claude Code, Codex 등의 작업을 3D 가상 오피스 형태로 시각화하고 관리하려는 오픈소스 AI Agent Management UI입니다.**

이 문장을 다시 쉬운 말로 바꾸면 이렇다.

> Hermes3D는 여러 AI 직원이 어떤 일을 맡고 어디까지 진행했는지, 3D 사무실처럼 한눈에 보여주려는 관리 화면이다.

## 14. 가장 간단한 구조 요약

원문의 마지막 구조 요약도 매우 중요하다.

```text
[사용자]

   ↓

[Hermes3D]
3D 사무실 / UI

   ↓

[Hermes Agent]
AI Agent Runtime

   ↓

┌──────────────────────────┐
│ LLM Providers            │
│ Claude / GPT / Gemini 등 │
└──────────────────────────┘

 +

┌──────────────────────────┐
│ AI Coding Agents         │
│ Claude Code / Codex      │
└──────────────────────────┘

 +

┌──────────────────────────┐
│ Tool / Skill / MCP       │
│ GitHub / Files / DB 등   │
└──────────────────────────┘
```

이 구조를 머릿속에 넣어두면, 이후 Hermes3D를 직접 보더라도 어디가 UI이고 어디가 실행 엔진이며 어디가 외부 연결층인지 덜 헷갈린다.

## 15. 참고 링크

- Hermes3D
  <https://github.com/iamlukethedev/Hermes3D>

- Hermes Agent
  <https://github.com/NousResearch/hermes-agent>

이 글은 이번에 받은 원문 메모를 바탕으로, Hermes3D, Hermes Agent, Claude Code, Codex, LLM Provider, MCP 관계를 하나의 학습 글로 다시 정리한 것이다.

## 이 글을 읽은 뒤 이렇게 기억하면 된다

처음 보는 분이라면 모든 세부 기술을 한 번에 다 외울 필요는 없다. 아래 네 줄만 기억해도 충분하다.

- `Hermes3D`는 보여주는 화면이다.
- `Hermes Agent`는 실제로 일하는 본체다.
- `LLM Provider`는 두뇌 공급처다.
- `MCP`는 바깥 도구와 연결되는 표준 멀티탭이다.

여기까지 정리되면, 이후 Hermes3D를 다시 보게 될 때는 “3D 캐릭터가 귀엽네”에서 멈추지 않고, **AI 에이전트를 실제 회사처럼 운영하고 관찰하는 화면이구나** 하고 볼 수 있게 된다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>Hermes3D를 볼 때는 먼저 `화면(UI)`인지 `실행 엔진(runtime)`인지 구분해서 본다.</li>
  <li>`Hermes3D`와 `Hermes Agent`를 같은 것으로 섞어 생각하지 않는다.</li>
  <li>`MCP`는 본체가 아니라 외부 연결 표준이라는 점을 기억한다.</li>
  <li>Claude Code, Codex 같은 도구는 Hermes가 직접 품고 있다기보다 필요할 때 불러 쓰는 협업 대상으로 이해한다.</li>
  <li>이 프로젝트의 핵심은 3D 그래픽보다 `AI Agent Management UI`와 `Spatial Observability`라는 점을 놓치지 않는다.</li>
</ul>

## 남겨둘 판단

Hermes3D는 지금 당장 모든 사람이 꼭 써야 할 필수 도구라기보다, **앞으로 AI 에이전트를 한두 개가 아니라 여러 역할로 굴리게 될 때 관리 화면이 어떻게 바뀔 수 있는지 보여주는 꽤 앞선 실험**으로 보는 편이 맞다. 그래서 이 프로젝트를 볼 때는 “와, 3D네”보다 “여러 AI가 함께 일할 때 사람은 어떤 화면으로 그 상태를 읽게 될까?”라는 질문으로 읽는 쪽이 훨씬 남는 것이 많다.
