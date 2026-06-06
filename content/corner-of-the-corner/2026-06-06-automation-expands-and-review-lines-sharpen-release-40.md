---
title: 2026-06-06 · 자동화는 넓어지고 검수선은 더 또렷해진다 · 릴리스 40건
description: Hermes, Codex, Claude Code, NotebookLM, HWPX, 음성 AI, 로컬 도구까지 최근 40개 자료를 다시 묶어보니 이제 중요한 차이는 무엇을 자동화하느냐보다 어디서 사람이 검수선을 긋느냐 쪽에서 더 분명하게 갈리고 있었다.
tags:
  - curation
  - ai-trends
  - ai-automation
  - developer-tools
  - education
  - corner-of-the-corner
created: "2026-06-06"
modified: "2026-06-06"
publish: true
cssclasses:
  - quick-note
---

# 2026-06-06 · 자동화는 넓어지고 검수선은 더 또렷해진다 · 릴리스 40건

이번에 받은 <strong>「LilysAI 최근 40개 노트 학습팩」</strong>은 겉으로 보면 도구가 많았다. Hermes, Codex, Claude Code, NotebookLM 계열, HWPX, PromptBridge, 로컬 LLM, 음성 복제, 영상 편집, 법률 검색까지 한 번에 섞여 있었다.

그런데 이번 묶음을 다시 읽으며 제일 크게 남은 건 “도구가 정말 많다”가 아니었다. 오히려 더 또렷했던 건, 이제 자동화는 거의 모든 곳으로 넓어지고 있지만 **사람이 어디서 검수해야 하는지 그 경계는 더 선명해지고 있다**는 점이었다. 이번 40선은 기능 소개 모음이라기보다, AI 시대의 작업 분업표가 점점 더 구체화되는 흐름으로 읽혔다.

## 먼저 결론

- 이번 40선의 핵심은 새 기능 경쟁보다 **자동화 범위와 인간 검수선의 재설계**에 있었다.
- Hermes, Codex, Claude Code, 하네스 자료를 같이 보면 AI 도구는 점점 챗봇이 아니라 **실행 환경과 작업 운영체계**로 이동하고 있다.
- NotebookLM, Open Notebook, Docufinder, Obsidian 계열 흐름은 정보 수집보다 **지식을 오래 남기는 구조**가 더 중요해졌음을 보여준다.
- HWPX, Markdowner, PromptBridge, PPT 자료는 생성 속도보다 **산출물의 형식 품질과 최종 편집 판단**이 병목임을 다시 확인시킨다.
- 음성 AI, 로컬 LLM, 법률 검색, 영상 편집 자료까지 함께 보면 앞으로의 차이는 “무엇을 자동화했는가”보다 **무엇을 반드시 사람이 확인하게 남겨뒀는가**에서 갈릴 가능성이 크다.

## 왜 이번 40선이 유독 운영 이야기처럼 읽혔나

이번 자료는 표면적으로는 범주가 넓다. 에이전트 런타임, 데스크톱 앱, 지식 그래프, 법률 검색, 마크다운 에디터, HWPX 스킬, 음성 복제, 마인드맵, 로컬 LLM까지 한꺼번에 나온다. 원래라면 분산된 관심사처럼 보일 수도 있다.

하지만 자세히 보면 거의 다 같은 질문으로 수렴한다.

- 이 일은 AI에게 어디까지 맡길 수 있나
- 사람은 어느 단계에서 반드시 확인해야 하나
- 결과물은 어디에서 틀어지기 쉬운가
- 반복 작업은 어떤 단위로 스킬화할 수 있나
- 기억과 문서는 어떻게 장기 자산으로 남길까

그래서 이번 40개는 “요즘 이런 도구도 나왔다”는 리스트보다, **AI와 사람이 함께 일하는 경계선이 더 세밀해지는 흐름**을 보여주는 아카이브에 가까웠다.

## 이번 묶음에서 가장 크게 보인 다섯 가지 변화

### 1) 에이전트 도구는 이제 기능보다 작업면 전체를 차지하려 한다

Hermes Agent, Hermes Workspace, Hermes Desktop, Codex App-Server Runtime, LazyCodex, Claude Code Setup, UltraCode-Shim, Harness 100 같은 자료를 한 줄에 세워보면 공통점이 분명하다.

이제 사람들은 AI 도구를 이렇게 묻는다.

- 코드만 잘 쓰나
- 대화만 잘하나

보다,

