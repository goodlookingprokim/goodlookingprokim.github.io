---
title: 2026-05-25 · 에이전트는 운영 체계가 된다 · 릴리스 20건
description: OpenClaw와 Hermes의 역할 분리, LLM Wiki, LM Studio, Gemini Omni까지 최근 20개 자료를 다시 묶어보니 이제 개인 AI의 승부처는 기능 수보다 운영 구조와 기억 체계 쪽으로 더 선명하게 이동하고 있었다.
tags:
  - curation
  - ai-trends
  - ai-automation
  - local-ai
  - knowledge-management
  - corner-of-the-corner
created: "2026-05-25"
modified: "2026-05-25"
publish: true
cssclasses:
  - quick-note
---

# 2026-05-25 · 에이전트는 운영 체계가 된다 · 릴리스 20건

이번에 받은 <strong>「최근 AI 에이전트·지식 시스템 동향 학습 큐레이션」</strong> 20개를 다시 읽으며 제일 먼저 선명해진 건 하나였다.

이제 사람들은 에이전트를 “무슨 기능이 있나”로만 고르지 않는다. 어떤 역할을 맡길지, 어떤 기억 구조를 붙일지, 어떤 화면에서 운영할지, 어떤 도구와 연결할지를 먼저 묻기 시작했다. 이번 20개 자료는 그 이동을 꽤 또렷하게 보여줬다.

## 먼저 결론

- 이번 20선의 핵심은 새 모델 발표보다 **에이전트를 어떻게 운영 체계처럼 다룰 것인가**에 있었다.
- OpenClaw와 Hermes는 경쟁 도구보다, **연결 레이어와 기억 레이어**로 나눠 읽을 때 훨씬 이해가 잘 된다.
- LLM Wiki 흐름은 RAG를 대체하는 유행어라기보다, **개인 지식베이스를 계속 관리하는 방식**으로 이동하는 실험에 가깝다.
- LM Studio MTP, Gemini CLI, Gemini Omni 같은 자료가 같이 보인다는 건 모델이 이제 별도 서비스가 아니라 **작업 화면 안으로 들어오고 있다는 뜻**이다.
- 이번 묶음은 링크를 다 읽는 것보다, “기억·운영·작업 화면”이라는 세 축으로 다시 묶어 볼 때 훨씬 오래 남는다.

## 왜 이번 20선이 유독 또렷했나

이번 자료는 숫자는 20개로 비교적 작지만, 방향은 오히려 더 선명했다. OpenClaw와 Hermes, LLM Wiki, LM Studio, Gemini Omni까지 서로 다른 분야처럼 보이던 자료가 결국 같은 질문으로 모였기 때문이다.

- 에이전트는 무엇을 기억해야 하는가
- 에이전트는 어떻게 운영해야 오래 버티는가
- 모델은 어떤 작업 화면 안으로 들어가고 있는가

이 세 가지가 계속 반복됐다. 그래서 이번 20개는 개별 툴 소개보다, **개인 AI 환경이 어떻게 한 단계 더 입체적으로 변하고 있는가**를 읽는 자료로 보는 편이 맞았다.

## 이번 묶음에서 가장 크게 보인 네 가지 변화

### 1) 에이전트는 기능 수보다 역할 분리로 이해해야 한다

이번 20선의 첫 축은 분명 이거였다.

OpenClaw와 Hermes를 비교하는 자료, 둘의 역할을 분리하는 자료, 휴대형 Hermes 환경, Hermes Agent 개념 정리까지 한 줄로 놓고 보면 공통 질문이 비슷하다.

- 이 에이전트는 무엇을 잘하나?
- 도구를 많이 붙일수록 좋은가?

보다,

- 연결은 누가 맡을까?
- 기억은 누가 맡을까?
- 실행과 판단을 같은 레이어에 둘까?

가 핵심이 된다.

특히 인상적이었던 건 OpenClaw를 외부 서비스 연결과 실행 레이어로, Hermes를 장기 기억과 자기 개선 레이어로 읽는 관점이었다. 이건 단순 비교표보다 훨씬 실무적이다.

