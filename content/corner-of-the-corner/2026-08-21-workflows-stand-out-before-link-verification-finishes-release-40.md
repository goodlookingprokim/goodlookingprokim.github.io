---
title: 2026-08-21 · 공개 전환이 덜 끝나도 작업 흐름은 또렷해진다 · 릴리스 40건
description: 최근 40개 학습 노트를 다시 묶어보니, 이번 흐름의 핵심은 AI 에이전트·바이브 코딩·문서 자동화·교육용 Gemini 자체보다 공개 가능한 링크와 반복 가능한 작업 절차를 얼마나 분리해 관리하느냐에 있었다.
tags:
  - curation
  - ai-trends
  - ai-agents
  - vibe-coding
  - document-automation
  - corner-of-the-corner
created: "2026-08-21"
modified: "2026-08-21"
publish: true
cssclasses:
  - quick-note
---

# 2026-08-21 · 공개 전환이 덜 끝나도 작업 흐름은 또렷해진다 · 릴리스 40건

이번에 받은 <strong>「최근 AI·기술 동향 학습 큐레이션 40」</strong>은 완성본이라기보다, LilysAI에서 최근 40개를 끌어와 다시 읽고 공개 가능한 링크 상태까지 점검하던 중간 산출물에 가깝다. 그래서 이 묶음은 단순한 “요즘 뭐가 떴나” 목록보다도, <strong>무엇이 이미 바깥으로 공유 가능한 상태인지, 무엇은 아직 내부 검토 단계인지</strong>를 먼저 읽게 만든다.

그런데 바로 그 점이 오히려 이번 40선을 더 또렷하게 보이게 한다. AI 에이전트, 바이브 코딩, Claude/Codex/Hermes/Grok 계열 워크플로우, 문서 자동화, 미디어 생성, 교육용 Gemini 활용이 넓게 퍼져 있어도, 실제로 오래 남는 차이는 새 도구 이름 자체보다 <strong>공개 가능한 요약 링크, 원본 확인 가능성, 반복 가능한 작업 절차</strong>를 얼마나 분리해 관리하느냐 쪽에 있었다.

## 먼저 결론

- 이번 40선은 새 도구 감탄보다 <strong>공개 가능한 링크와 검증 가능한 작업 절차를 같이 관리하는 감각</strong>이 더 중요해졌다는 점을 보여준다.
- AI 에이전트와 바이브 코딩 쪽에서는 모델 비교보다 <strong>스킬, MCP, 하네스, 멀티에이전트 운영</strong> 같은 실행 구조가 더 본체처럼 보인다.
- 문서 자동화 쪽에서는 HWP, 계약서, 구글시트, 세컨드 브레인처럼 <strong>실제 현장 파일과 검색 흐름</strong>이 중심으로 내려왔다.
- 미디어 생성과 교육 활용 쪽에서는 숏폼, 음성, 화이트보드 애니메이션, Gemini Spark처럼 <strong>결과물 제작과 수업 적용</strong>이 더 실전적으로 붙고 있다.
- 무엇보다 이번 묶음은 “좋은 링크 40개”보다 <strong>아직 덜 끝난 검증 상태까지 함께 기록하는 운영 습관</strong>이 신뢰를 만든다는 사실을 더 강하게 보여준다.

## 이번 학습팩은 왜 '중간 산출물'이라는 점이 중요한가

첨부된 원문은 처음부터 배포본이 아니라, 남은 공개 전환과 링크 검증을 이어가기 위한 검토용 학습팩이라고 밝히고 있다. 이 전제를 빼면 글 전체를 잘못 읽게 된다.

이번 상태는 대략 이렇게 나뉜다.

| 상태 | 건수 | 의미 |
|---|---:|---|
| `validated_browser` | 4 | Chrome 공유 대화상자에서 공개 링크를 직접 확인한 항목 |
| `legacy_needs_validation` | 15 | 목록상 공개 링크는 보이지만 공유 대화상자에서 최종 재확인을 못 한 항목 |
| `unresolved` | 21 | 공개 링크를 아직 확인하지 못했거나 공개 전환이 끝나지 않은 항목 |

즉 이 묶음은 “40개 전부 바로 공유 가능한 추천 링크”가 아니라, <strong>40개를 어디까지 공개 가능한 상태로 밀어놨는지 보여주는 작업 기록</strong>에 더 가깝다. 이 차이를 분명히 써두는 것이 오히려 블로그 글의 신뢰도를 높인다.

