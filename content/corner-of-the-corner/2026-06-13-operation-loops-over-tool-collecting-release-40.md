---
title: 2026-06-13 · 도구 수집보다 운영 루프가 먼저다 · 릴리스 40건
description: 에이전트 운영, LLM Wiki, 로컬 모델, 디자인 자동화까지 최근 40개 자료를 다시 묶어보니 이제 중요한 차이는 도구를 더 많이 아는가보다 자료를 구조화하고 맡기고 검수하는 운영 루프를 설계했는가 쪽에서 더 크게 갈리고 있었다.
tags:
  - curation
  - ai-trends
  - ai-automation
  - knowledge-management
  - design-automation
  - corner-of-the-corner
created: "2026-06-13"
modified: "2026-06-13"
publish: true
cssclasses:
  - quick-note
---

# 2026-06-13 · 도구 수집보다 운영 루프가 먼저다 · 릴리스 40건

이번에 받은 <strong>「LilysAI 최근 40개 노트 학습팩」</strong>은 겉으로 보면 주제가 꽤 넓다. 에이전트 운영, LLM Wiki, GraphRAG, 로컬 모델, Figma QA, Premiere Pro 자동 편집, HTML 결과물, 카드뉴스 생성, PDF 유틸리티까지 한 묶음에 들어 있다.

그런데 다시 읽으며 가장 크게 남은 건 “요즘 도구가 정말 많다”가 아니었다. 오히려 더 선명했던 건, 이제 차이는 도구 숫자에서 나기보다 <strong>자료를 모으고, 구조화하고, 에이전트에게 맡기고, 사람이 마지막에 검수하는 운영 루프를 얼마나 또렷하게 설계했는가</strong>에서 난다는 점이었다. 이번 40선은 기능 모음보다 작업 운영 방식의 지도가 되어가는 흐름으로 읽혔다.

## 먼저 결론

- 이번 40선의 핵심은 새 기능 경쟁보다 <strong>운영 루프 설계</strong>에 있었다.
- Hermes, Codex, Claude Code, Senior-Mode, RemotePair 자료를 같이 보면 에이전트는 답변기보다 <strong>역할이 나뉜 작업 파트너</strong> 쪽으로 이동하고 있다.
- Obsidian, LLM Wiki, GraphRAG, Ponder 흐름은 자료를 많이 모으는 것보다 <strong>다시 찾고 다시 쓰는 구조</strong>가 더 중요해졌음을 보여준다.
- Gemma, Nanobot, 모바일 로컬 LLM 흐름은 비용 절감보다 <strong>통제 가능성, 오프라인성, 개인 워크플로우 연결</strong>에 더 큰 의미가 있음을 드러낸다.
- Figma QA, Premiere Pro Agent, htmlbook, 카드뉴스 생성 자료는 결과물 초안보다 <strong>수정, 검수, 반복 편집</strong>이 더 큰 활용처가 되고 있음을 확인시킨다.

## 왜 이번 40선이 유독 운영 이야기처럼 읽혔나

이번 자료는 표면적으로는 서로 다른 카테고리처럼 보인다. 어떤 건 개발 도구고, 어떤 건 지식관리이며, 어떤 건 디자인 자동화고, 또 어떤 건 로컬 AI다. 원래라면 산만해질 수도 있는 조합이다.

하지만 자세히 보면 거의 다 같은 질문으로 모인다.

- 자료를 어디에 쌓아야 다음 작업에서 다시 쓸 수 있나
- 어떤 단계까지 에이전트에게 맡겨도 되나
- 사람은 어디서 검수선을 그어야 하나
- 반복 작업은 어떤 단위로 스킬화해야 하나
- 도구 하나보다 흐름 전체를 어떻게 이어야 하나

그래서 이번 40개는 “요즘 이런 것도 나왔다”는 링크 모음보다, <strong>AI와 사람이 같이 일하는 운영 루프가 점점 더 구체화되는 흐름</strong>을 보여주는 아카이브에 가까웠다.

