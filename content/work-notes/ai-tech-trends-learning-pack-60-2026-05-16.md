---
title: AI는 이제 답변기보다 작업 시스템에 가까워지고 있다 · 최근 AI·기술 자료 60선에서 읽은 흐름
description: Codex, Claude Code, Hermes, MCP, LLM Wiki, 로컬 AI, 공공 문서 자동화까지 60개 자료를 다시 묶어보며 지금 AI 흐름의 무게중심이 어디로 옮겨가고 있는지 정리한 글
tags:
  - curation
  - ai-trends
  - ai-automation
  - developer-tools
  - local-ai
  - work-notes
created: "2026-05-16"
modified: "2026-05-16"
publish: true
cssclasses:
  - quick-note
---

# AI는 이제 답변기보다 작업 시스템에 가까워지고 있다 · 최근 AI·기술 자료 60선에서 읽은 흐름

요즘 AI 흐름을 따라가다 보면, 예전과는 확실히 다른 공기가 느껴진다.

한때는 “어느 모델이 더 잘 쓰나”, “누가 더 똑똑한 답을 하나”가 중심이었다. 그런데 지금은 그 질문만으로는 부족하다. 사람들이 진짜 오래 붙잡고 있는 건 따로 있다. AI에게 목표를 맡기고, 도구를 연결하고, 브라우저를 움직이게 하고, 지식을 쌓아두고, 문서와 보고서 형식까지 맞춰서 실제 결과물로 마감하는 문제다.

이번에 받은 <strong>「최근 AI·기술 동향 학습 큐레이션 60선」</strong>은 바로 그 변화를 꽤 선명하게 보여주는 자료였다. 링크를 많이 모은 것이 중요한 게 아니라, 어디에 반복해서 무게가 실리는지가 드러난다는 점이 좋았다.

## 먼저 결론

- 지금 AI 흐름의 중심은 “더 똑똑한 답변”보다 **더 오래 굴러가는 작업 시스템** 쪽으로 옮겨가고 있다.
- 특히 **Codex·Claude Code 같은 코딩 에이전트, Hermes 같은 개인 런타임, MCP·브라우저 연결, LLM Wiki·Obsidian 계열 지식 시스템**이 한 덩어리로 묶여 움직이고 있다.
- 공공 문서, HWPX, 기관 보고서 같은 형식 작업이 자꾸 등장하는 걸 보면, 생성형 AI의 가치는 초안 작성보다 **현장의 형식과 검토 루프를 지키는 데**서 더 커지고 있다.
- 로컬 AI와 개인 개발환경 도구는 더 이상 취미 영역이 아니다. 이제는 **개인 작업실을 어떻게 AI 친화적으로 바꾸느냐**가 중요한 흐름이 됐다.
- 이런 큐레이션은 저장보다 재분류가 중요하다. 60개를 다 읽는 것보다, **반복해서 나타나는 축을 먼저 읽는 편**이 훨씬 남는다.

## 이번 묶음이 특히 좋았던 이유

이 자료는 단순히 링크를 잔뜩 나열한 모음이 아니었다.

- 큰 흐름 요약
- 카테고리별 맥락
- 짧은 설명
- 원본 링크
- LilysAI 공개 요약 링크
- 마지막 복사용 링크 표와 용어 정리

까지 같이 들어 있어서, 혼자 보기에도 좋고 다른 사람에게 다시 공유하기도 좋았다.

특히 마음에 든 건 “모든 자료를 다 읽으라”는 방식이 아니라, **먼저 지형을 보여주고 그다음 관심 분야를 파고들게 만드는 구조**였다는 점이다. 요즘 같은 정보 과잉 시기엔 이게 진짜 중요하다.

## 이번 60선에서 가장 크게 보인 여섯 가지 흐름

### 1) 코딩 AI는 이제 답변기보다 운영 도구에 가까워지고 있다

가장 먼저 눈에 들어오는 건 Codex와 Claude Code 쪽이다.

이제 사람들은 AI에게 단순히 코드 조각을 부탁하지 않는다.

- 목표를 주고
- 그 목표를 따라 여러 단계를 수행하게 하고
- 에이전트 뷰로 여러 세션을 관리하고
- 브라우저·DevTools·원격 제어기까지 붙이고
- 필요하면 다른 에이전트를 호출하게 만든다

이번 자료에서 이 축을 가장 잘 보여준 건 이런 항목들이었다.

- Follow a goal | Codex use cases
- Codex /goal 기능
- Codex vs Claude Code: 상위 개발자들이 둘 다 사용하는 이유 (2026)
- Chrome DevTools MCP for Agents
- Claude Code에 에이전트 대시보드가 추가되었습니다
- 클로드 코드(Claude Code)를 활용한 AI 팀 자동화 구축

이 흐름을 한 문장으로 줄이면 이렇다.