## 이번 40선에서 먼저 보인 다섯 가지 흐름

### 1) 에이전트는 이제 도구가 아니라 작업 운영면처럼 읽힌다

이번 목록에서 가장 먼저 눈에 띄는 건 AI 에이전트와 바이브 코딩 관련 항목의 밀도다. Auto Research, 챗GPT + MCP, Oh My Hermes, Grok Bot, Claude Skill, Graph Engineering, Claude Video, Meta MCP 문서, book-to-skill, claude-scaffold 같은 자료를 한 줄로 놓으면 공통점이 꽤 뚜렷하다.

- 단일 채팅창보다 멀티에이전트 운영
- 모델 하나보다 역할 분리와 라우팅
- 프롬프트 한 번보다 스킬과 재사용 구조
- 대답 품질보다 실행 절차와 검증 가능성

즉 이번 흐름의 중심은 “어느 모델이 더 세냐”가 아니라, <strong>AI를 어떻게 연결하고, 굴리고, 다시 쓰게 만들 것인가</strong>에 있다.

### 2) 문서 자동화는 점점 더 한국어 실무 파일 안쪽으로 내려온다

kayatext, Korean Law MCP, 세컨드브레인 구축, 학생부·강의영상 검색, 정부 공공데이터 활용, 구글시트 대시보드, HWP용 알한글 같은 항목은 전부 멋진 데모보다 훨씬 현실적인 층을 건드린다.

- 한글 문서에서 텍스트를 뽑기
- 법령과 계약서 검토 흐름에 MCP 연결하기
- 영상, 강의, 영수증, 한글 파일을 한 폴더 안에서 다시 찾기
- 공공데이터 API를 불러와 실제 대시보드 만들기

교사나 개발자 관점에서 중요한 건 바로 여기다. 자동화가 더 이상 “예쁘게 요약해준다” 수준이 아니라, <strong>실제 파일과 실제 검색 병목을 얼마나 줄여주느냐</strong>로 내려오고 있다.

### 3) 미디어 생성은 텍스트를 넘어서 제작 파이프라인 쪽으로 이동한다

나레이션 붙는 숏폼, 무료 GPU 음성 생성, 화이트보드 애니메이션 자동화, Fish Audio, ElevenLabs MCP 같은 항목들은 모두 비슷한 방향을 가리킨다. 이제 AI는 아이디어를 말해주는 수준이 아니라, <strong>영상, 음성, 자막, 애니메이션 조립 흐름</strong>까지 직접 건드리는 쪽으로 확장되고 있다.

이 변화가 중요한 이유는 간단하다. 콘텐츠 제작의 핵심이 단순 생성보다 <strong>여러 단계가 연결된 파이프라인</strong>으로 옮겨가기 때문이다. 그래서 앞으로는 결과 이미지 한 장보다, 어떤 순서로 목소리와 자막과 장면을 붙였는지가 더 큰 자산이 된다.

### 4) 교육용 Gemini와 세컨드 브레인 흐름은 '검색 가능한 개인 지식면'으로 모인다

교육자용 Gemini Spark, Google Drive에서 Gemini Notebook으로 소스 자동 추가, 세컨드브레인 구축, 강의영상·한글 파일 검색 같은 항목은 따로 보면 흩어져 보이지만, 같이 읽으면 꽤 선명하다.

- 자료를 모은다
- 텍스트화한다
- 질문 가능한 상태로 만든다
- 다시 수업이나 업무에 붙인다

즉 이 흐름의 핵심은 모델 사용법이 아니라, <strong>내 자료가 AI가 다시 찾고 설명할 수 있는 지식면으로 바뀌는가</strong>에 있다.

### 5) 이번 묶음의 진짜 메시지는 링크 검증 자체도 하나의 작업이라는 점이다

이번 파일에서 가장 인상적인 부분은 사실 개별 도구 소개보다도, 각 항목마다 `validated_browser`, `legacy_needs_validation`, `unresolved` 같은 상태가 붙어 있다는 점이다. 이건 사소해 보이지만 굉장히 중요하다.

좋은 큐레이션은 단순히 링크를 많이 모으는 데서 끝나지 않는다.

- 바깥에 바로 보내도 되는 링크인가
- noteVersionId까지 확인됐는가
- 목록에만 있고 실제 공유 대화상자에서 확인은 못 했는가
- 아직 공개 전환 자체가 안 끝났는가