## 이번 묶음에서 가장 크게 보인 네 가지 변화

### 1) 에이전트는 단일 도구보다 역할 분리된 작업면으로 간다

Senior-Mode, Agent Skills, RemotePair, Hermes 원클릭 키트, Claude Fable5 활용, Codex 필수 기능 정리 자료를 한 줄에 세워보면 공통점이 분명하다.

이제 에이전트를 볼 때 중요한 질문은

- 어느 모델이 더 센가
- 기능이 몇 개인가

보다,

- 판단과 실행을 어떻게 나누는가
- 장기 실행을 어떻게 유지하는가
- 스킬과 메모리를 어디에 붙이는가
- 여러 역할을 어떻게 분담하는가

에 더 가깝다.

즉 에이전트 흐름의 무게중심이 답변 품질 자체보다 <strong>역할 분리, 실패 복구, 장기 운영이 가능한 작업면</strong>으로 이동하고 있다.

### 2) 지식관리는 수집보다 재호출 구조가 더 중요해진다

Obsidian LLM Wiki, Karpathy 스타일 LLM Wiki, GraphRAG, Ponder 자료는 방향이 거의 같다.

예전에는 자료를 빨리 요약해주는지가 감탄 포인트였다면, 이제는 그 다음이 더 중요하다.

- 다시 찾을 수 있나
- 연결해서 설명할 수 있나
- 다음 프로젝트에서도 재사용되나
- AI가 읽기 좋은 구조로 남아 있나

이 흐름에서 중요한 건 노트를 쌓는 행위 자체가 아니라, <strong>개인 자료를 작업 기억으로 바꾸는 정보 구조</strong>다. 이번 40선은 그 차이를 꽤 선명하게 보여준다.

### 3) 로컬 모델은 성능 자랑보다 통제 가능한 환경으로 읽어야 한다

Nanobot, Gemma 4 12B, 모바일 로컬 LLM 활용 자료는 모두 “로컬에서도 된다”는 이야기를 한다. 하지만 진짜 포인트는 단순 성능 자랑이 아니다.

이제 질문은 이런 쪽으로 바뀐다.

- 내 장비에서 계속 돌릴 수 있나
- 인터넷 없이도 이어서 쓸 수 있나
- 개인정보를 밖으로 덜 내보낼 수 있나
- 개인 메모리나 사내 자료 흐름과 붙이기 쉬운가

그래서 로컬 AI는 비용 절감 옵션이라기보다 <strong>개인 네트워크 안에서 통제 가능한 운영 환경</strong>으로 읽는 편이 더 맞다.

### 4) 디자인 자동화의 핵심은 생성보다 수정과 QA다

Premiere Pro Agent, Figma MCP + Claude Code QA, htmlbook, Codex 디자인 활용, Claude Cowork, 웹툰·카드뉴스 생성 자료를 같이 보면 디자인 쪽도 흐름이 꽤 분명하다.

AI가 초안을 만드는 일은 이미 흔해졌다. 그런데 실제로 더 오래 남는 건 대개 이쪽이다.

- 수정 요청서를 자동으로 만드는가
- 원본 시안과 결과물 차이를 검수하는가
- 반복 편집을 덜어주는가
- 최종 품질을 체크리스트로 남길 수 있는가

즉 디자인과 콘텐츠 제작에서도 승부처는 “처음부터 다 만들어준다”보다 <strong>수정과 검수의 반복 비용을 얼마나 줄여주느냐</strong>에 있다.

## 그래서 이 40개를 어떻게 읽는 게 좋을까

처음부터 40개를 다 훑기보다, 아래 순서로 읽는 편이 흐름이 더 또렷하다.

### 1단계: 에이전트 운영 자료부터 본다

- Teach Skill
- Senior-Mode
- Agent Skills
- RemotePair
- Hermes 원클릭 키트
- Codex, Claude Code 필수 기능 정리

이 구간은 AI를 답변기가 아니라 <strong>운영해야 하는 작업 파트너</strong>로 보게 만든다.