- 작업을 어디서 시작하고 끝내나
- 메모리와 파일은 어떻게 이어지나
- 하위 에이전트와 스킬은 어떻게 부르나
- 원격 제어와 장기 운영은 어떻게 붙나

를 먼저 본다.

즉 에이전트 경쟁의 무게중심이 단일 답변 품질에서 **작업면 전체를 감싸는 운영 구조**로 옮겨가고 있다. 이번 40선에서 에이전트/코딩 워크플로우가 절반을 차지했다는 사실 자체가 그 증거처럼 보였다.

### 2) 자동화가 넓어질수록 사람의 검수선은 더 중요해진다

이번 자료에서 특히 반복된 건 “AI가 여기까지 대신할 수 있다”는 이야기였다. 전화로 에이전트에게 일 시키기, 원격 바이브코딩, 논문 학습 사이트 자동 구축, PPT 자동 생성, 문서 검색, 마인드맵 시각화, HWPX 생성, 번역 브릿지, 법률 검색까지 범위가 넓다.

그런데 이 흐름의 핵심은 완전 자동화 선언이 아니었다. 오히려 거의 모든 사례가 마지막엔 같은 질문을 남긴다.

- 이 답을 그대로 믿어도 되나
- 이 문서 형식은 실제 제출용으로 괜찮나
- 이 법률 근거는 최신인가
- 이 PPT는 읽는 사람이 봐도 설득력 있나
- 이 음성 결과는 품질과 윤리 기준을 넘었나

즉 자동화가 넓어질수록 경쟁력은 “다 해준다”보다 **어디서 사람이 끼어들어야 하는지 분명하게 설계하는 능력**에 가까워진다. 이번 40선은 그 점을 계속 확인시킨다.

### 3) 지식관리 도구의 승부처는 요약보다 재사용 구조다

Open Notebook, NotebookLM 마인드맵, NotebookLM + Obsidian, Docufinder, Understand Anything 자료를 같이 보면 지식관리 축도 분명하다.

예전엔 자료를 빨리 읽고 요약하는 것이 감탄 포인트였다면, 지금은 그 다음 질문이 더 중요해졌다.

- 다시 찾을 수 있나
- 연결해서 설명할 수 있나
- 팀이나 미래의 나도 이어받을 수 있나
- 요약이 아니라 작업 가능한 지식으로 남았나

그래서 이번 자료는 검색과 요약 기능 자체보다, **지식을 장기적으로 재호출하고 재맥락화하는 구조**가 더 중요해졌다는 흐름으로 읽혔다. 단기 이해보다 장기 축적이 더 중요한 단계로 넘어가는 셈이다.

### 4) 문서 자동화의 병목은 생성이 아니라 형식과 편집 감각이다

Markdowner, HWPX 문서 생성 스킬, 알한글 for macOS, PromptBridge, PPT 제작 노하우 자료를 함께 보면 이쪽도 꽤 선명하다.

문서 자동화는 이미 많이 가능해졌다. 마크다운을 쓰고, HWPX를 만들고, PPT를 초안 내고, 한국어 프롬프트를 영어로 바꿔주는 일까지 AI가 상당 부분 대신한다.

그런데 실제 실무에서 마지막에 남는 건 여전히 형식과 편집 판단이다.

- 줄바꿈과 자간이 읽기 좋은가
- 문서 양식이 제출 환경에 맞는가
- 발표 자료의 밀도와 흐름이 맞는가
- 번역된 프롬프트가 진짜 의도를 보존했는가

즉 이 영역에서 AI는 초안을 빠르게 만들지만, 완성도를 가르는 건 여전히 **사람의 편집 감각과 형식 검수**다.

### 5) 로컬 AI와 음성 AI는 “쓸 수 있나”보다 “계속 돌릴 수 있나” 단계로 왔다

Gemma 양자화, M5 Pro Max 로컬 LLM, LLM Council, Qwen3 한국어 보이스 클론, Hermes 전화 연동 자료는 모두 다른 주제처럼 보이지만 실제로는 같은 방향을 향한다.

이제 질문은 “이게 가능하냐”가 아니다.

- 속도가 실사용 수준인가
- 비용이 유지 가능한가
- 내 장비와 환경에서 계속 돌릴 수 있나
- 개인정보와 음성 데이터는 어떻게 다뤄야 하나

즉 로컬 AI와 음성 AI는 데모 단계를 지나 **운영 가능성, 지속 가능성, 책임 있는 사용** 쪽으로 평가 기준이 이동하고 있다.