> 앞으로 개인 에이전트를 설계할 때는 “어느 모델이 더 똑똑한가”보다 “어느 레이어에 무슨 역할을 줄 것인가”가 먼저 중요해진다.

### 2) Hermes는 설치형 툴이 아니라 운영 체계로 읽혀야 한다

이번 자료에서 Hermes 관련 항목들이 유독 많았던 이유도 여기 있다.

Hermes Desktop, VPS 구축, Telegram 연동, GitHub 백업, 칸반 보드, 크론, 상급 운영 패턴, 운영체제형 상상까지 이어지는 흐름을 보면, Hermes는 그냥 한 번 띄워보는 에이전트가 아니다.

오히려 질문은 이쪽에 가깝다.

- 상태를 어디서 볼까?
- 긴 작업은 어떻게 나눌까?
- 백업과 알림은 어떻게 붙일까?
- 역할 분리는 어떤 보드에서 관리할까?
- 기억은 어떻게 계속 갱신할까?

이건 곧 에이전트의 미래가 앱 하나가 아니라, **기억·실행·검수·알림이 묶인 개인 운영 환경** 쪽으로 간다는 뜻이기도 하다.

그래서 이번 묶음의 Hermes 자료는 “설치 튜토리얼”보다 “에이전트를 오래 굴리는 운영 수업”처럼 읽혔다.

### 3) LLM Wiki는 검색 기능이 아니라 지식 정원 관리에 가깝다

LLM Wiki 자료들도 이번 20선의 중심축이었다.

Karpathy식 LLM Wiki, Collect-Compile-Query, Obsidian 자동 유지보수, Claude Code와 Obsidian 연동, Raw to Wiki 흐름을 같이 보면 공통점이 명확하다.

이제 사람들은 문서를 매번 다시 찾아 모델에 던지는 방식만으로는 부족하다고 느낀다. 대신 AI가 자료를 한 번 읽고,
- 구조화하고
- 연결하고
- 중복을 줄이고
- 모순을 점검하고
- 나중 질문을 더 좋게 받게 만드는

쪽으로 이동하고 있다.

이게 중요한 이유는 단순하다. 개인 지식베이스의 경쟁력은 저장량보다 **질문이 더 좋아지는 구조**에 있기 때문이다.

그래서 LLM Wiki는 “RAG보다 더 멋진 기술”이라기보다, **내 자료를 계속 살아 있게 관리하는 운영 방식**으로 보는 편이 훨씬 정확하다.

### 4) 모델은 점점 작업 화면 안으로 들어오고 있다

Gemini CLI, LM Studio MTP, Gemini Omni가 같이 묶여 있다는 것도 꽤 상징적이었다.

예전에는 모델을 서비스처럼 호출했다면, 이제는 모델이 점점
- CLI 안으로 들어오고
- 로컬 실행 화면 안으로 들어오고
- 영상 편집 인터페이스 안으로 들어오고
- 일상 작업 도구의 일부가 되는

흐름이 보인다.

이 변화는 생각보다 크다.

왜냐하면 이건 결국 “AI를 어디서 쓸까?”의 문제가 아니라, **사람이 원래 일하던 화면이 어떻게 AI 친화적으로 바뀌는가**의 문제이기 때문이다.

LM Studio의 로컬 MTP 실행은 속도와 실험 감각 쪽을, Gemini Omni는 멀티모달 제작 화면 쪽을 보여준다. 둘 다 방향은 같다.

> 모델은 점점 독립된 제품이 아니라, 작업 환경 안에 스며드는 부품이 된다.

## 그래서 이 20개를 어떻게 읽는 게 좋을까

처음부터 20개를 순서대로 다 읽는 것보다, 아래 흐름으로 나눠 읽는 편이 훨씬 좋다.

### 1단계: OpenClaw와 Hermes의 역할 차이부터 본다
먼저 이 구간으로 전체 시야를 잡는다.