> 코딩 AI는 이제 질문에 답하는 도구가 아니라, 목표를 따라 움직이는 작업 운영체제로 가고 있다.

### 2) Hermes 계열은 “내가 통제하는 개인 에이전트 런타임” 쪽으로 진화하고 있다

Hermes 관련 자료가 8건이나 들어간 것도 눈에 띄었다.

이건 우연이 아니다. 사람들은 점점 “남이 만들어둔 AI 서비스”보다, **내가 직접 켜두고 통제할 수 있는 개인 런타임**에 관심을 보이고 있다.

그래서 Hermes 묶음에는 늘 비슷한 키워드가 따라온다.

- 설치
- 슬래시 명령어
- Discord나 Telegram 연결
- 워크플로우 레이어
- 스킬 세트
- 원격 모니터링

대표 자료는 아래다.

- 에르메스 설치 + 세팅 완벽 가이드 디스코드 버전
- Hermes 설치 후 꼭 알아야 할 슬래시 명령어
- Hermes Desktop
- Discord Agent Bridge
- Oh My Hermes
- 헤르메스 요원이 오픈클로를 처치했습니다 (전체 튜토리얼)

이쪽을 보고 있으면 결국 질문은 하나로 모인다.

“좋은 AI를 쓰는 것”보다 “내가 계속 부릴 수 있는 AI 작업 환경을 어떻게 세팅할 것인가?”

이건 꽤 큰 변화다.

### 3) MCP와 브라우저 연결은 에이전트를 현실 세계에 붙이는 표준층이 되고 있다

이번 묶음에서 수는 많지 않았지만 의미가 큰 카테고리가 바로 MCP, 브라우저, 도구 연결이었다.

왜 중요하냐면, AI가 아무리 말을 잘해도 실제 웹 환경과 외부 도구를 안정적으로 다루지 못하면 결국 대화창 안에 갇히기 때문이다.

카카오 PlayMCP와 Sigma Private AI Browser가 같이 들어간 건 상징적이다.

- 한쪽은 한국형 서비스와 공공 데이터 연결
- 다른 한쪽은 브라우저 안에서 실제 행동하는 에이전트

즉 방향은 분명하다.

> AI는 점점 더 “답변 생성기”에서 “외부 세계와 연결된 실행 주체”가 되려 하고 있다.

### 4) 개인 지식 시스템은 메모 저장이 아니라 재사용 구조로 이동 중이다

NotebookLM, Obsidian, Code Wiki, autoresearch, Karpathy의 Obsidian RAG 같은 자료가 한데 모인 것도 꽤 의미 있었다.

예전에는 “노트를 잘 정리하는 법”이 관심사였다면, 지금은 그보다 한 단계 더 나간다.

- 자료를 모으고
- AI가 읽을 수 있게 정리하고
- 필요한 순간 다시 찾고
- 연결 관계를 만들고
- 작업에 바로 투입하는 구조

를 만드는 쪽이다.

그래서 이 묶음은 단순한 노트앱 추천이 아니라, **개인 지식 시스템을 AI 친화적으로 개조하는 흐름**으로 읽는 게 맞다.

대표 자료는 이쪽이다.

- NotebookLM 마스터 가이드
- Code Wiki
- 옵시디언 노트를 HTML 블로그로 바꾸는 흐름
- 옵시디언과 Claude Code 연결
- autoresearch
- Karpathy의 옵시디언 RAG와 Claude Code의 조합

이 흐름은 앞으로 더 커질 가능성이 높다. 자료를 많이 모으는 사람보다, **모은 자료를 다시 일하게 만드는 사람**이 더 강해질 가능성이 커서다.

### 5) 공공 문서와 보고서 자동화는 AI 실무화의 진짜 시험장이다

이번 60선에서 내가 특히 반가웠던 축은 이쪽이었다.

공공 문서, 한글 보고서, 기관 양식, 의약품 안내, 범정부오피스 같은 자료는 겉보기엔 화려하지 않다. 그런데 오히려 그래서 더 중요하다.

실제 현장에서는 “멋진 초안”보다,

- 양식이 맞는지
- 기관 스타일을 지키는지
- 검토 포인트가 빠지지 않는지
- 반복 작업을 얼마나 줄였는지

가 더 중요하기 때문이다.

대표 자료는 아래처럼 묶인다.

- AI 콘텐츠를 공공기관 한글 보고서로 변환하는 Claude Skill
- 식약청 공식 의약품 정보 활용 의료 정보 안내 스킬
- K-Skill(Kakao Skill)
- 범정부오피스 자동화 자료

이걸 보면 생성형 AI의 진짜 가치는 점점 선명해진다.

> AI는 자유형 글쓰기에서만 빛나는 게 아니라, 오히려 형식이 빡빡한 문서 현장에서 더 큰 효율을 만들 수 있다.