이런 차이를 함께 기록해야, 나중에 다시 꺼내 쓸 때도 신뢰가 남는다. 이번 40선은 바로 그 운영 감각을 꽤 잘 보여준다.

## 지금 이 묶음을 어떻게 읽으면 좋은가

이번 글은 40개를 처음부터 순서대로 다 보기보다, 아래 순서로 보는 편이 더 좋다.

### 1단계: 공개 확인 4건부터 본다

이미 브라우저에서 공개 확인된 4건은 이 묶음의 가장 안전한 출발점이다.

- 개발 1도 몰라도 됩니다. 예약 시스템 무료로 만드는 법
- ScrapeGraphAI
- Connect AI Agents to Meta with MCP
- 서초바탕체

이 네 개는 링크를 다시 전달하거나 후속 정리에 재사용하기 가장 편하다.

### 2단계: `legacy_needs_validation` 항목을 흐름용 참고 자료로 본다

이 그룹은 공개 링크가 있더라도 최종 재확인이 아직 덜 끝났기 때문에, <strong>방향을 읽는 참고 자료</strong>로는 좋지만 바로 외부 공유용 목록으로 단정하면 안 된다. Auto Research, 챗GPT 바이브코딩, Claude Skill, 무료 GPU 음성 생성, 공공데이터, 바이브코딩 강의, book-to-skill, claude-scaffold 같은 항목이 여기에 많다.

### 3단계: `unresolved` 항목은 다음 검증 큐로 본다

이 항목들은 아직 공개 전환 자체가 안 끝났거나, 공유 링크를 확인하지 못했다. 그러므로 “좋은 자료”인지와 별개로, <strong>지금 당장 전달 가능한 링크 자산</strong>으로 보기는 어렵다. 이 구간이 바로 다음 작업에서 이어서 정리할 우선순위가 된다.

## 다음에 바로 쓸 검증 기준

- 공개 링크가 보여도 바로 배포본으로 단정하지 말고, share dialog 기준 최종 확인 여부를 상태로 남긴다.
- `legacy_needs_validation`과 `unresolved`는 같은 미완료가 아니라는 점을 분리해서 기록한다.
- 나중에 블로그 밖으로 링크를 다시 묶어 보낼 때는 `validated_browser` 항목만 우선 후보로 쓴다.
- 요약 품질이 거칠게 뽑힌 항목은 원본 가치와 요약 품질을 따로 본다.
- 링크 표는 길더라도 유지하되, 상태 구분이 첫눈에 읽히게 설명 문단을 앞에 둔다.

## 복사용 링크 표

