---
title: 2026-05-23 · 작업 환경이 본체가 된다 · 릴리스 50건
description: Codex, Claude Code, Hermes, 로컬 AI, 문서 포맷, 브라우저 자동화까지 최근 50개 자료를 다시 묶어보니 이제 AI 경쟁의 본체가 모델보다 작업 환경과 운영 구조 쪽으로 이동하고 있었다.
tags:
  - curation
  - ai-trends
  - ai-automation
  - developer-tools
  - local-ai
  - corner-of-the-corner
created: "2026-05-23"
modified: "2026-05-23"
publish: true
cssclasses:
  - quick-note
---

# 2026-05-23 · 작업 환경이 본체가 된다 · 릴리스 50건

이번에 받은 <strong>「최근 50개 LilysAI 노트 학습 큐레이션」</strong>을 다시 읽으며 가장 먼저 든 생각은 단순했다.

이제 사람들은 AI를 “잘 대답하는 모델”로만 보지 않는다. 어떤 도구를 붙여서 움직이게 할지, 어떤 메모리 구조를 쌓을지, 어떤 문서 포맷으로 넘길지, 어떤 인터페이스에서 실무까지 이어지게 할지가 더 중요해지고 있다. 이번 50개 자료는 바로 그 이동을 꽤 선명하게 보여주는 묶음이었다.

## 먼저 결론

- 지금 AI 흐름의 무게중심은 모델 비교보다 **작업 환경 설계와 운영 체계** 쪽으로 이동하고 있다.
- Codex, Claude Code, Hermes, Obsidian, LM Studio, 브라우저 자동화, 메신저 연결 도구가 한 묶음으로 반복해서 등장하는 건 우연이 아니다.
- 문서 포맷, 스킬 문서, DESIGN.md, LLM Wiki 같은 자료가 같이 보인다는 건 AI 협업의 인터페이스가 이제 채팅창 밖으로 넓어졌다는 뜻이다.
- 로컬 AI와 개인 지식베이스는 취미 영역이 아니라, 민감한 자료와 장기 기억을 다루는 **개인 AI 작업실 설계 문제**로 넘어가고 있다.
- 이런 큐레이션은 링크를 다 읽는 것보다, 무엇이 반복해서 나타나는지 먼저 보는 편이 훨씬 남는다.

## 왜 이번 50선이 유독 또렷했나

요즘 큐레이션은 많다. 하지만 이번 자료는 링크를 나열하는 데서 멈추지 않고, 이미 한 차례 주제별로 정리되어 있었고, 각 항목마다 “무엇인가 / 왜 볼까 / 원본 / 공개 요약”이 붙어 있었다. 그래서 다시 읽는 입장에서는 자료 하나하나보다 **전체 흐름의 반복**이 더 잘 보였다.

특히 좋았던 건 아래 다섯 축이었다.

1. 코딩 에이전트가 IDE 보조를 넘어 운영 체계가 되는 흐름
2. 로컬 AI와 개인 메모리 구조가 다시 중요해지는 흐름
3. 문서 포맷과 화면 구조가 실행 컨텍스트가 되는 흐름
4. 메신저·브라우저·터미널을 넘나드는 인터페이스 자동화 흐름
5. 텍스트 생성 이후 입력 수집과 출력 전달이 병목이 되는 흐름

## 이번 묶음에서 가장 크게 보인 다섯 가지 변화

### 1) 에이전트는 코딩 도구가 아니라 운영 체계가 되고 있다

이번 50선의 중심축은 분명 이쪽이었다.

Codex, Claude Code, Antigravity, Warp, K-Skill, Engineering Discipline, Agentation 같은 자료를 한 줄로 세우고 보면, 공통 질문이 비슷하다.

- 어떤 모델이 더 좋은가?
- 어떤 답변이 더 길고 똑똑한가?

가 아니라,

- 역할을 어떻게 나눌까?
- 검증 루프는 어떻게 붙일까?
- 하네스는 어떻게 만들까?
- 스킬을 어떤 단위로 쪼갤까?
- 팀 안에서 결과를 어떻게 공유할까?

가 핵심이 된다.

그래서 이번 묶음에서 반복적으로 인상적이었던 자료는 이런 것들이었다.

- K-Skill
- Codex use cases
- Claude Code, Codex, Hermes Agent 실무자 가이드
- 멀티 에이전트 시스템 운영 사례
- Codex 하네스 설계 자료
- Codex Discord Connector