### 6) 로컬 AI와 개인 개발환경은 “내 장비를 AI 친화적으로 바꾸는 일”이 되고 있다

로컬 AI와 개인 개발환경 카테고리도 꽤 균형이 좋았다.

- mq-dir
- Winget TUI
- DOT Studio
- zero-native
- LM Studio

이런 자료를 모아보면 공통점이 있다. 전부 “새 모델” 이야기가 아니라, **내가 쓰는 장비와 작업실을 어떻게 다시 짤 것인가**에 관한 얘기라는 점이다.

즉 클라우드 AI를 소비하는 데서 그치지 않고,

- 파일 관리자
- 패키지 관리
- 로컬 모델 실행
- 데스크톱 앱 구조
- 협업 캔버스

까지 전부 AI 중심으로 다시 재배치하려는 흐름이 보인다.

## 그럼 지금 뭘 먼저 읽는 게 좋을까

60개를 한 번에 다 보는 건 솔직히 무리다. 그래서 지금 기준으로는 이렇게 읽는 편이 훨씬 낫다.

### 1단계: 코딩 에이전트와 작업 운영 감각 잡기

먼저 아래 묶음부터 보는 걸 추천한다.

- Follow a goal | Codex use cases
- Codex vs Claude Code: 상위 개발자들이 둘 다 사용하는 이유 (2026)
- Claude Code에 에이전트 대시보드가 추가되었습니다
- Chrome DevTools MCP for Agents
- 클로드 코드(Claude Code)를 활용한 AI 팀 자동화 구축

이 다섯 개만 봐도, 왜 요즘 코딩 AI 논의가 단순 모델 비교에서 빠져나오는지 감이 잡힌다.

### 2단계: 개인 런타임과 지식 시스템 붙이기

그다음은 이 흐름이 좋다.

- Oh My Hermes
- Hermes 설치 후 꼭 알아야 할 슬래시 명령어
- NotebookLM 마스터 가이드
- Code Wiki
- 옵시디언에 클로드 코드 연결하면 이런 일이 가능합니다

이렇게 보면, 에이전트가 혼자 좋은 게 아니라 **기억과 구조를 붙였을 때 훨씬 강해진다**는 점이 잘 보인다.

### 3단계: 실제 현장 문서와 로컬 작업 환경으로 내려오기

마지막으로는 이쪽이 좋다.

- AI 콘텐츠를 공공기관 한글 보고서로 변환하는 Claude Skill
- 식약청 공식 의약품 정보 활용 의료 정보 안내 스킬
- LM Studio Is Getting Insane — Master Local AI Now
- mq-dir, MacOS 파일 관리자
- Sigma Private AI Browser

이 단계로 오면 비로소 AI가 “재밌는 장난감”을 지나 **실제 일의 인프라**로 들어오고 있다는 느낌이 난다.

## 이번 60선에서 특히 좋았던 점 하나

이 큐레이션은 카테고리를 잘 나눈 것도 좋았지만, 더 중요한 건 **학습의 난이도를 꽤 잘 낮췄다**는 점이다.

예를 들어 MCP, RAG, LLM, 오케스트레이션, 로컬 AI, HWPX 같은 용어는 익숙하지 않은 사람에겐 금방 부담이 된다. 그런데 마지막에 용어 정리표를 붙여둔 건 꽤 좋은 선택이었다.

이런 자료는 원래 “아는 사람만 읽는 문서”로 흐르기 쉬운데, 이번 자료는 적어도 **처음 보는 사람도 따라오게 만들려는 배려**가 있었다.

## 아쉬운 점도 있다

물론 그대로 블로그에 옮기기엔 조금 숨이 차는 구조이기도 했다.

왜냐하면 60건은 이미 충분히 많은데,

- 영상
- GitHub 저장소
- PDF
- 노션/문서
- 요약 링크

가 한꺼번에 들어오다 보니, 독자가 처음부터 끝까지 읽기보다는 중간에 길을 잃기 쉽다.

그래서 블로그 글로 바꿀 때는 원문을 그대로 복붙하기보다,

1. 이번 자료가 가리키는 큰 흐름을 먼저 세우고
2. 그다음 대표 자료를 고르고
3. 마지막에 전체 링크 표를 참고용으로 두는 편

이 더 읽기 좋다.

## 실제로 한 것

1. 60개 자료를 카테고리별로 다시 읽으면서 반복해서 나오는 축부터 추렸다.
2. Codex·Claude Code·Hermes·MCP·LLM Wiki·공공 문서 자동화·로컬 AI라는 흐름으로 다시 묶었다.
3. 블로그에서는 목록 전체보다 “지금 어디에 무게가 실리는가”가 먼저 보이도록 구조를 재작성했다.

## 막혔던 지점

> 원문 자료는 훌륭했지만, 그대로 옮기면 링크 사전처럼 보일 위험이 있었다.