## 그래서 이 40개를 어떻게 읽는 게 좋을까

이번 묶음은 처음부터 40개를 다 훑기보다 아래 순서로 읽는 편이 훨씬 선명하다.

### 1단계: 에이전트 작업면부터 본다

- Hermes Agent Codex App-Server Runtime
- Hermes Workspace
- Hermes Desktop
- Claude Code Setup
- Harness 100
- LazyCodex

이 구간은 AI 도구가 답변기가 아니라 **상시 실행되는 작업 환경**이 되어간다는 점을 보여준다.

### 2단계: 자동화와 검수선이 만나는 사례를 본다

- 원격 바이브코딩
- 논문 학습 사이트 자동 구축
- PPT 제작 노하우
- 법률 검색 LexDiff
- 전화형 Hermes 에이전트

이 구간에서는 AI가 일을 대신하는 범위가 넓어질수록, 마지막에 사람이 확인할 기준이 더 중요해진다는 점이 보인다.

### 3단계: 지식관리와 문서 워크플로우를 본다

- Understand Anything
- Open Notebook
- Docufinder
- NotebookLM + Obsidian
- Markdowner
- HWPX 스킬
- PromptBridge

여기서는 자료를 많이 읽는 것보다 **다시 부를 수 있는 구조**를 만드는 일이 핵심이라는 점이 드러난다.

### 4단계: 로컬과 음성 AI를 운영 기준으로 본다

- Gemma 4
- M5 Pro Max 로컬 LLM
- Qwen3 한국어 보이스 클론
- LLM Council

이 구간은 단순 성능 감탄보다 지속 운용성과 품질 기준을 어떻게 세울지를 생각하게 만든다.

## 이번 자료로 바로 떠오르는 활용 아이디어

- 개인 운영 실험: 반복 업무를 Hermes나 Codex 기반 작업면에 붙인 뒤, 사람이 최종 승인하는 단계만 따로 체크리스트로 고정하기
- 수업 설계 실험: NotebookLM, Open Notebook, Docufinder를 비교해 요약, 연결, 재검색이 각각 어떤 학습 효과를 내는지 활동으로 만들기
- 문서 자동화 실험: Markdowner, HWPX 스킬, PromptBridge를 한 세트로 묶어 원자료에서 활동지와 보고서를 동시에 뽑는 워크플로우 설계하기
- 검수 설계 실험: PPT, 법률 검색, 음성 복제 같은 고위험 결과물에 대해 “AI 생성 후 사람 확인 질문 5개”를 공통 규칙으로 만들기
- 로컬 AI 실험: 속도, 비용, 개인정보 기준으로 로컬 모델과 클라우드 모델의 역할 분리를 표로 정리하기

## 실제로 한 것

1. 40개 자료를 그대로 옮기지 않고 에이전트 작업면, 자동화와 검수선, 지식 재사용 구조, 문서 형식 판단, 로컬·음성 운영성이라는 다섯 축으로 다시 묶었다.
2. 에이전트/코딩 워크플로우 자료는 기능 나열보다 작업 환경과 운영체계 관점에서 다시 읽었다.
3. 지식관리와 문서 자동화 자료는 요약 속도보다 재사용성과 형식 품질 쪽으로 논지를 옮겼다.
4. 법률 검색, 음성 AI, 로컬 LLM 자료는 정확도와 실사용 운영 기준이 함께 붙는 영역으로 정리했다.
5. 참고용으로는 다시 찾아보기 쉽도록 원문 링크 표를 뒤에 남겼다.

## 막혔던 지점

> 이번 40선은 흥미로운 도구가 너무 많아서, 그대로 옮기면 풍성한 링크 모음은 되지만 한 문장 논지가 흐려질 위험이 컸다.

그래서 이번 글에서는 각 항목을 균등하게 소개하기보다, 자료들이 공통으로 가리키는 질문을 먼저 세웠다. 그 결과 제일 맞는 한 문장은 “자동화는 넓어지고 검수선은 더 또렷해진다”였다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>에이전트 자료는 모델 성능보다 작업면, 메모리, 위임 구조부터 먼저 읽는다.</li>
  <li>문서·PPT·법률·음성처럼 결과 책임이 큰 영역은 자동화 범위보다 인간 검수 질문을 먼저 적는다.</li>
  <li>지식관리 도구는 요약 품질보다 재검색, 재연결, 재사용 구조가 있는지 본다.</li>
  <li>로컬 AI 자료는 성능 숫자만 보지 말고 장시간 운영 가능성과 비용 구조까지 함께 본다.</li>
  <li>학습 큐레이션 글은 링크 수보다 이번 묶음이 결국 무엇을 말하는지 한 문장으로 먼저 고정한다.</li>