정리하면 이렇다.

> AI는 이제 “잘 쓰는 프롬프트”의 문제가 아니라, “오래 굴러가는 작업 환경”의 문제가 되고 있다.

### 2) 로컬 AI와 개인 지식베이스는 다시 핵심 인프라가 된다

Alt, Ollama, LM Studio, Hermes Memory Stack, Obsidian LLM Wiki 자료가 한쪽에 묶여 등장한 것도 중요했다.

한동안은 클라우드 모델만 잘 쓰면 되는 것처럼 보였지만, 민감한 회의 내용, 장기 기억, 개인 지식베이스, 반복되는 사내 문서 작업을 생각하면 결국 질문은 다시 이쪽으로 돌아온다.

- 내 자료를 어디에 쌓을까?
- 누가 읽을 수 있게 정리할까?
- 로컬에서 어느 정도까지 처리할까?
- 개인 에이전트가 기억을 어떻게 이어가게 할까?

이번 자료에서 그 고민을 잘 보여준 항목은 아래였다.

- Alt 로컬 AI 노트 도구
- OpenClaw와 Hermes Agent의 차이점
- LLM Wiki가 망하는 진짜 이유
- Hermes Memory Stack
- Obsidian 기반 LLM Wiki 사례
- M5 Max 로컬 LLM 세팅 가이드

예전엔 “좋은 앱 추천”으로 보이던 자료가, 지금은 **개인 AI OS 설계 참고서**처럼 읽힌다.

### 3) 문서 포맷이 곧 AI 협업 인터페이스가 되고 있다

이번 파일에서 내가 특히 반가웠던 대목은 HTML, DESIGN.md, 스킬 문서, LLM Wiki 같은 항목이 자연스럽게 같은 흐름으로 읽혔다는 점이다.

이건 생각보다 중요한 변화다.

이제 문서는 사람만 읽는 설명서가 아니다.
AI도 그 문서를 읽고,
- 규칙을 가져가고
- 문맥을 이어받고
- 실행 기준을 참고하고
- 다음 결과물을 맞춰낸다.

그래서 HTML 부상, DESIGN.md, 스킬 구조, 위키형 문서가 전부 따로 놀지 않고 한 묶음으로 보인다.

이건 결국 이런 뜻이다.

> 문서 형식은 이제 단순 전달 수단이 아니라, 에이전트가 실제로 일하는 작업 표면이다.

### 4) 자동화는 특정 앱 안에 갇히지 않는다

LangBot, Codex Discord Connector, CloakBrowser, CokacDIR 같은 항목을 보면 방향이 명확하다.

AI는 더 이상 특정 서비스 안에서만 답을 쓰는 존재가 아니다.
점점 더
- 메신저에서 답하고
- 브라우저에서 움직이고
- 터미널에서 파일을 다루고
- 다른 인터페이스로 결과를 넘긴다.

이번 자료를 읽으며 느낀 건, 인터페이스 자동화가 “부가기능”이 아니라 **실무 연결층**이 되었다는 점이다. 에이전트가 실제로 쓸모 있으려면 결국 사람이 이미 쓰고 있는 화면과 도구 사이를 드나들 수 있어야 한다.

### 5) 멀티모달 입출력이 다음 병목이 된다

비디오 요약, 온디바이스 TTS, 네트워크 속도 자료가 같이 들어 있던 것도 그냥 곁가지로 보면 아쉽다.

이 자료들이 말하는 건 결국 하나다.

텍스트를 잘 만드는 것만으로는 끝나지 않는다. 이제 남는 문제는
- 긴 영상에서 필요한 장면을 어떻게 뽑을지
- 음성으로 어떻게 내보낼지
- 로컬 장비와 네트워크 병목을 어떻게 줄일지
- 입력 수집과 출력 전달을 얼마나 자연스럽게 연결할지

다시 말해, 이제는 생성 이후 단계가 점점 더 중요해진다.

## 그래서 이 50개를 어떻게 읽는 게 좋은가

처음부터 50개를 다 읽으려 들면 금방 흐려진다. 이번 자료는 오히려 순서를 나눠 읽을 때 더 힘이 있다.

### 1단계: 코딩 에이전트와 개발 워크플로
먼저 이 섹션으로 현재 도구 지형을 잡는 편이 좋다.