- OpenClaw와 Hermes 비교
- 역할 분리 방법
- Hermes Agent 핵심 개념
- 휴대형 Hermes 환경

여기까지 보면 왜 에이전트를 단일 제품보다 레이어 구조로 읽어야 하는지 감이 온다.

### 2단계: Hermes 운영 체계를 본다
그다음은 실제 운영 감각을 잡는 단계다.

- Hermes Desktop
- VPS 구축
- Telegram 연동
- GitHub 백업
- 칸반 보드
- 크론과 상급 운영 패턴

이 구간은 “좋은 프롬프트”보다 “좋은 운영 습관”이 왜 더 중요해지는지 보여준다.

### 3단계: LLM Wiki로 지식베이스 쪽을 본다
그다음엔 기억과 지식 구조 쪽이다.

- Karpathy식 LLM Wiki
- Collect-Compile-Query
- Obsidian 자동 유지보수
- Claude Code + Obsidian
- Raw to Wiki

이 흐름은 결국 AI가 검색 도우미에서 **지식 관리 파트너**로 옮겨가는 단계라고 봐도 된다.

### 4단계: 개발·로컬·멀티모달 업데이트를 본다
마지막엔 확장 방향을 본다.

- Gemini CLI
- LM Studio MTP
- Gemini Omni

여기서는 작업 화면이 어떻게 바뀌는지, 그리고 로컬 실행과 멀티모달 편집이 어디까지 들어오는지 보는 게 좋다.

## 이번 자료로 바로 떠오르는 활용 아이디어

원문에 적혀 있던 아이디어 씨앗도 좋았지만, 다시 읽으며 특히 바로 써먹기 쉬웠던 건 이쪽이었다.

- 수업용: 같은 자료를 RAG 방식과 LLM Wiki 방식으로 정리하게 하고 질문 품질 차이를 비교하는 실험
- 개인 자동화용: Hermes를 Telegram, GitHub 백업, 크론과 연결해 “하루 한 번 자동 점검하는 비서” 구조 만들기
- 멀티 에이전트 설계용: OpenClaw는 실행·연결, Hermes는 기억·판단으로 나눠 레이어 아키텍처 그려보기
- 콘텐츠 제작용: Gemini Omni 같은 자연어 영상 편집 도구가 들어왔을 때 교육 영상 제작 역할이 어떻게 바뀌는지 토론하기

이번 20개는 자료 수 자체보다, **지금 내 환경에 어떤 구조를 붙여볼까**를 더 자연스럽게 떠올리게 한다는 점에서 좋았다.

## 실제로 한 것

1. 20개 자료를 그대로 옮기지 않고, 기억·운영·작업 화면이라는 세 축으로 다시 묶었다.
2. OpenClaw와 Hermes를 경쟁 도구가 아니라 역할 분리형 레이어로 읽는 방향을 앞에 세웠다.
3. LLM Wiki는 단순 검색보다 개인 지식 관리 방식의 이동으로 설명했다.
4. LM Studio, Gemini CLI, Gemini Omni는 모델이 작업 화면 안으로 들어오는 흐름으로 다시 연결했다.
5. 참고용으로는 원문의 장점을 살려 전체 링크 표와 용어 정리를 뒤에 남겼다.

## 막혔던 지점

> 원문 자체가 이미 잘 정리되어 있어서, 그대로 옮기면 깔끔한 학습팩은 되지만 블로그 글의 한 문장이 약해질 수 있었다.

이번 글에서는 개별 항목 설명을 더 길게 늘이기보다, **이번 묶음이 결국 무엇을 말하고 있는가**를 먼저 세우는 쪽이 더 중요했다. 그래서 “에이전트는 운영 체계가 된다”는 한 문장을 중심으로 다시 묶었다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>학습 큐레이션은 개별 링크보다 반복되는 운영 축부터 먼저 다시 묶는다.</li>
  <li>에이전트 자료는 기능 표보다 역할 분리 구조로 다시 읽는다.</li>
  <li>LLM Wiki 자료는 검색 기술보다 지식 유지보수 체계로 설명한다.</li>
  <li>로컬 실행 자료와 멀티모달 자료는 “작업 화면 안으로 들어오는 모델” 관점으로 함께 본다.</li>
  <li>최종 글의 앞부분은 반드시 한 문장 논지로 다시 세우고, 전체 링크 표는 뒤로 보낸다.</li>