</ul>

## 남겨둘 판단

이번 40선을 다시 묶고 나니 흐름은 꽤 분명했다.

AI는 점점 더 많은 일을 대신하게 되지만, 그만큼 사람의 역할이 사라지는 게 아니라 더 좁고 더 중요한 지점으로 이동한다. 이제 사람은 모든 과정을 직접 수행하는 쪽보다,

- 어떤 일은 자동화해도 되는지
- 어떤 결과는 꼭 다시 확인해야 하는지
- 어떤 형식과 책임은 사람 손에 남겨야 하는지

를 설계하는 쪽에서 더 중요해진다.

그래서 지금 흐름을 제대로 읽고 싶다면 새 도구 이름만 모으는 것으로는 부족하다. 결국 더 오래 남는 사람은 **자동화 범위를 넓히면서도 검수선을 흐리지 않는 사람**일 가능성이 크다. 이번 40선은 그 방향을 꽤 또렷하게 보여주는 묶음이었다.

## 복사용 링크 표

| # | 주제 | 제목 | 공개 요약 | 원문 |
| ---: | --- | --- | --- | --- |
| 1 | AI 에이전트/코딩 워크플로우 | Hermes Agent Codex App-Server Runtime, Hermes의 지능적인 운영 능력과 Codex의 app-server 런타임 활용한 강력한 실행 환경 결합 | [LilysAI](https://lilys.ai/digest/9944542/11545952?s=1&noteVersionId=8086030) | [원문](https://share.note.sx/o65stp06) |
| 2 | 모델/음성/로컬 AI | Gemma 4 with quantization-aware training | [LilysAI](https://lilys.ai/digest/9944338/11545680?s=1&noteVersionId=8085753) | [원문](https://blog.google/innovation-and-ai/technology/developers-tools/quantization-aware-training-gemma-) |
| 3 | AI 에이전트/코딩 워크플로우 | Understand Anything, 코드베이스나 지식 기반 데이터를 대화형 지식 그래프로 변환 | [LilysAI](https://lilys.ai/digest/9944272/11545584?s=1&noteVersionId=8085655) | [원문](https://github.com/Lum1104/Understand-Anything) |
| 4 | 문서/수업자료 제작 | Markdowner, Rust 기반 마크다운 데스크탑 에디터 | [LilysAI](https://lilys.ai/digest/9944240/11545548?s=1&noteVersionId=8085619) | [원문](https://github.com/channprj/markdowner) |
| 5 | AI 에이전트/코딩 워크플로우 | 교사용 보조칠판2026.6.4.버전 : 네이버 블로그 | [LilysAI](https://lilys.ai/digest/9944195/11545508?s=1&noteVersionId=8085576) | [원문](https://m.blog.naver.com/bojogaesam-ai-class/224305916238) |
| 6 | 영상/콘텐츠 제작 | LexDiff: AI 기반 법률 검색 서비스 | [LilysAI](https://lilys.ai/digest/9944119/11545473?s=1&noteVersionId=8085541) | [원문](https://github.com/chrisryugj/lexdiff) |
| 7 | AI 에이전트/코딩 워크플로우 | 헤르메스 에이전트한테 전화 걸기 — 일레븐랩스로 AI에게 통화하는 법 | [LilysAI](https://lilys.ai/digest/9944054/11545438?s=1&noteVersionId=8085506) | [원문](https://bbojjak-library.gpters.org/column/hermes-agent-phone-call) |
| 8 | 개발 도구/AI 서비스 | 출처: 중앙일보 | [LilysAI](https://lilys.ai/digest/9941673/11542225?s=1&noteVersionId=8082227) | [원문](https://share.google/VoITj1hDBjCugVyiF) |
| 9 | AI 에이전트/코딩 워크플로우 | Hermes Workspace | [LilysAI](https://lilys.ai/digest/9941306/11541740?s=1&noteVersionId=8081727) | [원문](https://github.com/outsourc-e/hermes-workspace) |
| 10 | 지식관리/검색 | GitHub - lfnovo/open-notebook: An Open Source implementation of Notebook LM with more flexibility | [LilysAI](https://lilys.ai/digest/9941285/11541712?s=1&noteVersionId=8081699) | [원문](https://github.com/lfnovo/open-notebook) |
| 11 | 영상/콘텐츠 제작 | 컷백 셀렉츠 - 영상 편집의 시작 | [LilysAI](https://lilys.ai/digest/9938406/11537851?s=1&noteVersionId=8077699) | [원문](https://cutback.video/ko/selects) |
| 12 | AI 에이전트/코딩 워크플로우 | 원격 바이브코딩 완벽공략집 | [LilysAI](https://lilys.ai/digest/9929349/11526357?s=1&noteVersionId=8065831) | [원문](https://www.youtube.com/watch?v=L2P0qn0Doio) |
| 13 | 지식관리/검색 | 노트북 LM 마인드맵, 이제 컬러풀하게 만드세요! | [LilysAI](https://lilys.ai/digest/9929311/11526302?s=1&noteVersionId=8065772) | [원문](https://www.youtube.com/watch?v=eqnMrRQRHJE) |
| 14 | AI 에이전트/코딩 워크플로우 | Opus 4.8로 논문 학습 사이트 만들어보기 | [LilysAI](https://lilys.ai/digest/9929292/11526285?s=1&noteVersionId=8065752) | [원문](https://www.youtube.com/watch?v=zAiiEsVx7Eg) |
| 15 | AI 에이전트/코딩 워크플로우 | M5 Pro MAX 128GB 로컬 LLM 실사용 | [LilysAI](https://lilys.ai/digest/9929280/11526270?s=1&noteVersionId=8065737) | [원문](https://www.youtube.com/watch?v=1y9LCBuSTS8) |
| 16 | 개발 도구/AI 서비스 | 99.9%가 모르는 AI 에이전트를 학습시키는 천재적 방법 | [LilysAI](https://lilys.ai/digest/9929253/11526238?s=1&noteVersionId=8065704) | [원문](https://www.youtube.com/watch?v=vrc0Uv2BfRk) |
| 17 | 개발 도구/AI 서비스 | 클로드 코드 Dynamic Workflow | [LilysAI](https://lilys.ai/digest/9929241/11526226?s=1&noteVersionId=8065692) | [원문](https://www.youtube.com/watch?v=fInMcawbKng) |
| 18 | AI 에이전트/코딩 워크플로우 | 헤르메스 에이전트 데스크탑 앱 출시! | [LilysAI](https://lilys.ai/digest/9910074/11501383?s=1&noteVersionId=8039662) | [원문](https://www.youtube.com/watch?v=3FGIrnMvtr4) |
| 19 | 모델/음성/로컬 AI | LLM Council | [LilysAI](https://lilys.ai/digest/9908538/11499561?s=1&noteVersionId=8037798) | [원문](https://github.com/karpathy/llm-council) |
| 20 | AI 에이전트/코딩 워크플로우 | 그냥 “PPT 만들어줘”라고 하면 망합니다 | [LilysAI](https://lilys.ai/digest/9903328/11492474?s=1&noteVersionId=8030300) | [원문](https://www.youtube.com/watch?v=BboGm3FR4hw) |
| 21 | AI 에이전트/코딩 워크플로우 | UltraCode-Shim, Claude Code의 UltraCode 모드의 오픈소스 버전 | [LilysAI](https://lilys.ai/digest/9892154/11477710?s=1&noteVersionId=8015062) | [원문](https://github.com/OnlyTerp/UltraCode-Shim) |
| 22 | AI 에이전트/코딩 워크플로우 | Hermes Desktop | [LilysAI](https://lilys.ai/digest/9892146/11477701?s=1&noteVersionId=8015053) | [원문](https://hermes-agent.nousresearch.com/desktop) |
| 23 | 문서/수업자료 제작 | 알한글 for MacOS | [LilysAI](https://lilys.ai/digest/9892134/11477685?s=1&noteVersionId=8015037) | [원문](https://github.com/postmelee/alhangeul-macos) |
| 24 | 문서/수업자료 제작 | HWPX 문서 생성 스킬 | [LilysAI](https://lilys.ai/digest/9885461/11468991?s=1&noteVersionId=8006012) | [원문](https://github.com/jkf87/hwpx-skill) |
| 25 | AI 에이전트/코딩 워크플로우 | Hermes 설치 후, 반드시 알아야 할 구조의 파악 | [LilysAI](https://lilys.ai/digest/9885440/11468966?s=1&noteVersionId=8005986) | [원문](https://www.youtube.com/watch?v=c6Cg2gfkqC8) |
| 26 | AI 에이전트/코딩 워크플로우 | 맥킨지 스타일의 PPT 만들기 스킬 | [LilysAI](https://lilys.ai/digest/9885391/11468919?s=1&noteVersionId=8005935) | [원문](https://github.com/seulee26/mckinsey-pptx) |
| 27 | AI 에이전트/코딩 워크플로우 | 윈도우에서 Codex 앱 사용하는 방법 | [LilysAI](https://lilys.ai/digest/9885223/11468758?s=1&noteVersionId=8005771) | [원문](https://www.youtube.com/watch?v=KckQkdcN45w) |
| 28 | AI 에이전트/코딩 워크플로우 | Harness 100 Project | [LilysAI](https://lilys.ai/digest/9876377/11457104?s=1&noteVersionId=7993687) | [원문](https://github.com/revfactory/harness-100) |
| 29 | 개발 도구/AI 서비스 | 초간단 하네스 사용법 | [LilysAI](https://lilys.ai/digest/9876343/11457064?s=1&noteVersionId=7993647) | [원문](https://www.youtube.com/watch?v=9bNL2urCdHU) |
| 30 | 개발 도구/AI 서비스 | AI-First-Company-Principles-WhitePaper | [LilysAI](https://lilys.ai/digest/9876307/11457018?s=1&noteVersionId=7993597) | [원문](https://share.note.sx/eebecf5e-e1a0-476a-b7f5-bad484ad068a) |
| 31 | 모델/음성/로컬 AI | 한국어 보이스 클론 만드는 Qwen3-TTS Colab Quickstart | [LilysAI](https://lilys.ai/digest/9856929/11432147?s=1&noteVersionId=7967819) | [원문](https://github.com/azzselloo-sudo/qwen3-korean-voice-clone) |
| 32 | 지식관리/검색 | Docufinder, 문서 검색, AI 질의 응답 | [LilysAI](https://lilys.ai/digest/9874880/11455224?s=1&noteVersionId=7991768) | [원문](https://github.com/chrisryugj/Docufinder) |
| 33 | AI 에이전트/코딩 워크플로우 | Odysseus, AI 작업 공간을 개인 서버에 직접 구축 | [LilysAI](https://lilys.ai/digest/9871772/11451040?s=1&noteVersionId=7987444) | [원문](https://github.com/pewdiepie-archdaemon/odysseus) |
| 34 | AI 에이전트/코딩 워크플로우 | Claude Code Setup, 개인 AI Work OS Harness | [LilysAI](https://lilys.ai/digest/9857373/11432681?s=1&noteVersionId=7968391) | [원문](https://hugh-kim.space/) |
| 35 | 문서/수업자료 제작 | PromptBridge, 한글 프롬프트를 영어로 변환하는 데스크탑 브릿지 | [LilysAI](https://lilys.ai/digest/9856971/11432200?s=1&noteVersionId=7967880) | [원문](https://github.com/MinkyuTheBuilder/PromptBridge) |
| 36 | AI 에이전트/코딩 워크플로우 | LazyCodex | [LilysAI](https://lilys.ai/digest/9849166/11421427?s=1&noteVersionId=7956703) | [원문](https://github.com/code-yeongyu/lazycodex) |
| 37 | 문서/수업자료 제작 | OpenHuman 프라이빗하고 강력한 에이전트 | [LilysAI](https://lilys.ai/digest/9848772/11420886?s=1&noteVersionId=7956142) | [원문](https://github.com/tinyhumansai/openhuman) |
| 38 | 지식관리/검색 | NotebookLM + Obsidian Changed How I Retain Information | [LilysAI](https://lilys.ai/digest/9841206/11410633?s=1&noteVersionId=7945625) | [원문](https://www.youtube.com/watch?v=sRjh5dM4cko) |
| 39 | AI 에이전트/코딩 워크플로우 | Hermes Agent 집중 과정: 자가 진화 스킬, 메모리, GEPA 및 10개 에이전트 확장 | [LilysAI](https://lilys.ai/digest/9841194/11410617?s=1&noteVersionId=7945608) | [원문](https://www.youtube.com/watch?v=bNp6YcKBLgY) |
| 40 | 개발 도구/AI 서비스 | 5월30 줌미팅 세미나(게임 만들기 시연, 코너속에 코너) | [LilysAI](https://lilys.ai/digest/9841174/11410586?s=1&noteVersionId=7945576) | [원문](https://www.youtube.com/watch?v=VkusFBL4eMU) |