### 2단계: 지식관리 축으로 넘어간다

- Obsidian LLM Wiki
- Karpathy 스타일 LLM Wiki
- GraphRAG
- Ponder

이 구간에서는 자료 수집보다 <strong>재사용 구조와 검색 가능한 기억 체계</strong>가 더 중요하다는 점이 보인다.

### 3단계: 로컬과 모바일 AI를 운영 기준으로 본다

- Nanobot
- Gemma 4 12B
- 모바일 로컬 LLM 활용

여기서는 모델 자체보다 <strong>어디서, 얼마나 안정적으로, 어떤 통제 아래 돌릴 수 있는가</strong>가 더 중요해진다.

### 4단계: 디자인과 결과물 자동화를 본다

- Premiere Pro Agent
- Figma QA 자동화
- htmlbook
- Codex 디자인 활용
- 카드뉴스 생성

이 구간은 초안 생성보다 <strong>수정, QA, 반복 편집</strong> 쪽에 더 큰 실무 가치가 있음을 보여준다.

## 이번 자료로 바로 떠오르는 활용 아이디어

- 개인 실험: 자료 보관, 에이전트 실행, 사람 검수 단계를 분리한 개인 운영 루프를 먼저 설계해보기
- 수업 설계: 같은 원자료를 링크 모음, Wiki, RAG, 발표자료로 각각 바꾸며 정보 구조 차이를 비교하게 하기
- 팀 실험: 반복 업무를 스킬로 고정하고, 마지막 승인 질문만 사람이 담당하는 검수 체크리스트 만들기
- 디자인 실험: 초안 생성보다 QA 리포트, 수정 요청서, 버전 비교표를 먼저 자동화해보기
- 로컬 AI 실험: 속도, 비용, 개인정보, 오프라인 사용성 기준으로 로컬 모델과 클라우드 모델 역할 분리표 만들기

## 실제로 한 것

1. 40개 자료를 카테고리별로 나열하기보다 에이전트 운영, 지식 재사용, 로컬 통제, 디자인 QA라는 네 축으로 다시 묶었다.
2. 원문에서 강조한 “자료를 모으고, 구조화하고, 맡기고, 검수하는 루프”를 이번 묶음의 핵심 문장으로 끌어올렸다.
3. 도구 이름을 소개하는 방식보다 각 자료가 어떤 운영 병목을 줄이려는지 중심으로 다시 읽었다.
4. 뒤에는 다시 찾아보기 쉽도록 40개 복사용 링크 표를 그대로 남겼다.

## 막혔던 지점

> 이번 40선은 주제가 넓어서, 그대로 옮기면 풍성한 링크 모음은 되지만 한 문장 논지가 흐려질 위험이 컸다.

그래서 이번 글에서는 개별 도구 설명을 늘리기보다, <strong>이번 묶음이 결국 무엇을 말하는가</strong>를 먼저 세우는 쪽이 더 중요했다. 가장 잘 맞는 한 문장은 “도구 수집보다 운영 루프가 먼저다”였다.

## 다음에 바로 쓸 체크리스트

<ul class="note-list">
  <li>학습 큐레이션 글은 자료 수보다 반복해서 나타나는 운영 축부터 먼저 다시 묶는다.</li>
  <li>에이전트 자료는 모델 비교보다 역할 분리, 검증, 실패 복구 구조 관점으로 읽는다.</li>
  <li>Wiki·RAG 자료는 요약 성능보다 재호출과 재사용 구조를 먼저 본다.</li>
  <li>로컬 AI 자료는 데모 성능보다 통제 가능성, 지속 운용성, 개인정보 기준으로 판단한다.</li>
  <li>디자인 자동화 자료는 초안 생성보다 QA, 수정 요청, 버전 비교 자동화에 먼저 붙여본다.</li>
</ul>

## 남겨둘 판단

이번 40선을 다시 묶고 나서 가장 또렷하게 남은 건 결국 이것이었다.

