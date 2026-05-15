---
title: 2026-05-09 · 운영이 실력을 이긴다 · 릴리스 30건
description: AI 에이전트, LLM Wiki, 로컬 AI, 코딩 하네스, 브라우저 도구까지 30개 자료를 다시 묶어 지금 흐름의 무게중심이 운영 구조로 옮겨가고 있음을 정리한 글
tags:
  - curation
  - ai-trends
  - ai-automation
  - local-llm
  - developer-tools
  - corner-of-the-corner
created: "2026-05-09"
modified: "2026-05-09"
publish: true
cssclasses:
  - quick-note
---

# 2026-05-09 · 운영이 실력을 이긴다 · 릴리스 30건

요즘 AI 흐름을 제대로 따라가려면, 새 모델 발표만 봐서는 부족하다.

정작 현장에서는 모델 성능표보다 더 많이 이야기되는 게 있다. 에이전트를 어떻게 오래 굴릴지, 지식을 어떻게 쌓을지, 로컬 환경과 브라우저를 어떻게 작업 공간으로 바꿀지, 그리고 생성 결과물을 어떻게 실제 배포물 수준까지 끌어올릴지 같은 문제들이다.

한마디로 말하면, 관심의 중심이 “무슨 모델이 더 똑똑한가”에서 “AI를 어떻게 일하게 만들 것인가”로 옮겨가고 있다.

이번 글은 바로 그 변화가 실제로 어디서 드러나는지 훑어보기 위해 정리했다.

## 먼저 결론

- 최근 흐름의 중심은 더 이상 “어떤 모델이 더 똑똑한가”보다 **AI를 어떻게 연결하고 운영할 것인가** 쪽에 있다.
- 특히 **에이전트 + 메모리 + 로컬 도구 + 브라우저 + 워크플로우 설계**가 한 덩어리로 움직이고 있다는 점이 눈에 띈다.
- RAG 하나로 끝내기보다, **LLM Wiki나 개인 지식 그래프처럼 지식을 축적하고 갱신하는 구조**에 대한 관심이 확실히 커졌다.
- 코딩 쪽에서는 Claude Code, Codex, Gemini 같은 모델 자체보다 **하네스, 플러그인, 세션 리포트, 비교 실험** 같은 운영 레이어가 더 중요해지고 있다.
- 콘텐츠 제작에서도 그냥 생성하는 것보다, **사람답게 다듬고 실제 배포물로 마감하는 후처리 도구**가 점점 더 중요해지는 분위기다.

## 이번 글을 쓰며 참고한 자료

이번에 흐름을 다시 읽기 위해 가장 먼저 참고한 자료는 <strong>「최근 AI·기술 동향 학습 큐레이션」</strong>이었다.

구성은 좋았다.

- 전체 흐름 요약
- 추천 학습 순서
- 30개 항목의 주제별 재분류
- 각 항목별 짧은 설명
- 원본 링크와 LilysAI 공개 요약 링크

그래서 이 글에서는 30개 항목을 그대로 다시 옮기기보다, **지금 읽어둘 만한 큰 흐름과 대표 사례** 위주로 정리해 본다.

## 이번 묶음에서 가장 크게 보인 다섯 가지

### 1) AI 에이전트는 이제 "대화 상대"보다 "작업 시스템"에 가까워지고 있다

이번 자료에서 가장 강한 축은 역시 에이전트였다.

예전에는 챗봇에게 잘 묻는 법, 프롬프트 잘 쓰는 법이 중심이었다면, 지금은 훨씬 운영형이다.

- 역할을 분담한 멀티 에이전트 팀을 꾸리고
- 스킬과 메모리를 붙이고
- 텔레그램이나 브라우저, 로컬 도구와 연결하고
- 장시간 작업 흐름을 유지하는 방식

이쪽 결을 가장 잘 보여주는 항목은 이런 것들이었다.