설명, 링크, 공개 요약이 이미 충분히 풍부해서 자료 자체는 좋았다. 다만 블로그 글은 큐레이션 원문과 역할이 다르다. 블로그에서는 “무엇이 가장 중요한 변화인가”가 먼저 보여야 읽는 힘이 생긴다. 그래서 이번 글은 자료를 줄이는 대신, 흐름을 더 세게 드러내는 쪽으로 정리했다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>학습 큐레이션을 블로그로 옮길 때는 링크를 다 싣기 전에 반복되는 축부터 먼저 뽑는다.</li>
  <li>모델 이름보다 운영 방식, 연결 계층, 메모리 구조, 배포 습관이 얼마나 자주 등장하는지 본다.</li>
  <li>공공 문서, 보고서, 기관 양식 같은 자료가 보이면 “AI 실무화가 어디까지 왔는가”를 읽는 신호로 본다.</li>
  <li>로컬 AI와 브라우저 도구는 별도 취미 카테고리가 아니라, 개인 작업실 재설계 흐름으로 읽는다.</li>
  <li>최종 글에서는 원문 링크 표를 남기더라도, 앞부분은 반드시 사람이 읽는 서사로 다시 세운다.</li>
</ul>

## 남겨둘 판단

이번 60개 자료를 훑고 나서 가장 또렷했던 건 하나다.

AI는 점점 더 “똑똑한 답변기”에서 멀어지고 있다.

대신 사람들은 AI에게

- 역할을 나눠주고
- 장기 목표를 맡기고
- 브라우저와 도구를 연결하고
- 개인 지식 시스템을 붙이고
- 문서 형식과 보고 체계를 지키게 하면서
- 결과물을 실제 현장에 맞게 마감하게 만들고 있다.

그러니까 지금 흐름을 제대로 읽고 싶다면, 새 모델 발표만 쫓아서는 부족하다.

이제는 **AI를 어떻게 연결하고, 저장하고, 운영하고, 검수해 실제 일로 바꾸는가**를 같이 봐야 한다. 이번 60선은 바로 그 전환을 꽤 선명하게 보여주는 자료였다.

## 참고 자료

아래 표는 이번 글을 쓰며 다시 참고한 60개 자료 중 핵심 항목을 주제별로 정리한 것이다. 원문 링크와 LilysAI 공개 링크가 함께 있어, 관심 분야만 골라 따라가기에 좋다.