이제 중요한 건 새 도구를 하나 더 아는가가 아니다.
자료를 어디에 쌓고,
어떤 단위로 구조화하고,
어느 단계까지 에이전트에게 맡기고,
사람이 어디서 검수선을 그을지를
반복 가능한 루프로 만들어두는 쪽이 더 오래 남는다.

그래서 지금 흐름을 제대로 읽고 싶다면 도구 이름만 쫓아서는 부족하다. 결국 더 강한 사람은 <strong>도구를 모으는 사람보다 운영 루프를 설계하는 사람</strong>일 가능성이 크다. 이번 40선은 그 방향을 꽤 분명하게 보여준 묶음이었다.

## 복사용 링크 표

| # | 카테고리 | 주제 | 제목 | 원본 링크 | 릴리스 공개 링크 |
| ---: | --- | --- | --- | --- | --- |
| 1 | 웹사이트 | 디자인/콘텐츠 제작 | Premiere Pro Agent: AI Agent가 어도비 프리미어 프로 타임라인을 직접 편집할 수 있도록 돕는 CLI 도구 | [원본](https://github.com/thedalbee/premiere-pro-agent) | [공개 요약](https://lilys.ai/digest/10067755/11707016?s=1&noteVersionId=8253685) |
| 2 | 멀티 자료 | 에이전트/코딩 워크플로우 | 2026-06-12 Teach Skill 심층 분석 - Stateful AI 개인 교사 | [원본](https://share.note.sx/73c7cby6) | [공개 요약](https://lilys.ai/digest/10067294/11706778?s=1&noteVersionId=8253437) |
| 3 | Beomsu Koh \| 고범수 · 유튜브 | 지식관리/RAG | Building an LLM Wiki in Obsidian — A Karpathy-Inspired Agent Knowledge Base | [원본](https://www.youtube.com/watch?v=sQSFeqeLKtU) | [공개 요약](https://lilys.ai/digest/10063416/11701592?s=1&noteVersionId=8248083) |
| 4 | AI 신영선 · 유튜브 | 기타 AI 도구 | “이거 모르면 헤르메스 쓰지 마세요” 99%가 모르고 있는 헤르메스 에이전트의 진실ㅣ코덱스, 클로드코드보다 더 중요한 활용법 | [원본](https://www.youtube.com/watch?v=-PPHdX3837w) | [공개 요약](https://lilys.ai/digest/10063414/11701589?s=1&noteVersionId=8248080) |
| 5 | 필로소피 AI 교육 · 유튜브 | 에이전트/코딩 워크플로우 | Claude Fable5로 나만의 영어 사전 만들기 | [원본](https://www.youtube.com/watch?v=PohQcZ_1-W8) | [공개 요약](https://lilys.ai/digest/10059685/11697138?s=1&noteVersionId=8243397) |
| 6 | 칼퇴연구소┃AI생산성 · 유튜브 | 지식관리/RAG | 옵시디언 LLM Wiki, 아무 자료나 넣으면 안 됩니다 \| LLM Wiki 만들기 전에 꼭 정해야 하는 2가지 | [원본](https://www.youtube.com/watch?v=of7Sr3uOlkA) | [공개 요약](https://lilys.ai/digest/10059642/11697075?s=1&noteVersionId=8243329) |
| 7 | 웹사이트 | 기타 AI 도구 | GEO 벤치마크 유틸리티는 LLM 답변에서 브랜드 가시성을 측정하는 오픈소스 도구이다. | [원본](https://github.com/NomaDamas/geobench) | [공개 요약](https://lilys.ai/digest/10057696/11694759?s=1&noteVersionId=8240936) |
| 8 | 웹사이트 | 에이전트/코딩 워크플로우 | Senior-Mode: Claude를 판단 등의 핵심 업무에 맡기고, 행동은 Codex Cli에 위임 | [원본](https://github.com/NewTurn2017/fable-senior-mode) | [공개 요약](https://lilys.ai/digest/10057268/11694137?s=1&noteVersionId=8240248) |
| 9 | 웹사이트 | 에이전트/코딩 워크플로우 | CLAUDE-FABLE-5 System Prompt | [원본](https://github.com/elder-plinius/CL4R1T4S/blob/main/ANTHROPIC/CLAUDE-FABLE-5.md) | [공개 요약](https://lilys.ai/digest/10057222/11694079?s=1&noteVersionId=8240187) |
| 10 | 웹사이트 | 에이전트/코딩 워크플로우 | Agent Skills: AI 에이전트가 시니어 엔지니어의 모범 사례와 워크플로우를 따르도록 돕는 구조화된 기술 세트 | [원본](https://github.com/addyosmani/agent-skills) | [공개 요약](https://lilys.ai/digest/10057157/11694000?s=1&noteVersionId=8240102) |
| 11 | 웹사이트 | 에이전트/코딩 워크플로우 | RemotePair, macOS에 있는 Claude Code를 계속 실행할 수 있게 한다. | [원본](https://github.com/ghyeongl/remote-pair) | [공개 요약](https://lilys.ai/digest/10055820/11692268?s=1&noteVersionId=8238251) |
| 12 | 웹사이트 | 에이전트/코딩 워크플로우 | Hermes Agent 원클릭 키트, 명령어 입력 없이 더블클릭으로 Hermes 설치, 실행, 메신저 연결까지 끝난다. | [원본](https://github.com/sodam-ai/Hermes-Agent_One-Click_Kit) | [공개 요약](https://lilys.ai/digest/10050941/11685700?s=1&noteVersionId=8231460) |
| 13 | 웹사이트 | 에이전트/코딩 워크플로우 | 대학생 AI 도구 추천 7선 \| ChatGPT·노트·녹음 정리 (2026) | [원본](https://thetawave.ai/ko/blog/ai-tools-for-college-students) | [공개 요약](https://lilys.ai/digest/10050921/11685677?s=1&noteVersionId=8231436) |
| 14 | 웹사이트 | 기타 AI 도구 | 마크다운을 네이버 블로그에 최적화된 HTML로 변환기 | [원본](https://github.com/jjlabsio/md-to-naver-blog) | [공개 요약](https://lilys.ai/digest/10049287/11683674?s=1&noteVersionId=8229368) |
| 15 | 웹사이트 | 에이전트/코딩 워크플로우 | Humanizer KR, 한글 AI 티 제거기 | [원본](https://github.com/epoko77-ai/im-not-ai) | [공개 요약](https://lilys.ai/digest/10041981/11673980?s=1&noteVersionId=8219227) |
| 16 | 웹사이트 | 로컬 모델/모바일 AI | Nanobot, 초경량 개인 AI 에이전트 | [원본](https://github.com/HKUDS/nanobot) | [공개 요약](https://lilys.ai/digest/10041856/11673835?s=1&noteVersionId=8219095) |
| 17 | 웹사이트 | 디자인/콘텐츠 제작 | htmlbook — the bookshelf for everything you and your AI build in HTML | [원본](https://htmlbook.io/) | [공개 요약](https://lilys.ai/digest/10030621/11659671?s=1&noteVersionId=8204374) |
| 18 | WorldofAI · 유튜브 | 로컬 모델/모바일 AI | Gemma 4 12B는 놀라워요! 최고의 로컬 AI 코딩 모델! 강력해요! (완벽 테스트) | [원본](https://www.youtube.com/watch?v=TpEBYINwokA) | [공개 요약](https://lilys.ai/digest/10030593/11659639?s=1&noteVersionId=8204340) |
| 19 | Matt Pocock · 유튜브 | 디자인/콘텐츠 제작 | 코딩할 때 /grill-me를 그만 썼습니다. 대신 이걸 씁니다. | [원본](https://www.youtube.com/watch?v=6BB6exR8Zd8) | [공개 요약](https://lilys.ai/digest/10030590/11659635?s=1&noteVersionId=8204336) |
| 20 | 배움의 달인 · 유튜브 | 지식관리/RAG | LLM Wiki + 로컬 LLM을 아이폰에서? 옵시디언+Tailscale 실전 인사이트 | [원본](https://www.youtube.com/watch?v=Rb_T1i3scfI) | [공개 요약](https://lilys.ai/digest/10024883/11651930?s=1&noteVersionId=8196161) |
| 21 | 웹사이트 | 에이전트/코딩 워크플로우 | CodeGraph, 코드 지식 그래프, 코딩 에이전트를 더 효울적으로 이해하고 탐색하도록 돕는 것 | [원본](https://github.com/colbymchenry/codegraph) | [공개 요약](https://lilys.ai/digest/10023963/11650764?s=1&noteVersionId=8194949) |
| 22 | 웹사이트 | 지식관리/RAG | Matt Pocock Agent Skills | [원본](https://github.com/mattpocock/skills) | [공개 요약](https://lilys.ai/digest/10016751/11641142?s=1&noteVersionId=8184920) |
| 23 | 코드깎는노인 · 유튜브 | 기타 AI 도구 | 역대 가장 강력한 AI 모델, 클로드 미소스 공개 | [원본](https://www.youtube.com/watch?v=wedQA2cVWbc) | [공개 요약](https://lilys.ai/digest/10012512/11635506?s=1&noteVersionId=8179062) |
| 24 | 웹사이트 | 업무 생산성 도구 | Smooth AI - 영어 미팅을 위한 실시간 AI 미팅 비서 | [원본](https://www.trysmooth.ai/ko) | [공개 요약](https://lilys.ai/digest/10012481/11635472?s=1&noteVersionId=8179026) |
| 25 | 유튜브신쌤 · 유튜브 | 기타 AI 도구 | 일 잘하는 사람은 클로드 코워크 이렇게 씁니다 | [원본](https://www.youtube.com/watch?v=0c4N1yOJ0b4) | [공개 요약](https://lilys.ai/digest/10010949/11633361?s=1&noteVersionId=8176813) |
| 26 | 김효율의 AI 개발단 · 멀티 자료 | 디자인/콘텐츠 제작 | 코덱스의 소름돋는 디자인 능력 \| AI 디자인 판을 바꿉니다 | [원본](https://www.youtube.com/watch?v=w7sJHKudLHw) | [공개 요약](https://lilys.ai/digest/10010625/11632987?s=1&noteVersionId=8176407) |
| 27 | 배움의 달인 · 유튜브 | 로컬 모델/모바일 AI | 구글 Gemma 4 12B 엄청나네! \| 모바일로 로컬 LLM 무료 사용하는 대박 꿀팁 대공개! | [원본](https://www.youtube.com/watch?v=Ko5GK2jIWxk) | [공개 요약](https://lilys.ai/digest/10010441/11632626?s=1&noteVersionId=8176027) |
| 28 | 피튜브 · 유튜브 | 디자인/콘텐츠 제작 | 디자이너분들, 디자인 수정 직접하지 마세요! 피그마(figma) MCP+클로드코드(claudecode)로 디자이... | [원본](https://www.youtube.com/watch?v=Qe2A_56bXhs) | [공개 요약](https://lilys.ai/digest/10010347/11632497?s=1&noteVersionId=8175892) |
| 29 | 칼퇴연구소┃AI생산성 · 유튜브 | 지식관리/RAG | 옵시디언 + LLM 이 조합 상위 1%는 이렇게 씁니다 \| 옵시디언 + LLM Wiki로 만드는 나만의 AI 업무 시스템 | [원본](https://www.youtube.com/watch?v=RWDBO_KNPlc) | [공개 요약](https://lilys.ai/digest/10010299/11632434?s=1&noteVersionId=8175828) |
| 30 | 일하는 ai · 유튜브 | 에이전트/코딩 워크플로우 | 헤르메스 스킬 만들기: 내 업무 흐름을 재사용하는 법 | [원본](https://www.youtube.com/watch?v=WVAyfx3e3Mw) | [공개 요약](https://lilys.ai/digest/10003481/11623513?s=1&noteVersionId=8166506) |
| 31 | AI 겸임교수 이종범 · 유튜브 | 디자인/콘텐츠 제작 | 클로드 코워크(Claude Cowork)로 비개발자도 MCP 설치부터 라이브 대시보드까지 한 번에 \| 코딩 몰라도 됩니다 | [원본](https://www.youtube.com/watch?v=cb8O8nbXeQ0) | [공개 요약](https://lilys.ai/digest/10003473/11623500?s=1&noteVersionId=8166491) |
| 32 | 멀티 자료 | 지식관리/RAG | LLM wiki + GraphRAG: AI 시대 개인 지식 관리 및 에이전트 구축 | [원본](https://tofu-llmwiki-manual.manus.space/guidebook.html) | [공개 요약](https://lilys.ai/digest/9991622/11607999?s=1&noteVersionId=8150367) |
| 33 | Jay Choi · 유튜브 | 기타 AI 도구 | 헤르메스 에이전트, 이제 10배 강해졌습니다 | [원본](https://www.youtube.com/watch?v=1hCMX1mvhDQ) | [공개 요약](https://lilys.ai/digest/9976123/11587126?s=1&noteVersionId=8128742) |
| 34 | AI 겸임교수 이종범 · 유튜브 | 지식관리/RAG | 노트북LM 뛰어넘은 'Ponder(폰더)' - 논문 분석, 자료조사, 초안 작성까지 자동화 | [원본](https://www.youtube.com/watch?v=SBJC2B6Jdqk) | [공개 요약](https://lilys.ai/digest/9971382/11581097?s=1&noteVersionId=8122483) |
| 35 | 웹사이트 | 업무 생산성 도구 | [윈도우즈용]KillerPDF, Adobe 구독 없이 PDF 편집 및 관리 가능한 무료 오픈소스 | [원본](https://github.com/SteveTheKiller/KillerPDF) | [공개 요약](https://lilys.ai/digest/9970184/11579460?s=1&noteVersionId=8120759) |
| 36 | 시민개발자 구씨 · 멀티 자료 | 에이전트/코딩 워크플로우 | 대부분 모르는 코덱스 신규 기능, 일하는 방식이 바뀝니다! | [원본](https://www.youtube.com/watch?v=paklphOK9uM) | [공개 요약](https://lilys.ai/digest/9960114/11579319?s=1&noteVersionId=8120614) |
| 37 | 코드팩토리 · 유튜브 | 에이전트/코딩 워크플로우 | 코덱스 18가지 필수 기능 12분 정리 | [원본](https://www.youtube.com/watch?v=86B_oGCkyMs) | [공개 요약](https://lilys.ai/digest/9966476/11574841?s=1&noteVersionId=8115944) |
| 38 | 코드팩토리 · 유튜브 | 에이전트/코딩 워크플로우 | Claude Code 필수 지식 20가지 13분 정리! | [원본](https://www.youtube.com/watch?v=sfCm60LVVuI) | [공개 요약](https://lilys.ai/digest/9966451/11574826?s=1&noteVersionId=8115928) |
| 39 | 편집자P · 유튜브 | 디자인/콘텐츠 제작 | 순수 안티그래비티로 사이트 만들기 + 세팅 꿀팁 + 카파시 스킬 | [원본](https://www.youtube.com/watch?v=UKw4j-Mvq5M) | [공개 요약](https://lilys.ai/digest/9960266/11566965?s=1&noteVersionId=8107736) |
| 40 | AI팩트 · 유튜브 | 디자인/콘텐츠 제작 | 구글이 미쳤다! 웹툰·인스타 카드뉴스 무제한 생성 (무료 도구 2종 배포) | [원본](https://www.youtube.com/watch?v=NwcsjuA4xK4) | [공개 요약](https://lilys.ai/digest/9960223/11566908?s=1&noteVersionId=8107678) |