- K-Skill
- Codex use cases
- Claude Code 입문 recap
- 실무자 가이드
- 멀티 에이전트 시스템 운영 사례

여기까지 보면 왜 AI 논의가 모델 비교에서 운영 설계 쪽으로 이동하는지 감이 온다.

### 2단계: 로컬 AI, Hermes, 개인 AI OS
그다음은 내 작업실을 어떻게 바꿔야 할지 보는 단계다.

- Alt
- Hermes Memory Stack
- OpenClaw vs Hermes
- LLM Wiki / Obsidian 자료
- 로컬 LLM 세팅 가이드

이 흐름은 “AI를 잘 쓰는 사람”이 아니라 “AI가 계속 일할 수 있는 환경을 만든 사람”이 강해진다는 걸 보여준다.

### 3단계: 교육·문서·콘텐츠 자동화
수업, 회의, 문서, 마케팅 쪽 아이디어는 이 구간에서 많이 나온다.

- HTML의 부상
- 메모리 최신화 자료
- Honen
- 마케팅 자동화 입문
- STP 분석 자료

여기서는 결과물을 어떻게 재사용 가능한 자료로 바꾸는지가 핵심이다.

### 4단계: 브라우저·봇·멀티모달
마지막엔 확장 지점을 본다.

- LangBot
- Codex Discord Connector
- CloakBrowser
- NVIDIA VSS
- Supertonic

이 구간은 “다음 자동화 확장은 어디인가”를 생각할 때 특히 좋다.

## 이번 자료로 바로 떠오르는 활용 아이디어

원문에 적혀 있던 아이디어 씨앗도 꽤 좋았다. 그중에서도 실제로 바로 붙이기 쉬운 건 이쪽이다.

- 수업용: Claude / Codex / Hermes / Obsidian 네 갈래로 “AI 에이전트 작업환경 만들기” 워크숍 구성
- 업무용: 회의 녹취 → 로컬 요약 → Obsidian 지식베이스 → 공개 링크 배포 파이프라인
- 개발용: 스킬 단위로 입력, 출력, 검증 기준을 붙여 팀 지식으로 관리
- 콘텐츠용: HTML, DESIGN.md, LLM Wiki를 “AI가 읽는 문서 포맷” 시리즈로 확장

특히 이번엔 “자료를 보는 것”에서 끝나지 않고, **내 환경에 어떻게 번역할까**가 더 자연스럽게 따라왔다. 이런 큐레이션이 좋은 이유가 딱 그거다.

## 실제로 한 것

1. 50개 자료를 그대로 옮기지 않고, 반복해서 등장하는 운영 축부터 다시 묶었다.
2. 코딩 에이전트, 로컬 AI, 문서 포맷, 인터페이스 자동화, 멀티모달 인프라라는 다섯 축으로 재해석했다.
3. 블로그 글에서는 링크보다 “지금 어디에 무게가 실리는가”가 먼저 보이게 구조를 다시 세웠다.
4. 참고용으로는 원문이 가진 장점도 살리기 위해 전체 링크 표와 용어 정리를 뒤에 남겼다.

## 막혔던 지점

> 원문을 그대로 옮기면 훌륭한 링크 사전은 되지만, 블로그 글로서는 힘이 빠질 수 있었다.

자료 자체는 이미 정리가 잘 되어 있었다. 다만 블로그 글은 정보 보관함이 아니라, 독자가 “그래서 지금 무엇이 중요하냐”를 먼저 느끼게 해야 한다. 그래서 이번 글은 링크를 줄이기보다, **흐름을 더 세게 보이게 하는 방식**으로 다시 썼다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>학습 큐레이션은 링크를 그대로 옮기기 전에, 반복되는 축부터 먼저 다시 묶는다.</li>
  <li>모델 이름보다 운영 구조, 메모리, 연결 계층, 검증 루프가 얼마나 자주 등장하는지 본다.</li>
  <li>문서 포맷 자료가 보이면 “AI가 읽는 실행 컨텍스트” 관점으로 다시 읽는다.</li>
  <li>로컬 AI 자료는 취미 카테고리가 아니라 개인 AI 작업실 설계 문제로 다룬다.</li>
  <li>최종 글의 앞부분은 반드시 사람이 읽는 서사로 다시 세우고, 전체 링크 표는 뒤로 보낸다.</li>
</ul>

## 남겨둘 판단

이번 50개를 다시 묶고 나서 가장 또렷했던 건 결국 이것이다.