### 1. OpenAI Codex와 코딩 에이전트 운영

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| Follow a goal \| Codex use cases | Codex CLI의 목표 기반 실행 개념을 가장 직접적으로 보여주는 공식 문서 | [원본](https://developers.openai.com/codex/use-cases/follow-goals) | [요약](https://lilys.ai/digest/9604790/11098188?s=1&noteVersionId=7622139&include_suggestion=true) |
| Codex /goal 기능 | `/goal` 기능을 다시 짚으며 Codex가 단발성 생성기에서 작업 루프로 이동하는 흐름을 보여주는 항목 | [원본](https://developers.openai.com/codex/use-cases/follow-goals) | [요약](https://lilys.ai/digest/9604789/11098189?s=1&noteVersionId=7622140&include_suggestion=true) |
| Codex vs Claude Code: 상위 개발자들이 둘 다 사용하는 이유 (2026) | 두 도구를 경쟁 관계보다 병행 전략으로 바라보는 관점을 정리한 비교 자료 | [원본](https://www.youtube.com/watch?v=3DhgRoP54H8) | [요약](https://lilys.ai/digest/9581407/11068049?s=1&noteVersionId=7591058&include_suggestion=true) |
| AI 코딩 에이전트는 더 이상 수동 관리가 필요하지 않아요 | 목표 기반 코딩 루프가 왜 새로운 패러다임인지 설명하는 영상 | [원본](https://www.youtube.com/watch?v=lSYRPyko7fM) | [요약](https://lilys.ai/digest/9581367/11067995?s=1&noteVersionId=7591004&include_suggestion=true) |
| Crack CLI | Codex가 다른 에이전트까지 활용하게 만드는 원격 제어형 도구 | [원본](https://github.com/Royaltyprogram/Crack-CLI) | [요약](https://lilys.ai/digest/9554887/11032416?s=1&noteVersionId=7554355&include_suggestion=true) |
| AGENTS.md | AI 코딩 에이전트에게 작업 기준을 주는 운영 문서 개념을 설명하는 저장소 | [원본](https://github.com/agentsmd/agents.md) | [요약](https://lilys.ai/digest/9532743/11001364?s=1&noteVersionId=7522439&include_suggestion=true) |
| 클로드 코드 말고 Codex? GPT-5.5 코딩 AI 73개 명령어 완전 정복 | 초보자 관점에서 Codex CLI 기본 명령과 운영 감각을 길게 짚어주는 입문 영상 | [원본](https://www.youtube.com/watch?v=Zt_Bkv4Hgas) | [요약](https://lilys.ai/digest/9513950/10976999?s=1&noteVersionId=7496688&include_suggestion=true) |
| Chrome DevTools MCP for Agents | AI 코딩 에이전트가 실제 브라우저를 제어하고 디버깅하는 연결 계층을 소개하는 자료 | [원본](https://github.com/ChromeDevTools/chrome-devtools-mcp) | [요약](https://lilys.ai/digest/9506783/10967614?s=1&noteVersionId=7486971&include_suggestion=true) |
| ChatGPT만 쓰면 손해입니다. Codex 쓰세요! | ChatGPT와 Codex를 다른 도구로 이해하게 도와주는 초보자 튜토리얼 | [원본](https://www.youtube.com/watch?v=ir8Lax4Q38o) | [요약](https://lilys.ai/digest/9501598/10961546?s=1&noteVersionId=7480706&include_suggestion=true) |

### 2. Claude Code와 에이전트 자동화

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| Hermes를 대체했습니다... Claude Agent 2.0 | 기존 에이전트 시스템의 한계를 넘어 더 맞춤형 자동화로 가려는 흐름을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=kpBgBNzb2pY) | [요약](https://lilys.ai/digest/9581447/11068174?s=1&noteVersionId=7591183&include_suggestion=true) |
| Claude Code에 에이전트 대시보드가 추가되었습니다 | 여러 세션을 하나의 뷰에서 보는 Agent View의 의미를 짚는 자료 | [원본](https://www.youtube.com/watch?v=ZAaxx3qyT8g) | [요약](https://lilys.ai/digest/9581396/11068015?s=1&noteVersionId=7591024&include_suggestion=true) |
| Claude Code 초보자용 강의 정리 | 설치, Plan Mode, 검증 루프, 권한 모드까지 폭넓게 다룬 입문 PDF | PDF 업로드 | [요약](https://lilys.ai/digest/9573111/11056772?s=1&noteVersionId=7579438&include_suggestion=true) |
| 클로드코드 대박 신기능 Agent View | Agent View가 멀티 에이전트 관리 경험을 어떻게 바꾸는지 보여주는 영상 | [원본](https://www.youtube.com/watch?v=MPWKZzP-bQs) | [요약](https://lilys.ai/digest/9549896/11025294?s=1&noteVersionId=7547012&include_suggestion=true) |
| 클로드 코드(Claude Code)를 활용한 AI 팀 자동화 구축 | Claude Code와 tmux, 원격 제어를 묶어 역할형 AI 팀을 구성하는 가이드 | [원본](https://wikidocs.net/book/19736) | [요약](https://lilys.ai/digest/9535599/11005647?s=1&noteVersionId=7526832&include_suggestion=true) |
| Caveman | 답변을 짧고 효율적으로 만들려는 후처리 스킬 관점을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=iEScgjg_eR4) | [요약](https://lilys.ai/digest/9532628/11001177?s=1&noteVersionId=7522246&include_suggestion=true) |
| 만드는 사람과 방향을 보는 사람만 AI 시대에 남을 것이다 | AI 도구 활용 격차가 실제 직무와 생산성을 어떻게 갈라놓는지 다루는 글 | [원본](https://share.note.sx/sh8d046x#xIsiwT1ttdqgEMdIAJygzU/SUtDtcYBEaMQNDenATQc) | [요약](https://lilys.ai/digest/9518695/10983125?s=1&noteVersionId=7502989&include_suggestion=true) |
| Verbal Coding | 음성 인터페이스로 CLI 코딩 에이전트를 조종하는 실험적 도구 | [원본](https://github.com/ca1773130n/VerbalCoding) | [요약](https://lilys.ai/digest/9514666/10977951?s=1&noteVersionId=7497674&include_suggestion=true) |
| 2026년, Claude Code를 무료로 사용하는 방법 | 무료 대안이나 우회 전략을 통해 Claude Code 류 흐름을 활용하는 관점을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=aet6r1nEeho) | [요약](https://lilys.ai/digest/9501543/10960808?s=1&noteVersionId=7479931&include_suggestion=true) |

### 3. Hermes와 개인 에이전트 런타임

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| 에르메스 설치 + 세팅 완벽 가이드 디스코드 버전 | Hermes 설치부터 Discord 연결까지 실제 세팅 흐름을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=OWEQKlfA4DM) | [요약](https://lilys.ai/digest/9571803/11055040?s=1&noteVersionId=7577667&include_suggestion=true) |
| Hermes 설치 후 꼭 알아야 할 슬래시 명령어 | Hermes를 쓸 때 바로 체감되는 운영 명령어를 정리한 입문 자료 | [원본](https://www.youtube.com/watch?v=vfhXPrMp15A) | [요약](https://lilys.ai/digest/9558139/11036655?s=1&noteVersionId=7558709&include_suggestion=true) |
| Hermes Desktop | Hermes Desktop의 기능 업데이트와 성능 개선 흐름을 보여주는 릴리즈 자료 | [원본](https://github.com/fathah/hermes-desktop/releases/) | [요약](https://lilys.ai/digest/9525567/10991958?s=1&noteVersionId=7512123&include_suggestion=true) |
| Discord Agent Bri | Discord에서 AI 에이전트 작업을 원격 모니터링하게 해주는 브리지 도구 | [원본](https://github.com/DoBuDevel/discord-agent-bridge) | [요약](https://lilys.ai/digest/9514673/10977962?s=1&noteVersionId=7497685&include_suggestion=true) |
| Oh My Hermes | Hermes 위에 워크플로우 레이어와 운영 습관을 얹는 대표 프로젝트 | [원본](https://github.com/Salomondiei08/oh-my-hermes) | [요약](https://lilys.ai/digest/9514172/10977293?s=1&noteVersionId=7496985&include_suggestion=true) |
| paperclip 실제 사용 후기 | AI 비서 작업 관리 문제를 보완하는 실전 도구 관점을 담은 후기 영상 | [원본](https://www.youtube.com/watch?v=-OnM0ABAYzM) | [요약](https://lilys.ai/digest/9514070/10977143?s=1&noteVersionId=7496834&include_suggestion=true) |
| Hermes Agent를 위한 워크플로우 레이어 | Oh My Hermes를 다시 소개하며 앱 구축 자동화 흐름을 강조하는 자료 | [원본](https://github.com/Salomondiei08/oh-my-hermes) | [요약](https://lilys.ai/digest/9501259/10960452?s=1&noteVersionId=7479566&include_suggestion=true) |
| 헤르메스 요원이 오픈클로를 처치했습니다 | Hermes 설치와 Telegram 연결까지 한 번에 보여주는 전체 튜토리얼 | [원본](https://www.youtube.com/watch?v=jmtpYUOr7_U) | [요약](https://lilys.ai/digest/9501121/10960269?s=1&noteVersionId=7479379&include_suggestion=true) |

### 4. MCP, 브라우저, 도구 연결

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| 카카오 PlayMCP | 한국형 공공 데이터와 업무 서비스를 AI 에이전트에 연결하는 방향을 보여주는 자료 | [원본](https://www.youtube.com/watch?v=oDsxxKmJz-k) | [요약](https://lilys.ai/digest/9587571/11076448?s=1&noteVersionId=7599700&include_suggestion=true) |
| Sigma Private AI Browser | 브라우저 안에서 AI 에이전트가 페이지 탐색과 요약, 양식 작업까지 수행하는 방향을 보여주는 도구 | [원본](https://www.sigmabrowser.com/) | [요약](https://lilys.ai/digest/9535455/11005468?s=1&noteVersionId=7526648&include_suggestion=true) |

### 5. 개인 지식 시스템과 학습 노트

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| NotebookLM 마스터 가이드 | 문서 기반 학습과 요약 도구로서 NotebookLM의 본질과 활용 전략을 설명하는 자료 | PDF 업로드 | [요약](https://lilys.ai/digest/9594678/11085497?s=1&noteVersionId=7609008&include_suggestion=true) |
| Code Wiki | 코드베이스를 AI가 읽기 좋은 문서 구조로 바꿔 주는 Google 계열 도구 | [원본](https://codewiki.google/) | [요약](https://lilys.ai/digest/9573079/11056734?s=1&noteVersionId=7579399&include_suggestion=true) |
| 옵시디언 노트가 딸깍 한번에 HTML 블로그로 | Obsidian 노트를 바로 HTML 블로그로 발행하는 플러그인 흐름 소개 | [원본](https://www.youtube.com/watch?v=LkV03ZxLGG4) | [요약](https://lilys.ai/digest/9549856/11025235?s=1&noteVersionId=7546952&include_suggestion=true) |
| 옵시디언에 클로드 코드 연결하면 이런 일이 가능합니다 | Obsidian과 Claude Code를 결합해 사업 시스템과 정보 정리를 자동화하는 관점 | [원본](https://www.youtube.com/watch?v=OVilj8E2NnM) | [요약](https://lilys.ai/digest/9546767/11021049?s=1&noteVersionId=7542639&include_suggestion=true) |
| autoresearch | AI 에이전트가 코드를 자율 수정하며 실험까지 이어가는 연구형 프로젝트 | [원본](https://github.com/karpathy/autoresearch) | [요약](https://lilys.ai/digest/9506935/10967832?s=1&noteVersionId=7487195&include_suggestion=true) |
| Karpathy의 옵시디언 RAG와 Claude Code의 조합 | Obsidian 기반 개인 지식 시스템과 코딩 에이전트를 함께 쓰는 감각을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=OSZdFnQmgRw) | [요약](https://lilys.ai/digest/9501113/10960259?s=1&noteVersionId=7479369&include_suggestion=true) |

### 6. 업무 문서와 공공 보고서 자동화

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| AI 콘텐츠를 공공기관 한글 보고서로 변환하는 Claude Skill | AI 초안을 공공기관 표준 보고서 형식으로 바꾸는 실전형 스킬 | [원본](https://github.com/Kminer2053/public-doc-to-hwpx) | [요약](https://lilys.ai/digest/9592511/11082695?s=1&noteVersionId=7606123&include_suggestion=true) |
| 식약청 공식 의약품 정보 활용 의료 정보 안내 스킬 | 공식 의약품 정보를 AI 스킬로 안전하게 활용하는 방법 | [원본](https://github.com/NomaDamas/k-skill/blob/main/docs/features/mfds-drug-safety.md) | [요약](https://lilys.ai/digest/9586106/11074500?s=1&noteVersionId=7597695&include_suggestion=true) |
| K-Skill(Kakao Skill) | 한국 생활형 서비스와 공공 데이터를 AI 에이전트에 붙이려는 스킬 묶음 | [원본](https://github.com/NomaDamas/k-skill) | [요약](https://lilys.ai/digest/9571859/11055072?s=1&noteVersionId=7577701&include_suggestion=true) |
| 범정부오피스 자동화 자료 1 | 공무원 보고서 편집 자동화를 통해 반복 행정 업무를 줄이는 사례 | [원본](https://www.innovation.go.kr/ucms/bbs/B0000043/view.do?nttId=18191&menuNo=300251&searchType=2&pageIn) | [요약](https://lilys.ai/digest/9571782/11054997?s=1&noteVersionId=7577624&include_suggestion=true) |
| 범정부오피스 자동화 자료 2 | 같은 주제를 다른 요약 흐름으로 다시 보여주는 참고 항목 | [원본](https://www.innovation.go.kr/ucms/bbs/B0000043/view.do?nttId=18191&menuNo=300251&searchType=2&pageIn) | [요약](https://lilys.ai/digest/9571781/11054996?s=1&noteVersionId=7577623&include_suggestion=true) |

### 7. AI 서비스 운영과 제품 전략

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| 마누스 대란이 우리에게 남긴 것들, 교훈 | AI 서비스는 기능뿐 아니라 가격, 환불, 운영 신뢰도까지 같이 봐야 함을 보여주는 사례 | [원본](https://www.youtube.com/watch?v=l8GMqvXAcZ0) | [요약](https://lilys.ai/digest/9555520/11033203?s=1&noteVersionId=7555160&include_suggestion=true) |

### 8. 로컬 AI와 개인 개발환경

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| mq-dir | 병렬 프로젝트와 다양한 아티팩트를 함께 다루기 좋게 설계한 macOS 파일 관리자 | [원본](https://github.com/h5nam/mq-dir) | [요약](https://lilys.ai/digest/9582190/11069287?s=1&noteVersionId=7592327&include_suggestion=true) |
| Winget TUI | Windows 패키지 관리 작업을 터미널 안에서 더 쉽게 다루게 하는 도구 | [원본](https://github.com/shanselman/winget-tui) | [요약](https://lilys.ai/digest/9575217/11059668?s=1&noteVersionId=7582435&include_suggestion=true) |
| DOT Studio | AI 에이전트 협업 구조를 시각적으로 설계하게 돕는 캔버스형 환경 | [원본](https://github.com/dance-of-tal/dot-studio) | [요약](https://lilys.ai/digest/9513020/10975701?s=1&noteVersionId=7495354) |
| zero-native | Zig와 웹 UI를 활용해 데스크톱·모바일 앱을 만드는 대안적 프레임워크 | [원본](https://github.com/vercel-labs/zero-native) | [요약](https://lilys.ai/digest/9506851/10967709?s=1&noteVersionId=7487067) |
| LM Studio Is Getting Insane — Master Local AI Now | 로컬 환경에서 AI 모델을 실제로 돌리는 흐름과 가능성을 보여주는 입문 영상 | [원본](https://www.youtube.com/watch?v=FHzWptAH9V0) | [요약](https://lilys.ai/digest/9501586/10960854?s=1&noteVersionId=7479977) |

### 9. 콘텐츠 제작, 발표, 번역 자동화

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| AI 피팅룸 앱 핵심 기능 완성 | 노코드 환경에서 AI 앱 기능을 실제 서비스 구조로 연결하는 사례 | [원본](https://www.youtube.com/watch?v=ArFWdHMOREY) | [요약](https://lilys.ai/digest/9587675/11076487?s=1&noteVersionId=7599740) |
| Air Translate 실시간 전사 및 번역 | macOS에서 시스템 오디오를 잡아 실시간 전사와 번역까지 수행하는 오픈소스 앱 | [원본](https://github.com/himomohi/AirTranslate) | [요약](https://lilys.ai/digest/9587402/11076112?s=1&noteVersionId=7599351) |
| AirTranslate, MacOS에서 실시간 전사 및 번역 | 같은 프로젝트를 다른 설명 흐름으로 확인할 수 있는 중복 참고 항목 | [원본](https://github.com/himomohi/AirTranslate) | [요약](https://lilys.ai/digest/9571878/11055102?s=1&noteVersionId=7577733) |
| Autopreso | 실시간 음성을 화이트보드 프레젠테이션으로 바꾸는 발표 자동화 실험 도구 | [원본](https://github.com/kunchenguid/autopreso) | [요약](https://lilys.ai/digest/9506889/10967773?s=1&noteVersionId=7487133) |

### 10. 플랫폼·OS와 사용자 생산성

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| iOS 26.5 정식 변화 정리 | OS 업데이트의 작은 변화가 다음 생산성 습관과 AI 기능에 어떤 영향을 주는지 읽게 하는 자료 | [원본](https://www.youtube.com/watch?v=5wXuofjbAu4) | [요약](https://lilys.ai/digest/9555508/11033183?s=1&noteVersionId=7555140) |
| 19 Ways To Use Copy And Paste On Your Mac Beyond the Basics | 기본 OS 기능을 얼마나 깊게 쓰느냐가 생산성 차이로 이어진다는 걸 보여주는 자료 | [원본](https://www.youtube.com/watch?v=nCqqAXFUw5o) | [요약](https://lilys.ai/digest/9532582/11001117?s=1&noteVersionId=7522184) |
| 맥북 활용도 수직상승하는 무료앱 7가지 | 거대한 AI 도구보다 작은 유틸리티가 실제 사용성을 더 바꾸는 순간을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=3fJfKYVQ-vI) | [요약](https://lilys.ai/digest/9486458/10941441?s=1&noteVersionId=7459983) |

### 11. 오픈소스와 개발자 커뮤니티

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| semble_rs | AI 에이전트 친화형 코드 검색 도구로 코드 탐색 효율을 높이려는 프로젝트 | [원본](https://github.com/johunsang/semble_rs) | [요약](https://lilys.ai/digest/9582262/11069388?s=1&noteVersionId=7592429) |
| Dev Workflow Agent | 사용자·LLM·코딩 에이전트 역할을 분리해 개발 워크플로우를 구조화하는 프레임워크 | [원본](https://github.com/bfdcoco/dev-workflow-agent-ko) | [요약](https://lilys.ai/digest/9571934/11055171?s=1&noteVersionId=7577802) |
| Getting started with open source contributions for beginners | 초보자의 오픈소스 기여 진입을 돕는 기본 강의 | [원본](https://www.youtube.com/watch?v=WldXhauP024) | [요약](https://lilys.ai/digest/9532604/11001149?s=1&noteVersionId=7522216) |
| 72시간만에 깃헙에 엄청난 커밋과 PR을 올려 벤당한 사건 | AI 시대의 오픈소스 기여 속도와 커뮤니티 규범 문제를 같이 보여주는 사례 | [원본](https://www.youtube.com/watch?v=BXruBLvln9Y) | [요약](https://lilys.ai/digest/9532533/11001042?s=1&noteVersionId=7522109) |

### 12. AI 에이전트와 코딩 워크플로우

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| google_cloud_ai_agent_trends_2026_report.pdf | 2026년 AI 에이전트 흐름을 비즈니스 가치와 운영 관점에서 읽게 하는 보고서 | PDF 업로드 | [요약](https://lilys.ai/digest/9597192/11088869?s=1&noteVersionId=7612520) |
| 5월 10일 줌미팅 | 실제 현장의 AI 기반 개발 경험과 문제의식을 담은 대화형 자료 | [원본](https://www.youtube.com/watch?v=p_qFcySaM44) | [요약](https://lilys.ai/digest/9501435/10960666?s=1&noteVersionId=7479787) |

### 13. 기타 참고 자료

| 제목 | 한 줄 요약 | 원본 링크 | LilysAI 공개 링크 |
|---|---|---|---|
| Notion CLI | Notion API와 자동화를 터미널 쪽에서 다루게 해주는 공식 도구 | [원본](https://developers.notion.com/cli/get-started/overview) | [요약](https://lilys.ai/digest/9582238/11069359?s=1&noteVersionId=7592400) |
| 심심해서 코덱스와 펜슬로 사주팔자 앱 만드는 영상 | 가벼운 실험 프로젝트도 AI 도구를 통해 빠르게 제품 아이디어로 바꿀 수 있음을 보여주는 영상 | [원본](https://www.youtube.com/watch?v=noRraXqJrrU) | [요약](https://lilys.ai/digest/9534933/11005385?s=1&noteVersionId=7526565) |