| 카테고리 | 주제 | 제목 | 원본 링크 | 릴리스 공개 링크 |
|---|---|---|---|---|
| 검토 필요 | 1. 안드레 카파시의 Auto Research AI Agent 소개 [1] | 자는 동안에도 최고의 모델을 찾아내는 Agent 만들기 \| Auto Research | [원본](https://www.youtube.com/watch?v=KlzWWGIdlZs) | [공개 요약](https://lilys.ai/digest/11048798/13006598?s=1) |
| 검토 필요 | 1. 챗GPT와 코덱스의 차이점 및 챗GPT 코딩의 한계 [1] | 챗GPT 알뜰하게 본전 뽑는 방법 \| 바이브코딩 | [원본](https://www.youtube.com/watch?v=dKQQs-z_E64) | [공개 요약](https://lilys.ai/digest/11048526/13006277?s=1) |
| 검토 필요 | 1. 개요 | Oh My Hermes 사용법: Hermes Agent 메모리·스킬·모델 라우팅 전부 딸깍! | [원본](https://www.youtube.com/watch?v=wNZkp9fvW0E) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 에이전트 시대의 도래와 주요 에이전트 소개 [1] | 이제 AI 에이전트가 대신하는 시대! Grok Bot vs Buzz vs Hermes 비교! | [원본](https://www.youtube.com/watch?v=UMDSNYu7iNU) | 공개 전환 미완료 |
| 검토 필요 | kayatext | GitHub - kjh0523/kayatext: 한글(HWP)·엑셀·워드 문서에서 AI 가 읽을 텍스트를 뽑습니다. | [원본](https://github.com/kjh0523/kayatext) | [공개 요약](https://lilys.ai/digest/11037231/12991429?s=1) |
| 검토 필요 | 목소리에 착 붙는 숏폼,오늘 하나 만들어 봅니다 | 나레이션 붙는 숏폼 | [원본](https://remotion-shorts-guide.vercel.app/) | 공개 전환 미완료 |
| 공개 확인 | 1. 개발 지식 없이 클로드로 예약 시스템 구축하기 [1] | 개발 1도 몰라도 됩니다. 예약 시스템 무료로 만드는 법 \| 클로드 웹사이트 2탄 | [원본](https://www.youtube.com/watch?v=lCJ5_vWCVpg) | [공개 요약](https://lilys.ai/digest/11026169/12977235?s=1&noteVersionId=9571202) |
| 검토 필요 | 1. 클로드(Claude)와 코리안 로우 MCP(Korean Law MCP)를 활용한 법률 업무 효율화 [1] | 클로드 계약서 검토부터 내용증명 까지 \| Claude code 한국 법령 MCP 실전 활용 \| Korean Law MCP | [원본](https://www.youtube.com/watch?v=z-cxE0yus4g) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 스킬의 등장 배경 및 필요성 [1] | 요즘 AI 바이브코딩 고수들이 스킬을 쓰는 이유 | [원본](https://www.youtube.com/watch?v=dsP4AR6lFUQ) | [공개 요약](https://lilys.ai/digest/11025412/12976339?s=1) |
| 검토 필요 | 1. 세컨드 브레인, 만들고 나서 무엇을 해야 하는가 [1] | 세컨드브레인 만들기 \| 클로드 코드로 한글파일·강의영상까지 검색 (코딩 없이 4분) | [원본](https://www.youtube.com/watch?v=MoYGM-HZc2I) | 공개 전환 미완료 |
| 검토 필요 | 1. 유료 AI 음성 서비스의 한계와 대안의 필요성 [1] | 내 목소리 AI, 제 컴퓨터에 설치했습니다 (무료·무제한·상업이용 OK) | [원본](https://www.youtube.com/watch?v=UzzTPBvOmaA) | 공개 전환 미완료 |
| 검토 필요 | 1. 내 컴퓨터가 아닌 외부 GPU로 AI 음성 생성하기 [1] | 클로드 코드한테 시켰더니 무료 GPU로 제 목소리를 뽑아왔습니다 | [원본](https://www.youtube.com/watch?v=aTtnuVokUNk) | [공개 요약](https://lilys.ai/digest/11025290/12976198?s=1) |
| 검토 필요 | 1. AI가 답하지 못하는 질문, 공공데이터로 해결하다 [1] | 정부가 공짜로 푸는 데이터 11,915개, 뭘 할 수 있는지 직접 만들어봤습니다 | [원본](https://www.youtube.com/watch?v=Ifq0Yt7Thzc) | [공개 요약](https://lilys.ai/digest/11025056/12975861?s=1) |
| 검토 필요 | 1. AI 엔지니어링 패러다임의 진화 소개 [1] | Graph 엔지니어링 쉽게 설명해드림 - AI 엔지니어링 패러다임의 진화 🚀 | [원본](https://www.youtube.com/watch?v=MRTFz8Bust0) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 앱 보안 사고의 심각성 및 주요 원인 [1] | AI로 만들 앱이 털릴 수 밖에 없는 이유 | [원본](https://www.youtube.com/watch?v=UzsLfQjpXJw) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 시대의 바이브 코딩과 레버리지 [1] | 3시간 순삭) 55개 기술 의사결정, 소스코드 해설까지! 현존 바이브코딩 기본 강의 중 가장 실전적인 강의 | [원본](https://www.youtube.com/watch?v=K6Rsy-pHBi0) | [공개 요약](https://lilys.ai/digest/11024716/12975424?s=1) |
| 검토 필요 | 1. AI 지능 활용 방식의 변화: '빌려 쓰는 지능'에서 '나만의 AGI' 구축으로 [2] | 상위 0.1% 직행! AI에 내 지식을 쌓는 방법 현장 강의 (시연, 개념 전체 포함) | [원본](https://www.youtube.com/watch?v=21qi89gSy-A) | [공개 요약](https://lilys.ai/digest/11024634/12975336?s=1) |
| 검토 필요 | 1. 인공지능 시대, 출발선이 다시 제로가 되다 [1] | [시즌 3] 인공지능 시대에는 어떻게 공부를 해야 할까? 사람은 정말로 필요 없는 걸까? | [원본](https://www.youtube.com/watch?v=IiKkUFQTFvQ) | [공개 요약](https://lilys.ai/digest/11024539/12975220?s=1) |
| 검토 필요 | 1. AI를 활용한 RPG 게임 개발 소개 [1] | [시즌 3] 클로드 코드 + 코덱스로 RPG 게임 만들기 | [원본](https://www.youtube.com/watch?v=_IyVJ7ZD9H4) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 화이트보드 애니메이션 영상 자동화 소개 [1] | 코덱스로 AI 화이트보드 애니메이션 영상 자동화 만들기(무료 오픈소스 대공개) | [원본](https://www.youtube.com/watch?v=aelyPpDGiZQ) | 공개 전환 미완료 |
| 공개 확인 | 🕷️ ScrapeGraphAI: You Only Scrape Once | GitHub - ScrapeGraphAI/Scrapegraph-ai: Python scraper based on AI · GitHub | [원본](https://github.com/ScrapeGraphAI/Scrapegraph-ai) | [공개 요약](https://lilys.ai/digest/11024017/12974585?s=1&noteVersionId=9568438) |
| 검토 필요 | 목소리에 착 붙는 숏폼,오늘 하나 만들어 봅니다 | 나레이션 붙는 숏폼 | [원본](https://remotion-shorts-guide.vercel.app/) | 공개 전환 미완료 |
| 검토 필요 | /watch | Claude Video | [원본](https://github.com/bradautomates/claude-video) | 공개 전환 미완료 |
| 검토 필요 | 1. ElevenLabs MCP, Claude에 통합: 음성 및 채팅 에이전트 관리의 새로운 시대 [1] | Introducing the ElevenLabs MCP, now available in Claude. | [원본](https://www.youtube.com/watch?v=wHTkD5eagGU) | 공개 전환 미완료 |
| 검토 필요 | 1. Google Workspace Studio를 활용한 Gemini Notebook 소스 자동 추가 기능 [1] | Automatically Add Google Drive Sources to Gemini Notebook | [원본](https://www.youtube.com/watch?v=wz2QRwV0lVQ) | 공개 전환 미완료 |
| 공개 확인 | Connect AI Agents to Meta with MCP | Connect AI Agents to Meta with MCP \| Developer Documentation | [원본](https://developers.facebook.com/documentation/mcp) | [공개 요약](https://lilys.ai/digest/10992155/12936318?s=1&noteVersionId=9529113) |
| 검토 필요 | 1. AI 시대, 마케터의 역할 변화와 생산성 혁신 [1] | "AI는 실행하고, 마케터는 결정합니다" 15년차 퍼포먼스 마케터가 공개한 12단계 자동화 (김형태 대표, 데일리그로스) | [원본](https://www.youtube.com/watch?v=FZzxy_0FT0o) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 활용의 변화와 실제 시간 및 비용 절약 사례 [1] | 2026 최신 AI 사용법｜ChatGPT·Gemini, 제가 실제로 잘 쓰는 기능 10가지 | [원본](https://www.youtube.com/watch?v=7TbZ6KweVFs) | 공개 전환 미완료 |
| 검토 필요 | 1. Grokbot 소개: AI 에이전트의 새로운 지평 [1] | Cursor에서 방금 출시한 Grok Bot (매우 쉬운 AI 에이전트) | [원본](https://www.youtube.com/watch?v=QTcZPI-g7is) | 공개 전환 미완료 |
| 검토 필요 | 1. 개요 | Claude Opus 5로 수준 높은 Three.js 웹사이트를 구축하는 방법 | [원본](https://www.youtube.com/watch?v=G-F5Qvy-7KM) | [공개 요약](https://lilys.ai/digest/10984632/12933699?s=1) |
| 공개 확인 | 서초바탕 (Seocho Batang) | 서초바탕체: 법원 판결문에 사용하는 글자체를 오마주하여 만듦 | [원본](https://github.com/iwantanid/SeochoBatang-Font) | [공개 요약](https://lilys.ai/digest/10983394/12924972?s=1&noteVersionId=9517515) |
| 검토 필요 | Alhangeul | 알한글: macOS에서 HWP 시용하는 오픈소스 앱 | [원본](https://github.com/postmelee/alhangeul-macos) | 공개 전환 미완료 |
| 검토 필요 | 1. AI 기반 학습 도구 및 게임 개발 현황 공유 [1] | 8월15일 줌세미나 영상(코너속의코너, Seedance2.5, Three.js+WebGL2, Fish audio, 회원님들의 게임제작현황) | [원본](https://www.youtube.com/watch?v=0s-orFa2oRw) | [공개 요약](https://lilys.ai/digest/10972641/12911061?s=1) |
| 검토 필요 | book-to-skill | book-to-skill | [원본](https://github.com/virgiliojr94/book-to-skill) | [공개 요약](https://lilys.ai/digest/10960473/12895147?s=1) |
| 검토 필요 | claude-scaffold | Claude Code가 마치 규칙을 아는 팀원 처럼 작동하도록 돕는다. | [원본](https://github.com/LeeYudok/claude-scaffold) | [공개 요약](https://lilys.ai/digest/10960453/12895122?s=1) |
| 검토 필요 | 1. Grok Bot의 주요 특징 및 장점 [1] | Grok Bot 너무 좋습니다. Hermes, Openclaw 다 지웠어요. | [원본](https://www.youtube.com/watch?v=MzObKXUaSbc) | [공개 요약](https://lilys.ai/digest/10960404/12895055?s=1) |
| 검토 필요 | 1. 구글 시트와 무료 Gemini를 활용한 실시간 대시보드 구축 [1] | 와.. 이제 구글시트가 앱이 됩니다! \| 무료 Gemini로 실시간 대시보드 만드는 법 | [원본](https://www.youtube.com/watch?v=XSsKjS1z7Yg) | [공개 요약](https://lilys.ai/digest/10960394/12895044?s=1) |
| 검토 필요 | PolarBears's Story | 진짜 매일 쓰는 Claude Skill 3개 (꾸준히 쓰는 이유) | [원본](https://www.youtube.com/watch?v=VABNRP-S124) | 공개 전환 미완료 |
| 검토 필요 | 코드팩토리 | Grok 4.6 너무 저렴한데 이정도로 잘한다고? | [원본](https://www.youtube.com/watch?v=QzOzVIMuFhk) | 공개 전환 미완료 |
| 검토 필요 | 필로소피 AI 교육 | 교육자분들을 위한 Gemini Spark 활용법 (출시는 조금 늦었지만, 역시나 저력이 있는 Gemini) | [원본](https://www.youtube.com/watch?v=YJ8G1h23THg) | 공개 전환 미완료 |

## 용어 정리

| 용어 | 쉬운 설명 | 생활 속 예시 |
|---|---|---|
| 공개 요약 링크 | LilysAI 요약을 링크가 있는 사람이 볼 수 있게 만든 주소입니다. | 수업 자료 링크처럼 전달할 수 있는 상태입니다. |
| noteVersionId | LilysAI 요약 노트의 특정 버전 번호입니다. | 같은 문서의 1차, 2차 수정본을 구분하는 번호와 비슷합니다. |
| AI 에이전트 | 목표를 받고 여러 단계를 이어서 처리하는 AI 작업자입니다. | 자료를 찾고 요약하고 표로 정리하는 일을 순서대로 맡기는 비서와 비슷합니다. |
| 바이브코딩 | 자연어 지시와 AI 도움을 받아 빠르게 앱이나 웹을 만드는 방식입니다. | 개발자가 아니어도 예약 페이지 초안을 만들어 보는 실습입니다. |
| MCP | AI가 외부 도구나 문서, 브라우저와 연결되는 표준 방식입니다. | 여러 기기를 같은 규격 포트에 꽂는 것과 비슷합니다. |

## 남겨둘 판단

이번 40개를 한 문장으로 줄이면 이렇다.

> 이제 중요한 건 새 AI 도구를 빨리 아는가보다, 공개 가능한 링크와 반복 가능한 작업 절차를 얼마나 분리해서 관리하고 끝까지 검증하느냐에 더 가깝다.

그래서 다음에 비슷한 학습팩을 다시 받으면, 먼저 아래를 보면 된다.

- 이 항목은 지금 바로 밖으로 공유해도 되는가
- 공개 링크와 원본 링크가 둘 다 살아 있는가
- 요약 품질과 원본 가치가 분리돼 있는가
- 이 자료가 한 번 보고 끝날 소식인지, 다음 작업에서 다시 꺼내 쓸 절차인지

이 네 가지가 선명하면, 큐레이션은 단순한 링크 모음이 아니라 진짜로 다시 쓰이는 작업 자산이 된다.