AI의 경쟁력은 점점 모델 하나의 성능보다,
- 어떻게 연결하는가
- 어디에 저장하는가
- 어떤 형식으로 넘기는가
- 어떤 화면과 도구에서 실제 일로 마감하는가

쪽으로 이동하고 있다.

그래서 지금 흐름을 제대로 읽고 싶다면, 새 모델 발표만 좇아서는 부족하다. 이제는 **AI를 둘러싼 작업 환경 전체를 같이 설계하는 사람**이 더 오래 남는다. 이번 50선은 바로 그 변화를 꽤 선명하게 보여줬다.

## 참고 자료

아래는 이번 글을 쓰며 다시 참고한 전체 자료 목록이다.

## 복사용 링크 표

| # | 날짜 | 주제 | 제목 | 원본 | 공개 LilysAI 요약 |
|---:|---|---|---|---|---|
| 1 | 2026.05.23 | 교육·문서·콘텐츠 제작 자동화 | AI 시대 HTML의 부상: 새로운 마크다운, 판단하는 화면 | 텍스트 노트 또는 멀티 자료 원문 | [공개 요약](https://lilys.ai/digest/9644891/11150777?s=1&noteVersionId=7676450) |
| 2 | 2026.05.23 | 로컬 AI, Hermes, 개인 AI OS | 강의 및 회의용 로컬 AI 노트 Alt: 무료, 오픈소스, 학습 부담 완화 | [원본 1](https://github.com/altalt-org/Lightning-SimulWhisper), [원본 2](https://altalt.io/ko/support), [원본 3](https://altalt.io/ko/about) | [공개 요약](https://lilys.ai/digest/9717980/11246072?s=1&noteVersionId=7775101) |
| 3 | 2026.05.23 | 로컬 AI, Hermes, 개인 AI OS | 강의 및 회의 AI 노트 Alt: 로컬 기반 무료 필기 앱 활용 가이드 | [원본 1](https://github.com/altalt-org/Lightning-SimulWhisper), [원본 2](https://altalt.io/ko/support), [원본 3](https://altalt.io/ko/about) | [공개 요약](https://lilys.ai/digest/9717982/11246074?s=1&noteVersionId=7775103) |
| 4 | 2026.05.23 | AI 코딩 에이전트와 개발 워크플로 | 케이-스킬 (K-Skill) — 한국형 LLM 에이전트 스킬 모음 (80개 / 8 카테고리) | [원본](https://k-skill.nomadamas.org/) | [공개 요약](https://lilys.ai/digest/9717900/11245975?s=1&noteVersionId=7775002) |
| 5 | 2026.05.23 | AI 코딩 에이전트와 개발 워크플로 | Codex use cases | [원본](https://developers.openai.com/codex/use-cases) | [공개 요약](https://lilys.ai/digest/9717872/11245935?s=1&noteVersionId=7774959) |
| 6 | 2026.05.22 | AI 코딩 에이전트와 개발 워크플로 | 클로드 코드 입문 recap(2편) ━ 코워크부터 터미널, 클로드 코드까지 | [원본](https://www.youtube.com/channel/UC4PwAtNhPsuBYdavDJb4F0g) | [공개 요약](https://lilys.ai/digest/9708513/11233961?s=1&noteVersionId=7762588) |
| 7 | 2026.05.22 | 교육·문서·콘텐츠 제작 자동화 | 클로드 메모리 10분만에 최신화시키기 | 텍스트 노트 또는 멀티 자료 원문 | [공개 요약](https://lilys.ai/digest/9707122/11232010?s=1&noteVersionId=7760549) |
| 8 | 2026.05.22 | 교육·문서·콘텐츠 제작 자동화 | Honen - Create Courses with AI \| Honen | 텍스트 노트 또는 멀티 자료 원문 | [공개 요약](https://lilys.ai/digest/9706525/11231288?s=1&noteVersionId=7759811) |
| 9 | 2026.05.22 | AI 코딩 에이전트와 개발 워크플로 | DOT Studio | [원본](https://github.com/dance-of-tal/dot-studio) | [공개 요약](https://lilys.ai/digest/9705131/11229198?s=1&noteVersionId=7757638) |
| 10 | 2026.05.22 | AI 코딩 에이전트와 개발 워크플로 | Claude Code, Codex, Hermes Agent 실무자 가이드(Obsidian, MidJourney 포함) | [원본](https://blakecrosley.com/ko/guides) | [공개 요약](https://lilys.ai/digest/9705115/11229183?s=1&noteVersionId=7757623) |
| 11 | 2026.05.22 | AI 코딩 에이전트와 개발 워크플로 | 클로드 코드 + 코덱스 + 제미나이 동시에 굴리는 멀티 에이전트 시스템 (한 번 쓰면 못 돌아감) | [원본](https://www.youtube.com/channel/UCyREOF9iL_-HHB2w0BvNnyA) | [공개 요약](https://lilys.ai/digest/9703158/11226172?s=1&noteVersionId=7754531) |
| 12 | 2026.05.22 | AI 플랫폼·산업 동향 | Google IO Antigravity 2.0, Gemini 3.5 Flash 7분 정리 | [원본](https://www.youtube.com/channel/UCxZ2AlaT0hOmxzZVbF_j_Sw) | [공개 요약](https://lilys.ai/digest/9703141/11226153?s=1&noteVersionId=7754512) |
| 13 | 2026.05.22 | AI 코딩 에이전트와 개발 워크플로 | Codex 마스터 클래스 1시간 편집본 \| 하네스 설계부터 서비스 배포까지 | [원본](https://www.youtube.com/channel/UC1_ZZYZsHh2_DzCXN4VGVcQ) | [공개 요약](https://lilys.ai/digest/9703109/11226114?s=1&noteVersionId=7754471) |
| 14 | 2026.05.21 | AI 코딩 에이전트와 개발 워크플로 | Antigravity CLI 사용법! Obsidian AI 자동화 끝판왕 플러그인 무료 제공! | [원본](https://www.youtube.com/channel/UCiiUQuKEqhZ1g15EglqnHHg) | [공개 요약](https://lilys.ai/digest/9703019/11226003?s=1&noteVersionId=7754358) |
| 15 | 2026.05.21 | AI 코딩 에이전트와 개발 워크플로 | [2시간 풀버전] 클로드코드 풀코스 - AI를 잘 쓰는 방법 | [원본](https://www.youtube.com/channel/UCyjLjMUl4IEe0M4yBTXPSyw) | [공개 요약](https://lilys.ai/digest/9702984/11225943?s=1&noteVersionId=7754298) |
| 16 | 2026.05.21 | AI 코딩 에이전트와 개발 워크플로 | Oh My Pi(omp) Pi를 포크해서 만든 강력한 코딩 도구 | [원본](https://github.com/can1357/oh-my-pi) | [공개 요약](https://lilys.ai/digest/9693272/11213513?s=1&noteVersionId=7741382) |
| 17 | 2026.05.20 | AI 코딩 에이전트와 개발 워크플로 | Antigravity CLI | [원본](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/?u) | [공개 요약](https://lilys.ai/digest/9680334/11196831?s=1&noteVersionId=7724082) |
| 18 | 2026.05.20 | 로컬 AI, Hermes, 개인 AI OS | OpenClaw와 Hermes Agent의 차이점 | [원본](https://brunch.co.kr/@abrahamsong/170?shem=rimspwouoe) | [공개 요약](https://lilys.ai/digest/9677853/11193446?s=1&noteVersionId=7720624) |
| 19 | 2026.05.20 | 로컬 AI, Hermes, 개인 AI OS | 픽셀 데스크톱 펫, Clawd on Desk | [원본](https://github.com/rullerzhou-afk/clawd-on-desk) | [공개 요약](https://lilys.ai/digest/9671491/11185126?s=1&noteVersionId=7712032) |
| 20 | 2026.05.20 | AI 코딩 에이전트와 개발 워크플로 | Engineering Discipline Skill | [원본](https://github.com/tmdgusya/engineering-discipline) | [공개 요약](https://lilys.ai/digest/9671137/11184671?s=1&noteVersionId=7711558) |
| 21 | 2026.05.20 | AI 코딩 에이전트와 개발 워크플로 | Agentation, AI 코딩 에이전트가 웹페이지 특정 요소를 정확히 찾아 코드 수정 가능 도구 | [원본](https://github.com/benjitaylor/agentation) | [공개 요약](https://lilys.ai/digest/9671113/11184624?s=1&noteVersionId=7711510) |
| 22 | 2026.05.19 | AI 플랫폼·산업 동향 | LLM 관련 전 세계 최고의 자료들을 총정리한 것들의 모음집 | [원본](https://github.com/WangRongsheng/awesome-LLM-resources) | [공개 요약](https://lilys.ai/digest/9665860/11177521?s=1&noteVersionId=7704187) |
| 23 | 2026.05.19 | AI 코딩 에이전트와 개발 워크플로 | GitHub - Alishahryar1/free-claude-code: Use claude-code for free in the terminal, VSCode extension o | [원본](https://github.com/Alishahryar1/free-claude-code) | [공개 요약](https://lilys.ai/digest/9664510/11175790?s=1&noteVersionId=7702390) |
| 24 | 2026.05.19 | 로컬 AI, Hermes, 개인 AI OS | LLM Wiki가 망하는 진짜 이유: Obsidian·Claude Code보다 중요한 AI OS 설계 | [원본](https://www.youtube.com/channel/UCRJ0Q5MheESq1JOrVQYECEQ) | [공개 요약](https://lilys.ai/digest/9659263/11168980?s=1&noteVersionId=7695346) |
| 25 | 2026.05.19 | AI 코딩 에이전트와 개발 워크플로 | Code with Claude 2026: 오프닝 키노트 | [원본](https://www.youtube.com/channel/UCV03SRZXJEz-hchIAogeJOg) | [공개 요약](https://lilys.ai/digest/9659258/11168974?s=1&noteVersionId=7695340) |
| 26 | 2026.05.19 | 멀티모달·음성·비디오·네트워크 인프라 | Ethernet is DEAD?? Mac Studio is 100x FASTER!! | [원본](https://www.youtube.com/channel/UC9x0AN7BWHpCDHSm9NiJFJQ) | [공개 요약](https://lilys.ai/digest/9652411/11160284?s=1&noteVersionId=7686346) |
| 27 | 2026.05.19 | AI 코딩 에이전트와 개발 워크플로 | [바로바로 클로드 with 코워크, 스킬, 클로드 코드, 디자인] 01장 처음 만나는 클로드 | [원본](https://www.youtube.com/channel/UC4PwAtNhPsuBYdavDJb4F0g) | [공개 요약](https://lilys.ai/digest/9652396/11160272?s=1&noteVersionId=7686334) |
| 28 | 2026.05.19 | AI 플랫폼·산업 동향 | Anthropic CEO on Safety, Job Displacement and Anthropic's $350B Valuation \| WSJ | [원본](https://www.youtube.com/channel/UCZh2cjNAEMVguN1Lg00IWNA) | [공개 요약](https://lilys.ai/digest/9652332/11160188?s=1&noteVersionId=7686249) |
| 29 | 2026.05.19 | 교육·문서·콘텐츠 제작 자동화 | Python 학습 노트북 | [원본](https://github.com/eddmpython/codaro) | [공개 요약](https://lilys.ai/digest/9652295/11160128?s=1&noteVersionId=7686188) |
| 30 | 2026.05.19 | AI 코딩 에이전트와 개발 워크플로 | Warp Project Open Source | [원본](https://github.com/warpdotdev/warp) | [공개 요약](https://lilys.ai/digest/9652181/11159892?s=1&noteVersionId=7685946) |
| 31 | 2026.05.17 | 브라우저·봇·인터페이스 자동화 | GitHub - langbot-app/LangBot: Production-grade platform for building agentic IM bots - LLM을 쉽게 채팅 플랫폼에 연결하기 | [원본](https://github.com/langbot-app/LangBot) | [공개 요약](https://lilys.ai/digest/9630317/11131691?s=1&noteVersionId=7656690) |
| 32 | 2026.05.17 | 브라우저·봇·인터페이스 자동화 | CloakBrowser, 봇 탐지 시스템을 우회하여 크롤링을 진행함, Playwright Puppeteer 대체 가능 | [원본](https://github.com/CloakHQ/CloakBrowser) | [공개 요약](https://lilys.ai/digest/9630135/11131470?s=1&noteVersionId=7656463) |
| 33 | 2026.05.17 | 브라우저·봇·인터페이스 자동화 | OpenHuman Agent | [원본](https://github.com/tinyhumansai/openhuman) | [공개 요약](https://lilys.ai/digest/9624410/11124081?s=1&noteVersionId=7648803) |
| 34 | 2026.05.17 | AI 코딩 에이전트와 개발 워크플로 | Codex Discord Connector | [원본](https://github.com/joungminsung/codex-discord-connector) | [공개 요약](https://lilys.ai/digest/9617753/11114988?s=1&noteVersionId=7639420) |
| 35 | 2026.05.17 | 멀티모달·음성·비디오·네트워크 인프라 | NVIDIA VSS(Video Search and Summarization) 방대한 비디오 데이터를 실시간으로 분석하고 요약 | [원본](https://github.com/NVIDIA-AI-Blueprints/video-search-and-summarization) | [공개 요약](https://lilys.ai/digest/9617704/11114875?s=1&noteVersionId=7639306) |
| 36 | 2026.05.17 | 교육·문서·콘텐츠 제작 자동화 | 5월16일 줌미팅(코너속의 코너) | [원본](https://www.youtube.com/channel/UC9RVmFD7Afw-bAWSGapAqYA) | [공개 요약](https://lilys.ai/digest/9617516/11119644?s=1&noteVersionId=7644212) |
| 37 | 2026.05.16 | 멀티모달·음성·비디오·네트워크 인프라 | Supertonic: 초고속 온디바이스 다국어 TTS 시스템 | [원본](https://github.com/supertone-inc/supertonic) | [공개 요약](https://lilys.ai/digest/9617033/11113933?s=1&noteVersionId=7638347) |
| 38 | 2026.05.16 | 브라우저·봇·인터페이스 자동화 | CokacDIR, AI 기반 자연어 명령을 지원하는 멀티 패널 터미널 파일 관리자 | [원본](https://github.com/kstost/cokacdir) | [공개 요약](https://lilys.ai/digest/9616989/11113893?s=1&noteVersionId=7638305) |
| 39 | 2026.05.16 | AI 코딩 에이전트와 개발 워크플로 | DESIGN.md 개발자가 디자인 시스템을 쉽게 활용할 수 있도록 돕는 서비스 | [원본](https://designmd.ai/) | [공개 요약](https://lilys.ai/digest/9614640/11110997?s=1&noteVersionId=7635272) |
| 40 | 2026.05.16 | AI 코딩 에이전트와 개발 워크플로 | tiny skill, Hermes가 스스로 학습하고 업그레이드할 수 있도록 돕는 기능 | [원본](https://github.com/tinyfish-io/tinyfish-cookbook/tree/main/skills/tinyskill) | [공개 요약](https://lilys.ai/digest/9614475/11110786?s=1&noteVersionId=7635054) |
| 41 | 2026.05.16 | 로컬 AI, Hermes, 개인 AI OS | Hermes Memory Stack, Hermes Agent에 계층적 메모리 및 지식 환경을 선택적으로 설치할 수 있도록 돕는 도구 | [원본](https://github.com/yelixir-dev/hermes-memory-stack) | [공개 요약](https://lilys.ai/digest/9612198/11108041?s=1&noteVersionId=7632244) |
| 42 | 2026.05.16 | AI 코딩 에이전트와 개발 워크플로 | Claude Code vs Codex? 비교하지 말고 이렇게 쓰세요 | [원본](https://www.youtube.com/channel/UCDLlMjELbrJdETmSiAB68AA) | [공개 요약](https://lilys.ai/digest/9610643/11106030?s=1&noteVersionId=7630182) |
| 43 | 2026.05.16 | 로컬 AI, Hermes, 개인 AI OS | I Built Karpathy’s LLM Wiki in Obsidian | [원본](https://www.youtube.com/channel/UCaynjLdmzjkwcsmPN-68iHA) | [공개 요약](https://lilys.ai/digest/9610086/11105304?s=1&noteVersionId=7629439) |
| 44 | 2026.05.16 | 로컬 AI, Hermes, 개인 AI OS | DGX Spark에서 로컬 모델로 구동되는 Hermes 에이전트는 기본적으로 마법과 같아요 | [원본](https://www.youtube.com/channel/UCfQNB91qRP_5ILeu_S_bSkg) | [공개 요약](https://lilys.ai/digest/9610070/11105287?s=1&noteVersionId=7629422) |
| 45 | 2026.05.16 | 로컬 AI, Hermes, 개인 AI OS | I Built the ULTIMATE AI Second Brain (Karpathy's LLM Wiki Setup Guide) | [원본](https://www.youtube.com/channel/UCLoqOC7mh3K8esgadBCJvOQ) | [공개 요약](https://lilys.ai/digest/9610061/11105268?s=1&noteVersionId=7629403) |
| 46 | 2026.05.16 | 교육·문서·콘텐츠 제작 자동화 | 바이브코딩 1권 — 마케팅 자동화 입문 | [원본](https://aiaijungle.github.io/vibe-ebook/book1.html) | [공개 요약](https://lilys.ai/digest/9608906/11103768?s=1&noteVersionId=7627875) |
| 47 | 2026.05.16 | AI 코딩 에이전트와 개발 워크플로 | 클로드 코드 + 블로그 자동화 프로그램 만들기(웹 브라우저 자동화 원리 이해, GPT API 사용 이해, 모델 선택 가이드) | [원본](https://www.youtube.com/channel/UC4PwAtNhPsuBYdavDJb4F0g) | [공개 요약](https://lilys.ai/digest/9607300/11101598?s=1&noteVersionId=7625650) |
| 48 | 2026.05.16 | 교육·문서·콘텐츠 제작 자동화 | 700만명의 한국인 페르소나로 STP 분석하기 | [원본](https://www.youtube.com/channel/UC0mIbPKIglOAIY2NUz-1kbg) | [공개 요약](https://lilys.ai/digest/9607267/11101561?s=1&noteVersionId=7625611) |
| 49 | 2026.05.16 | 로컬 AI, Hermes, 개인 AI OS | Hermes Desktop | [원본](https://github.com/fathah/hermes-desktop) | [공개 요약](https://lilys.ai/digest/9607198/11101456?s=1&noteVersionId=7625506) |
| 50 | 2026.05.16 | 로컬 AI, Hermes, 개인 AI OS | M5 Max 맥북으로 로컬 LLM 세팅하는 법 \| Ollama + LM Studio + Hermes Agent 완전 가이드 | [원본](https://www.youtube.com/channel/UCDArTNDqDo-LordcZS8v9cA) | [공개 요약](https://lilys.ai/digest/9606680/11100800?s=1&noteVersionId=7624832) |

## 용어 정리

| 용어 | 쉬운 설명 |
|---|---|
| AI 에이전트 | 목표를 받아 도구 사용, 파일 편집, 브라우저 조작, 검증까지 여러 단계를 수행하는 AI 작업자. |
| Codex | 코드 읽기, 수정, 테스트, 배포 보조에 초점을 둔 OpenAI 계열 코딩 에이전트 환경. |
| Claude Code | 터미널과 프로젝트 파일을 기반으로 개발 작업을 수행하는 Anthropic 계열 코딩 도구. |
| Antigravity CLI | Google 계열 개발자 도구 흐름에서 Gemini CLI 이후 방향으로 언급되는 CLI 기반 에이전트 도구. |
| Hermes Agent | 로컬 모델, 메모리, 데스크톱/봇 인터페이스와 연결되는 개인 AI 에이전트 계열 워크플로. |
| LLM Wiki | LLM이 읽고 재사용하기 좋게 정리한 개인·팀 지식베이스. |
| Obsidian | Markdown 기반 개인 지식관리 도구. AI 메모리와 학습 노트의 저장소로 자주 쓰임. |
| Ollama | 로컬 머신에서 LLM을 실행하고 관리하는 도구. |
| LM Studio | 로컬 LLM 실행과 실험을 돕는 데스크톱 앱. |
| DESIGN.md | 디자인 의도와 시스템 규칙을 에이전트가 읽을 수 있게 문서화하는 파일 패턴. |
| 스킬 | 반복 가능한 작업 절차, 입력 규칙, 검증 방식을 패키징한 에이전트용 능력 단위. |
| 하네스 | 에이전트가 코드를 실행·검증·되돌릴 수 있게 감싸는 테스트/도구/환경 구조. |
| 온디바이스 TTS | 클라우드 호출 없이 기기 안에서 음성을 합성하는 기술. |
| 브라우저 자동화 | Playwright/Puppeteer 같은 도구로 웹 브라우저를 코드나 에이전트가 조작하는 방식. |
| STP 분석 | 시장 세분화(Segmentation), 타깃팅(Targeting), 포지셔닝(Positioning)을 정리하는 마케팅 프레임워크. |

## 검증 메모

- 최근 50개 항목을 기준으로 정리했다.
- 50개 항목 모두 공개 LilysAI 요약 링크를 포함한다.
- 원본 링크가 없는 항목은 텍스트 노트 또는 멀티 자료 원문으로 표시했다.