</ul>

## 남겨둘 판단

이번 20선을 다시 묶고 나니 가장 또렷하게 남는 건 결국 이것이었다.

AI의 다음 경쟁력은 모델 하나의 성능보다,
- 무엇을 기억하게 할지
- 어떻게 오래 운영할지
- 어떤 화면 안에서 실제 일로 연결할지

쪽으로 더 빠르게 이동하고 있다.

그래서 지금 흐름을 제대로 읽고 싶다면, 새 모델 발표만 따라가서는 부족하다. 이제는 **기억과 실행, 운영과 화면을 함께 설계하는 사람**이 더 오래 남는다. 이번 20선은 바로 그 변화를 짧고 선명하게 보여주는 묶음이었다.

## 참고 자료

아래는 이번 글을 쓰며 다시 참고한 전체 자료 목록이다.

## 복사용 링크 표

| 카테고리 | 주제 | 제목 | 원본 링크 | 릴리스 공개 링크 |
|---|---|---|---|---|
| 에이전트 선택: 넓은 연결 vs 깊은 학습 | OpenClaw와 Hermes 비교 | OpenClaw VS Hermes 비교 이야기 | [원본](https://brunch.co.kr/@abrahamsong/170) | [공개 요약](https://lilys.ai/digest/9745467/11282681?s=1&noteVersionId=7812852) |
| 에이전트 선택: 넓은 연결 vs 깊은 학습 | 두뇌와 실행 레이어 분리 | OpenClaw와 Hermes 역할 분리 방법 | [원본](https://wool-hollyhock-319.notion.site/Hermes-Agent-OpenClaw-AI-36b43e66b6018120b3d8c9583c85cf94) | [공개 요약](https://lilys.ai/digest/9754409/11294692?s=1&noteVersionId=7825268) |
| 에이전트 선택: 넓은 연결 vs 깊은 학습 | 휴대형 개인 에이전트 | I Turned a USB Drive Into a Portable AI Agent \| Hermes AI | [원본](https://www.youtube.com/watch?v=gL220WHXWeo) | [공개 요약](https://lilys.ai/digest/9735011/11268749?s=1&noteVersionId=7798493) |
| 에이전트 선택: 넓은 연결 vs 깊은 학습 | Hermes Agent 핵심 개념 | Hermes Agent Explained In 5 Minutes | [원본](https://www.youtube.com/watch?v=9GpWELm3_XI) | [공개 요약](https://lilys.ai/digest/9734745/11268375?s=1&noteVersionId=7798103) |
| Hermes 운영 체계: 데스크톱, 칸반, 크론 | Hermes Desktop과 상태 관리 | Hermes Desktop GitHub으로 멀티 에이전트 AI 워크플로우 문제 해결하기 | [원본](https://www.youtube.com/watch?v=LM19VIhD2Ao) | [공개 요약](https://lilys.ai/digest/9734443/11268105?s=1&noteVersionId=7797831) |
| Hermes 운영 체계: 데스크톱, 칸반, 크론 | Hermes 활용 단계 | 46분 만에 끝내는 100시간 분량의 Hermes 에이전트 레슨 | [원본](https://www.youtube.com/watch?v=G47mnkGkYwQ) | [공개 요약](https://lilys.ai/digest/9734442/11268111?s=1&noteVersionId=7797837) |
| Hermes 운영 체계: 데스크톱, 칸반, 크론 | 개인 AI 비서 구축 | Hermes 에이전트: 제로에서 개인 AI 비서 만들기(1시간 코스) | [원본](https://www.youtube.com/watch?v=gb5TlGw6Uks) | [공개 요약](https://lilys.ai/digest/9734441/11268114?s=1&noteVersionId=7797840) |
| Hermes 운영 체계: 데스크톱, 칸반, 크론 | 멀티 에이전트 칸반 | Hermes 에이전트 칸반 설정 가이드(멀티 에이전트 작업 보드) | [원본](https://www.youtube.com/watch?v=R_aLVXYzDac) | [공개 요약](https://lilys.ai/digest/9734439/11294854?s=1&noteVersionId=7825438) |
| Hermes 운영 체계: 데스크톱, 칸반, 크론 | 상급 운영 패턴 | 상위 1%처럼 Hermes 에이전트를 활용하는 방법 | [원본](https://www.youtube.com/watch?v=NvakBZyc1Sg) | [공개 요약](https://lilys.ai/digest/9734438/11268363?s=1&noteVersionId=7798091) |
| Hermes 운영 체계: 데스크톱, 칸반, 크론 | 에이전트 운영체제 구상 | 10배 더 강력해진 Hermes 에이전트(에이전트 운영체제) | [원본](https://www.youtube.com/watch?v=7xuWZ-3lyQE) | [공개 요약](https://lilys.ai/digest/9734436/11268258?s=1&noteVersionId=7797985) |
| LLM Wiki와 개인 지식 베이스 | LLM Wiki 설치 관점 | 카르파티의 LLM 위키 - 초보자를 위한 전체 설정 가이드 | [원본](https://www.youtube.com/watch?v=iXd0t60YmMw) | [공개 요약](https://lilys.ai/digest/9734450/11268087?s=1&noteVersionId=7797813) |
| LLM Wiki와 개인 지식 베이스 | LLM Wiki의 의미 | 카르파티의 LLM 위키: 의미와 구축 방법 | [원본](https://www.youtube.com/watch?v=zVEb19AwkqM) | [공개 요약](https://lilys.ai/digest/9734448/11268090?s=1&noteVersionId=7797816) |
| LLM Wiki와 개인 지식 베이스 | Collect-Compile-Query | 개인 LLM 지식 베이스 구축 방법 (카르파티의 방법론) | [원본](https://www.youtube.com/watch?v=VRub1w-APTc) | [공개 요약](https://lilys.ai/digest/9734447/11268096?s=1&noteVersionId=7797822) |
| LLM Wiki와 개인 지식 베이스 | 옵시디언 자동 유지보수 | 옵시디언을 24시간 유지보수하는 AI 구축하기 (Claude Code + LLM 위키) | [원본](https://www.youtube.com/watch?v=RJoiJ_EenxA) | [공개 요약](https://lilys.ai/digest/9734445/11268102?s=1&noteVersionId=7797828) |
| LLM Wiki와 개인 지식 베이스 | Claude Code + Obsidian | Claude Code와 옵시디언으로 LLM 위키를 구축하는 방법 | [원본](https://www.youtube.com/watch?v=p3J0cdh4bdQ) | [공개 요약](https://lilys.ai/digest/9734440/11268122?s=1&noteVersionId=7797848) |
| LLM Wiki와 개인 지식 베이스 | Raw to Wiki 연구 자동화 | 카르파티의 LLM 위키 + 이 스킬 = 판도를 바꾸는 기술 | [원본](https://www.youtube.com/watch?v=v8rCHym0lXE) | [공개 요약](https://lilys.ai/digest/9734437/11268261?s=1&noteVersionId=7797988) |
| LLM Wiki와 개인 지식 베이스 | 입문자를 위한 LLM Wiki | LLM Wiki 입문 가이드 | [원본](https://www.youtube.com/watch?v=S6w4g2OQlVQ) | [공개 요약](https://lilys.ai/digest/9734434/11268377?s=1&noteVersionId=7798105) |
| 개발·로컬 모델·멀티모달 제작 업데이트 | Gemini CLI와 AI 개발 환경 | 구글IO 2026 안티그래비티 2.0과 GEMINI Flash 3.5 그리고 GEMINI CLI의 매우 큰 변화 핵심 정리 | [원본](https://www.youtube.com/watch?v=9ZdXve5DaCc) | [공개 요약](https://lilys.ai/digest/9734928/11268615?s=1&noteVersionId=7798354) |
| 개발·로컬 모델·멀티모달 제작 업데이트 | LM Studio와 MTP 로컬 실행 | LM Studio MTP tutorial : Run Qwen 3.6 MTP in local | [원본](https://www.youtube.com/watch?v=IGIiUl8pcKM) | [공개 요약](https://lilys.ai/digest/9734910/11268594?s=1&noteVersionId=7798333) |
| 개발·로컬 모델·멀티모달 제작 업데이트 | Gemini Omni 영상 편집 | Gemini Omni, 일관성 유지 대박! 이제는 영상을 자연어로 간단하게 수정하는 시대! | [원본](https://www.youtube.com/watch?v=FPs9SWwiEeM) | [공개 요약](https://lilys.ai/digest/9734897/11268578?s=1&noteVersionId=7798317) |

## 용어 정리

| 용어 | 쉬운 설명 | 일상 예시 |
|---|---|---|
| AI 에이전트 | 목표를 받고 여러 단계를 스스로 처리하는 AI 도구입니다. | 여행지를 말하면 항공권, 숙소, 일정 후보를 차례로 알아봐 주는 비서와 비슷합니다. |
| OpenClaw | 여러 채널과 외부 도구를 빠르게 연결하는 에이전트 실행·연동 레이어로 볼 수 있습니다. | 사무실의 여러 기기와 앱을 한 리모컨으로 연결해 주는 허브처럼 생각하면 됩니다. |
| Hermes Agent | 장기 기억, 스킬 생성, 반복 작업 학습을 강조하는 개인 에이전트 런타임입니다. | 새 업무를 할 때마다 노하우 노트를 남겨 다음번에 더 잘하는 조수와 비슷합니다. |
| LLM Wiki | AI가 읽은 자료를 구조화된 위키로 정리하고 계속 갱신하게 하는 지식 관리 방식입니다. | 책상 위 자료를 매번 찾는 대신, 조교가 주제별 파일철을 계속 정리해 두는 상황입니다. |
| RAG | AI가 답하기 전에 관련 문서 조각을 찾아 참고하게 하는 방식입니다. | 시험 답안을 쓰기 전에 책장에서 필요한 페이지만 찾아 펼쳐 놓는 것과 비슷합니다. |
| Obsidian | 마크다운 노트를 서로 연결해 개인 지식 베이스를 만드는 노트 앱입니다. | 생각과 자료가 끈으로 연결된 카드 상자처럼 사용할 수 있습니다. |
| Claude Code | 코드와 파일 작업을 대화형으로 도와주는 개발자용 AI 코딩 도구입니다. | 개발 폴더 안에서 같이 파일을 읽고 수정하는 동료 개발자처럼 보면 됩니다. |
| MTP | Multi-Token Prediction의 줄임말로, 모델이 다음 토큰 여러 개를 한 번에 예측해 속도를 높이는 기법입니다. | 한 글자씩 받아쓰는 대신 다음 몇 단어를 미리 예상해 적는 속기 방식과 비슷합니다. |
| 칸반 | 작업을 카드로 나누고 진행 상태별로 옮기며 관리하는 방식입니다. | 포스트잇을 할 일, 진행 중, 완료 칸에 붙여 옮기는 작업판입니다. |
| 크론 | 정해진 시간마다 명령이나 작업을 자동 실행하는 스케줄러입니다. | 매일 아침 8시에 자동으로 커피머신이 켜지도록 예약하는 것과 비슷합니다. |
| VPS | 인터넷에 항상 켜 둘 수 있는 임대 서버입니다. | 내 컴퓨터를 꺼도 계속 일하는 작은 원격 컴퓨터를 빌리는 것입니다. |
| 컨텍스트 | AI가 답변할 때 참고하는 대화, 파일, 규칙, 이전 작업 기억입니다. | 회의 중 칠판에 적어 둔 결정사항을 보며 다음 논의를 이어가는 상황입니다. |