- [Hermes Agent 사례집](https://hermes-agent.nousresearch.com/docs/user-stories)
- [DOT Studio](https://github.com/dance-of-tal/dot-studio)
- [Claude · Codex · Gemini 셋이서 한 작업 — AI Dev Team 데모](https://www.youtube.com/watch?v=ly5CUJwelFc)
- [Hermes 에이전트 리뷰](https://www.youtube.com/watch?v=dVMu7vcej14)

핵심은 “AI가 답을 잘하느냐”가 아니라, **AI가 사람 일의 일부를 맡아 오래 굴러가게 만들 수 있느냐**다.

### 2) LLM Wiki와 개인 지식 시스템은 RAG의 보완재가 아니라 사실상 다른 철학이다

이번 묶음에서 두 번째로 인상적이었던 건 지식관리 쪽이었다.

특히 아래 흐름이 반복해서 등장했다.

- 로컬 문서를 요약하고
- 핵심 엔티티를 뽑고
- 연결 관계를 만들고
- 시간이 지나면 다시 갱신하는 구조

이건 단순한 검색 보조가 아니라, **AI가 다시 읽을 수 있는 개인용 위키를 만든다**는 쪽에 더 가깝다.

대표적으로는 아래 자료들이 눈에 남았다.

- [Ollama, LangChain, Obsidian으로 LLM Wiki 구축하기](https://www.youtube.com/watch?v=l4EzuMKmeA0)
- [Karpathy LLM Wiki + InfraNodus](https://www.youtube.com/watch?v=t61HGh4NsPs)
- [LLM WIKI 구축 스킬](https://github.com/infranodus/skills/blob/master/skill-llm-wiki/SKILL.md)
- [Local LLM Wiki 활용법](https://www.youtube.com/watch?v=YCirjfAurng)

개인적으로는 이 흐름이 꽤 중요해 보였다. 앞으로는 “찾아보는 AI”보다 **축적한 지식을 다시 엮어 쓰는 AI**가 더 실전적일 수 있어서다.

### 3) 코딩 에이전트의 생산성은 모델보다 하네스와 워크플로우가 더 크게 좌우한다

이제 Claude Code, Codex, Gemini 같은 이름은 익숙해졌다. 그런데 실제 생산성을 가르는 건 모델 이름보다 **주변 설계**인 경우가 많다.

예를 들면 이런 것들이다.

- 플러그인을 어떻게 붙이는지
- 세션 리포트를 어떻게 남기는지
- 코드베이스 검색을 어떻게 줄이는지
- 같은 과제를 어떤 하네스로 돌렸을 때 비용과 결과가 어떻게 달라지는지

이번 자료에서 이 흐름은 아래 항목들이 잘 보여줬다.

- [클로드 코드 공식 플러그인 4개로 토큰 절약 끝](https://www.youtube.com/watch?v=L94yAQR9VvA)
- [AI 코딩 하네스 벤치마크 결과](https://github.com/first-fluke/oh-my-agent/blob/main/benchmarks/README.ko.md)
- [Ouroboros](https://github.com/Q00/ouroboros)
- [Codex vs Claude Code 랜딩 페이지 제작 비교](https://www.youtube.com/watch?v=pN6jugUyeLk)

결국 코딩 에이전트도 “좋은 모델 하나”보다, **좋은 문제 정의 + 좋은 컨텍스트 + 좋은 운영 습관**이 더 크게 먹힌다.

### 4) 로컬 AI와 브라우저 도구는 이제 취미 영역이 아니라 실전 작업 환경이 되고 있다

이번 큐레이션에서 은근히 강했던 또 하나의 축은 로컬 환경이었다.

- LM Studio로 로컬 모델 돌리기
- PC 문서를 통째로 검색하는 로컬 검색 엔진
- 브라우저 안에서 Gemini가 멀티탭 비교와 요약을 하는 흐름
- USB 드라이브에서 Claude Code를 실행하는 아이디어
- Cloudflare Tunnel로 로컬 개발 환경을 외부와 연결하는 방식

대표 항목은 이쪽이다.

- [Gemini Chrome 업데이트](https://www.youtube.com/watch?v=GDwX09tMMzI)
- [Docufinder](https://github.com/chrisryugj/Docufinder)
- [LM Studio](https://www.youtube.com/watch?v=OOCioZC4tk0)
- [USB 드라이브에서 Claude Code 실행하기](https://www.youtube.com/watch?v=9Dh3kKWFFjg)
- Cloudflare Tunnel 관련 노트

예전에는 이런 게 다소 실험적으로 느껴졌는데, 지금은 오히려 **개인 작업실을 확장하는 기본기**처럼 보이기 시작했다.

### 5) 글쓰기와 콘텐츠 제작은 생성보다 후처리가 중요해졌다

마지막으로 눈에 띈 건 글쓰기와 콘텐츠 품질 관리였다.

이제는 “AI가 초안을 만들 수 있다”는 사실 자체는 별로 새롭지 않다. 대신 더 중요해진 건,

- AI 티를 얼마나 줄일 수 있는지
- 강의 영상을 얼마나 잘 구조화된 노트로 바꿀 수 있는지
- 슬라이드나 문서를 얼마나 실제 배포물처럼 마감할 수 있는지

였다.

이 흐름과 닿아 있는 자료는 아래처럼 보였다.

- [Master of Slide](https://github.com/reallygood83/master-of-slide)
- [Humanizer](https://github.com/blader/humanizer)
- [im-not-ai](https://github.com/epoko77-ai/im-not-ai)
- [Claude Watch](https://github.com/devinilabs/claude-watch)

이건 그냥 편집 기술 얘기가 아니라, 생성형 AI 시대에 **결과물의 마지막 20%를 어떻게 책임질 것인가**에 대한 얘기이기도 하다.

## 내가 다시 보고 싶은 항목 몇 개

30개를 다 다시 보기는 쉽지 않아서, 지금 기준으로 특히 다시 읽을 만한 것만 추리면 이렇다.

### 1) Master of Slide

React 기반 슬라이드 제작 흐름을 어떻게 에이전트 친화적으로 만들 수 있는지 보여준다.

- 원본: <https://github.com/reallygood83/master-of-slide>
- 요약: <https://lilys.ai/digest/9481835/10935258?s=1&noteVersionId=7453620>

### 2) Claude Code 플러그인 4개 자료

토큰 절약, 세션 리포트, 검색 최적화 같은 실무 운영 감각을 보기 좋다.

- 원본: <https://www.youtube.com/watch?v=L94yAQR9VvA>
- 요약: <https://lilys.ai/digest/9466550/10915773?s=1&noteVersionId=7432810>

### 3) Ollama/LangChain/Obsidian LLM Wiki

RAG와는 다른 방식으로 지식을 쌓아가는 감각을 익히기에 좋다.

- 원본: <https://www.youtube.com/watch?v=l4EzuMKmeA0>
- 요약: <https://lilys.ai/digest/9477304/10929512?s=1&noteVersionId=7447678>

### 4) Docufinder

로컬 문서 검색이 어디까지 실용적일 수 있는지 보기에 괜찮다.

- 원본: <https://github.com/chrisryugj/Docufinder>
- 요약: <https://lilys.ai/digest/9444394/10888058?s=1&noteVersionId=7402286>

### 5) Humanizer / im-not-ai

결과물을 실제 배포 문장으로 다듬는 마지막 레이어가 왜 필요한지 바로 체감된다.

- Humanizer 원본: <https://github.com/blader/humanizer>
- Humanizer 요약: <https://lilys.ai/digest/9468252/10917945?s=1&noteVersionId=7435540>
- im-not-ai 원본: <https://github.com/epoko77-ai/im-not-ai>
- im-not-ai 요약: <https://lilys.ai/digest/9468018/10917660?s=1&noteVersionId=7435235>

## 추천 학습 순서도 괜찮았다

원문 자료에는 추천 학습 순서도 같이 들어 있었다. 그중에서 지금 바로 써먹기 좋은 흐름만 다시 정리하면 이렇다.

### 60분 빠른 훑기

1. 에이전트와 코딩 워크플로우부터 본다.
2. 그다음 LLM Wiki와 개인 지식 시스템을 본다.
3. 마지막으로 로컬 AI와 브라우저 도구 쪽을 붙여 본다.

### 반나절 깊게 보기

1. 에이전트 개발 환경과 하네스를 먼저 읽고
2. 지식 관리 구조를 보고
3. 콘텐츠 제작과 후처리 도구를 확인한 뒤
4. 로컬 개발 환경 확장 도구로 마무리한다.

이 순서가 좋은 이유는 간단하다. 요즘 AI 흐름은 점점 **모델 → 운영 → 저장 → 배포** 순으로 연결되고 있기 때문이다.

## 실제로 한 것

1. 30개 자료를 그대로 복붙하지 않고, 반복해서 등장하는 주제부터 다시 묶어 봤다.
2. AI 에이전트, 지식 시스템, 코딩 하네스, 로컬 도구, 콘텐츠 후처리라는 다섯 축으로 다시 읽었다.
3. 그중에서도 지금 흐름을 가장 잘 보여주는 대표 항목만 다시 골라 블로그에서 읽기 쉬운 구조로 정리했다.

## 막혔던 지점

> 원문 자료는 훌륭한 학습 팩이었지만, 블로그 글로 옮기려면 정보가 조금 더 기울어져야 했다.

각 항목 설명은 이미 충분히 정리돼 있었지만, 그대로 옮기면 “그래서 지금 가장 중요한 변화가 뭔가?”가 조금 흐려질 수 있었다. 그래서 이번 글에서는 목록을 다 싣기보다, **이번 묶음이 가리키는 방향**을 앞쪽에 세우는 쪽으로 정리했다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>링크 묶음을 읽을 때는 먼저 “이번에 반복해서 보이는 주제가 무엇인가”부터 잡는다.</li>
  <li>모델 이름보다 운영 구조, 메모리, 연결 방식이 더 자주 나오는지 본다.</li>
  <li>개별 항목은 다 소개하지 말고, 흐름을 대표하는 4~6개만 고르면 글의 밀도가 좋아진다.</li>
  <li>학습 큐레이션은 저장보다 재분류가 중요하다. 같은 자료도 다시 묶으면 전혀 다른 그림이 보인다.</li>
</ul>

## 남겨둘 판단

이번 30개 자료를 훑고 나서 가장 또렷했던 건 하나다.

이제 AI의 중심축은 “똑똑한 답변”에서 멈추지 않는다.

사람들은 점점 더,

- AI에게 역할을 나눠주고
- 기억을 붙이고
- 로컬 환경과 연결하고
- 브라우저와 문서, 개발 도구까지 묶어서
- 오래 쓸 수 있는 작업 시스템으로 만들고 있다.

그래서 요즘 흐름을 따라갈 때도, 새 모델 발표만 쫓는 것보다 **에이전트를 어떻게 운영하고, 지식을 어떻게 축적하고, 결과물을 어떻게 마감하는지**를 같이 보는 편이 훨씬 남는 게 많다.

## 참고 자료

아래 표는 이번 글을 쓰면서 다시 참고한 30개 자료를 주제별로 정리한 것이다. 제목만 모아두면 다시 찾기 불편해서, 한 줄 요약과 원문 링크, LilysAI 공개 링크까지 같이 붙였다.

### 1. AI 에이전트와 코딩 워크플로우

| 제목 | 한 줄 요약 | 원문 링크 | 릴리스 AI 공개 링크 |
|---|---|---|---|
| Master of Slide | React와 Markdown 기반으로 슬라이드를 만들고 HTML·PDF·PPTX까지 연결하는 에이전트 친화형 발표 자료 도구 | [원문](https://github.com/reallygood83/master-of-slide) | [요약](https://lilys.ai/digest/9481835/10935258?s=1&noteVersionId=7453620) |
| User Stories & Use Cases \/ Hermes Agent | Hermes Agent를 병렬 운용, 자동화, 조사 작업에 실제로 적용한 사례를 모은 활용 사례집 | [원문](https://hermes-agent.nousresearch.com/docs/user-stories) | [요약](https://lilys.ai/digest/9469768/10920072?s=1&noteVersionId=7437836) |
| New Note | Hermes Agent 활용 사례를 다시 스크랩해 빠르게 훑어볼 수 있게 정리한 재확인용 항목 | [원문](https://hermes-agent.nousresearch.com/docs/user-stories) | [요약](https://lilys.ai/digest/9469767/10920071?s=1&noteVersionId=7437835) |
| DOT Studio | AI 에이전트의 역할과 협업 구조를 시각적으로 설계하는 로컬 캔버스형 작업 공간 | [원문](https://github.com/dance-of-tal/dot-studio) | [요약](https://lilys.ai/digest/9468361/10918087?s=1&noteVersionId=7435692) |
| Adam | C 언어로 만든 임베디드 AI 에이전트 라이브러리로 도구 호출, 메모리, 세션을 직접 내장하게 돕는 프로젝트 | [원문](https://github.com/sqliteai/adam) | [요약](https://lilys.ai/digest/9468348/10918064?s=1&noteVersionId=7435669) |
| 클로드 코드 공식 플러그인 4개로 토큰 절약 끝 | Claude Code 플러그인과 세션 리포트, Serena MCP를 활용해 비용과 컨텍스트 낭비를 줄이는 운영 자료 | [원문](https://www.youtube.com/watch?v=L94yAQR9VvA) | [요약](https://lilys.ai/digest/9466550/10915773?s=1&noteVersionId=7432810) |
| AI 코딩 하네스 벤치마크 결과 | 같은 프롬프트로 여러 Claude Code 하네스를 비교해 품질과 비용, UI 차이를 살펴본 벤치마크 | [원문](https://github.com/first-fluke/oh-my-agent/blob/main/benchmarks/README.ko.md) | [요약](https://lilys.ai/digest/9444489/10888174?s=1&noteVersionId=7402403) |
| Claude · Codex · Gemini 셋이서 한 작업 — AI Dev Team 데모 | 여러 코딩 에이전트를 역할 분담시켜 단일 에이전트보다 더 객관적인 협업 흐름을 만드는 데모 | [원문](https://www.youtube.com/watch?v=ly5CUJwelFc) | [요약](https://lilys.ai/digest/9444069/10887637?s=1&noteVersionId=7401858) |
| Ouroboros | 모호한 아이디어를 질문과 온톨로지 분석으로 명확한 개발 사양으로 바꾸는 시스템 | [원문](https://github.com/Q00/ouroboros) | [요약](https://lilys.ai/digest/9441279/10883958?s=1&noteVersionId=7398039) |
| Hermes 에이전트 리뷰: 670 스킬, LLM Wiki, 텔레그램 봇 연동까지 | Hermes Agent를 스킬, 메모리, LLM Wiki, 텔레그램 연동 관점에서 정리한 종합 리뷰 | [원문](https://www.youtube.com/watch?v=dVMu7vcej14) | [요약](https://lilys.ai/digest/9441016/10883572?s=1&noteVersionId=7397646) |

### 2. LLM Wiki와 개인 지식 시스템

| 제목 | 한 줄 요약 | 원문 링크 | 릴리스 AI 공개 링크 |
|---|---|---|---|
| Ollama, LangChain, Obsidian으로 Karpathy의 LLM Wiki 구축하기 | 로컬 문서를 요약하고 핵심 엔티티를 연결해 개인 지식 베이스를 점진적으로 확장하는 방법 | [원문](https://www.youtube.com/watch?v=l4EzuMKmeA0) | [요약](https://lilys.ai/digest/9477304/10929512?s=1&noteVersionId=7447678) |
| Android에 Hermes 설치: Termux로 AI 에이전트 돌리기 | 안드로이드 Termux에서 Hermes를 돌리고 메시지를 Obsidian과 LLM Wiki로 저장하는 흐름 | [원문](https://www.youtube.com/watch?v=xw4afp4-j9o) | [요약](https://lilys.ai/digest/9466679/10915863?s=1&noteVersionId=7432925) |
| Karpathy LLM Wiki + InfraNodus | LLM Wiki에 지식 그래프를 결합해 연결의 빈틈과 새로운 질문을 발견하는 방법 | [원문](https://www.youtube.com/watch?v=t61HGh4NsPs) | [요약](https://lilys.ai/digest/9466640/10915820?s=1&noteVersionId=7432869) |
| LLM WIKI 구축 | 원문 수집, 구조화, 교차 참조, 갱신 흐름으로 개인 위키 자동화를 설명하는 스킬 문서 | [원문](https://github.com/infranodus/skills/blob/master/skill-llm-wiki/SKILL.md) | [요약](https://lilys.ai/digest/9456753/10903723?s=1&noteVersionId=7418476) |
| Local LLM Wiki 활용법 | 로컬 LLM으로 개인 노트를 인덱싱하고 외부 LLM과 연결해 지식 업데이트를 자동화하는 활용법 | [원문](https://www.youtube.com/watch?v=YCirjfAurng) | [요약](https://lilys.ai/digest/9443748/10887234?s=1&noteVersionId=7401442) |

### 3. 글쓰기, 학습 노트, 콘텐츠 품질 개선

| 제목 | 한 줄 요약 | 원문 링크 | 릴리스 AI 공개 링크 |
|---|---|---|---|
| Humanizer, 사람처럼 글쓰기 | AI 문체를 줄이고 더 자연스러운 사람 문장으로 다듬는 후처리 스킬 | [원문](https://github.com/blader/humanizer) | [요약](https://lilys.ai/digest/9468252/10917945?s=1&noteVersionId=7435540) |
| im-not-ai, 한글 AI 티 제거기 | 한국어 글에서 번역투와 기계적 병렬을 줄여 더 자연스러운 문장으로 바꾸는 스킬 | [원문](https://github.com/epoko77-ai/im-not-ai) | [요약](https://lilys.ai/digest/9468018/10917660?s=1&noteVersionId=7435235) |
| Claude Watch, 강의 영상을 구조화된 학습 노트로 변환 | 강의 영상을 타임스탬프와 스크린샷이 있는 Markdown 학습 노트로 바꾸는 도구 | [원문](https://github.com/devinilabs/claude-watch) | [요약](https://lilys.ai/digest/9461964/10910265?s=1&noteVersionId=7425371) |

### 4. 로컬 AI, 브라우저, 개인 개발 환경 도구

| 제목 | 한 줄 요약 | 원문 링크 | 릴리스 AI 공개 링크 |
|---|---|---|---|
| Gemini Chrome 업데이트 | Chrome 안에서 Gemini가 페이지 요약, 이미지 이해, 멀티탭 비교를 수행하는 흐름을 정리한 자료 | [원문](https://www.youtube.com/watch?v=GDwX09tMMzI) | [요약](https://lilys.ai/digest/9461108/10909193?s=1&noteVersionId=7424096) |
| Docufinder, PC 문서를 통째로 검색하는 로컬 검색 엔진 | 파일명뿐 아니라 문서 본문으로 검색하고 선택적으로 AI 요약까지 제공하는 로컬 검색 도구 | [원문](https://github.com/chrisryugj/Docufinder) | [요약](https://lilys.ai/digest/9444394/10888058?s=1&noteVersionId=7402286) |
| Codexy-pet-usage-ring | Codex Desktop의 사용량 제한을 링 형태로 시각화해 작업 리듬을 관리하게 돕는 보조 도구 | [원문](https://github.com/himomohi/Codexy-pet-usages-ring) | [요약](https://lilys.ai/digest/9444346/10888008?s=1&noteVersionId=7402234) |
| LM Studio로 로컬 AI 모델 실행하기 | 로컬 컴퓨터에서 AI 모델을 실행하는 기본 방법과 장점을 설명하는 입문 자료 | [원문](https://www.youtube.com/watch?v=OOCioZC4tk0) | [요약](https://lilys.ai/digest/9444232/10887857?s=1&noteVersionId=7402081) |
| USB 드라이브에서 Claude Code 실행하기 | USB 드라이브에서 이동식 AI 코딩 환경을 실행하는 아이디어를 보여주는 실험적 자료 | [원문](https://www.youtube.com/watch?v=9Dh3kKWFFjg) | [요약](https://lilys.ai/digest/9444150/10887749?s=1&noteVersionId=7401971) |
| Chromex, Codex 크롬브라우저 사이드 패널 | Chrome 사이드패널과 로컬 브리지로 Codex를 연결해 페이지·파일·브라우저 작업을 붙이는 도구 | [원문](https://github.com/GENEXIS-AI/chromex) | [요약](https://lilys.ai/digest/9430764/10870943?s=1&noteVersionId=7384676) |
| Cloudflare Tunnel | 로컬 프로젝트를 포트 포워딩 없이 외부에 공개해 테스트와 원격 작업 연결에 쓰는 가이드 | 텍스트 노트 | [요약](https://lilys.ai/digest/9428171/10867563?s=1&noteVersionId=7381163) |

### 5. 바이브코딩, 웹 개발, 결과물 비교

| 제목 | 한 줄 요약 | 원문 링크 | 릴리스 AI 공개 링크 |
|---|---|---|---|
| 바이브패밀리 — 할일 관리 앱 DOOOZ 개발기 | 가족용 할일 관리 앱을 AI와 대화하며 실제 제품으로 구체화한 바이브코딩 사례 | [원문](https://www.youtube.com/watch?v=G4VliKcuxHo) | [요약](https://lilys.ai/digest/9480751/10933897?s=1&noteVersionId=7452229) |
| 비개발자 바이브코더를 위한 웹서버 및 배포 지식 | 서버, 도메인, DNS, 데이터베이스, 배포 같은 웹 기본기를 정리한 입문 강의 | [원문](https://www.youtube.com/watch?v=rESpjQLptUs) | [요약](https://lilys.ai/digest/9461062/10909165?s=1&noteVersionId=7424066) |
| Codex vs Claude Code, 기업 소개 랜딩 페이지 제작 비교 | 같은 랜딩 페이지 과제를 Codex와 Claude Code가 어떻게 다르게 푸는지 비교한 자료 | [원문](https://www.youtube.com/watch?v=pN6jugUyeLk) | [요약](https://lilys.ai/digest/9443778/10887272?s=1&noteVersionId=7401480) |

### 6. 하드웨어와 IoT

| 제목 | 한 줄 요약 | 원문 링크 | 릴리스 AI 공개 링크 |
|---|---|---|---|
| Arduino Uno Q 핵심 정리 | Linux와 AI까지 실행 가능한 Arduino Uno Q의 확장된 성격을 다룬 하드웨어 정리 자료 | [원문](https://www.youtube.com/watch?v=HjcXwTvOz9o) | [요약](https://lilys.ai/digest/9443924/10887431?s=1&noteVersionId=7401643) |
| 맹구 코덱스 펫 | Codex 작업 환경에 커스텀 펫을 추가해 사용 경험을 개인화하는 작은 프로젝트 | [원문](https://github.com/bible-highting/maang9-codex-pet) | [요약](https://lilys.ai/digest/9462171/10910522?s=1&noteVersionId=7425685) |
