---
title: 2026-09-06 · AI 도구는 하나의 작업면으로 모인다 · 릴리스 40건
description: 최근 40개 학습 노트를 다시 묶어보니, 이번 흐름의 핵심은 Codex·Claude·MCP·문서·미디어·오픈소스 도구가 각각의 기능을 넘어 하나의 연결된 작업면으로 수렴하는 데 있었다.
tags:
  - curation
  - ai-trends
  - ai-agents
  - tool-integration
  - open-source
  - corner-of-the-corner
created: "2026-09-06"
modified: "2026-09-06"
publish: true
cssclasses:
  - quick-note
---

# 2026-09-06 · AI 도구는 하나의 작업면으로 모인다 · 릴리스 40건

<section class="release-infographic">
  <figure class="release-infographic__figure">
    <img alt="에이전트 운영, 문서와 공공데이터, 미디어 제작, 오픈소스 작업장이 하나의 중앙 작업면으로 연결되고 세 가지 결과물로 나뉘는 지도형 인포그래픽" src="./2026-09-06-ai-tools-converge-on-one-work-surface-release-40-infographic.png" />
    <figcaption>이번 40선은 도구가 흩어진 생태계로 남기보다, 에이전트·문서·미디어·오픈소스 작업이 하나의 중앙 작업면에서 만나 학습·자동화·공유 결과물로 이어지는 방향을 보여준다.</figcaption>
  </figure>
  <div class="release-infographic__summary">
    <p class="release-infographic__eyebrow">Release 40 Connected Work Surface</p>
    <p class="release-infographic__lead">이번 인포그래픽은 지난 글의 학습 경로형 벽면 보드와 다르게, 네 개의 작업 영역이 중앙의 원형 작업면으로 수렴하는 지도형 구도로 설계했다. 도구 이름을 나열하는 대신 <code>연결</code>, <code>변환</code>, <code>검토</code>, <code>공유</code>가 한 장면 안에서 순환하도록 배치했다.</p>
    <ul class="release-infographic__points">
      <li><strong>네 개의 유입 영역</strong> Codex·Claude 같은 에이전트 운영, HWPX·공공문서, 음성·영상 제작, 오픈소스 커뮤니티가 각각 독립된 작업 영역으로 들어온다.</li>
      <li><strong>중앙 작업면</strong> MCP와 브라우저 연결, 스킬과 CLI, 로컬 환경이 서로 다른 도구를 실제 작업 흐름 안에서 만나게 한다.</li>
      <li><strong>사람의 검토 지점</strong> 자동화가 커질수록 승인·품질 확인·개인정보·비용 판단은 중앙에서 사람이 맡아야 한다.</li>
      <li><strong>세 가지 결과물</strong> 연결된 작업은 학습 가능한 지식, 반복 가능한 자동화, 다시 공유할 수 있는 콘텐츠로 빠져나간다.</li>
    </ul>
  </div>
</section>

이번에 받은 <strong>「최근 AI·기술 동향 학습 큐레이션」</strong>은 도구 목록처럼 시작하지만, 끝까지 훑고 나면 전혀 다른 그림이 남는다. Codex와 Claude Code는 에이전트 운영으로, MCP와 WebMCP는 연결 계층으로, HWPX와 공공문서 도구는 현장 파일 처리로, 음성·영상 도구는 제작 파이프라인으로 이어진다. 여기에 오픈소스 프로젝트와 개발자 커뮤니티가 바닥을 받친다.

그래서 이번 40선을 “새로 나온 도구 40개”로 읽으면 핵심을 놓치기 쉽다. 더 정확한 해석은 <strong>각자 따로 놀던 AI 도구가 하나의 작업면으로 모이고 있다</strong>는 쪽이다. 채팅창에서 답을 받는 데서 끝나는 것이 아니라, 자료를 읽고, 파일을 바꾸고, 브라우저와 로컬 앱을 움직이고, 결과를 검토한 뒤, 다른 사람에게 다시 건네는 흐름이 한 덩어리가 된다.

이번 글은 그 흐름을 네 가지 작업 영역과 하나의 운영 원칙으로 다시 묶어본 기록이다. 마지막 링크 표도 자료를 쌓아두는 창고가 아니라, 어떤 영역에서 시작해 어떤 결과물로 빠져나올지 선택하는 실행판으로 남긴다.

## 먼저 결론

- 이번 40선의 핵심은 특정 모델이나 서비스의 승리가 아니라 <strong>서로 다른 도구를 하나의 작업면에 연결하는 방식</strong>이다.
- 가장 선명한 축은 `에이전트 운영`, `문서·공공데이터`, `미디어 제작`, `오픈소스 작업장` 네 갈래다.
- MCP·브라우저·CLI·스킬은 기능 목록이 아니라, 도구와 결과물 사이를 이어주는 <strong>작업 연결 계층</strong>으로 읽어야 한다.
- 자동화가 넓어질수록 사람은 입력보다 <strong>검토·승인·비용·공유 범위</strong>를 결정하는 자리에 남아야 한다.

## 이번 40선에서 먼저 읽히는 최근 흐름

### 1) 에이전트는 채팅 상대에서 작업면의 조정자로 이동한다

Codex 스킬, codex-host, claude-mem, fable-advisor, Claude SEO, MCP 연동 자료를 함께 보면 공통된 변화가 보인다. 에이전트가 답변을 만들어주는 데서 멈추지 않고, 세션과 스킬을 기억하고, 여러 모델을 조정하고, 브라우저와 외부 시스템까지 연결하는 쪽으로 내려오고 있다.

이때 중요한 건 모델 이름을 더 많이 아는 일이 아니다. 어떤 작업을 맡길지, 어떤 도구를 열어둘지, 중간 결과를 어디에 기록할지, 마지막 승인을 누가 할지를 정하는 일이다. 에이전트는 점점 <strong>작업을 대신하는 기능</strong>보다 <strong>작업을 배치하고 조정하는 운영면</strong>에 가까워진다.

### 2) MCP와 브라우저는 도구를 붙이는 기술에서 작업을 연결하는 표면이 된다

WebMCP와 MCP 관련 자료는 AI가 웹과 외부 시스템을 다루는 방법이 더 표준화될 수 있음을 보여준다. 예전에는 도구마다 별도 연동을 만들었다면, 이제는 에이전트가 사용할 수 있는 기능과 데이터의 경계를 약속된 방식으로 노출하는 방향이다.

이 변화가 중요한 이유는 자동화의 단위가 프롬프트에서 <strong>작업 흐름</strong>으로 바뀌기 때문이다. 검색하고, 파일을 읽고, 변환하고, 결과를 확인하고, 다음 도구로 넘기는 순서가 연결되면 AI는 단순한 생성기가 아니라 실제 업무의 중간 계층이 된다. 대신 권한, 개인정보, 잘못된 클릭을 막는 검수선도 함께 설계해야 한다.

### 3) 문서 자동화의 승부처는 예쁜 요약보다 현장 파일의 재사용이다

한국형 레이아웃 구성, HWP 작업법, HWPX 전환 자료는 문서 자동화가 어디에서 진짜 가치를 만드는지 보여준다. 문장을 잘 쓰는 것만으로는 현장 업무가 끝나지 않는다. 한글 파일의 구조를 읽고, 표와 서식을 보존하고, 공공기관의 형식과 검토 기준을 통과해야 실제로 다시 쓸 수 있다.

이번 묶음에서 문서와 공공 보고서가 따로 떨어져 있지 않은 이유도 여기에 있다. AI가 문서를 이해하는 단계에서 멈추지 않고 <strong>업무 파일을 다음 과정으로 넘길 수 있는 상태</strong>까지 만들어야 한다. HWPX·XML, 레이아웃, 템플릿, 표 처리는 모두 그 연결을 위한 기반이다.

### 4) 미디어 제작은 결과물 하나보다 반복 가능한 파이프라인으로 이동한다

로컬 음성 AI, AirTranslate, 영상 설명 스킬, MoneyPrinterTurbo, video-use, VoiceStudio를 함께 보면 음성·영상 제작의 관심사가 달라졌다는 점이 읽힌다. 이제는 이미지나 영상 하나를 뽑는 순간보다, 음성을 만들고, 전사하고, 번역하고, 자막을 붙이고, 편집하고, 배포하는 순서를 얼마나 안정적으로 되풀이하는지가 더 중요하다.

특히 로컬 실행과 오픈소스 대안은 비용과 개인정보라는 현실적인 판단을 끌어온다. 기능이 많아도 내 환경에서 반복할 수 없다면 작업 자산이 되기 어렵다. 결국 좋은 미디어 도구는 화려한 데모보다 <strong>내가 다시 실행할 수 있는 제작 루프</strong>를 남긴다.

### 5) 오픈소스 커뮤니티는 작업면의 바닥과 출구를 함께 만든다

Xournal++, Concat, Windows Kakao Auto, polish-doc, Upstage CLI, OpenDisplay, DURU, Unlazy, abogen, GenOffice, Paperthin, VoiceStudio, super-terrain, video-use, Paseobility까지 넓게 보면 오픈소스는 하나의 카테고리라기보다 작업면의 여러 부품을 공급하는 생태계다.

필기·영상·문서·색상·모니터·오디오북·지형 편집처럼 분야는 달라도, 공통점은 분명하다. 구독과 특정 플랫폼에만 기대지 않고, 사용자가 자신의 환경에서 직접 돌려보고 조립하고 개선할 수 있는 여지를 준다. AI 시대의 오픈소스는 “무료 대안”을 넘어 <strong>작업 흐름을 내 것으로 가져오는 방법</strong>으로 읽을 필요가 있다.

## 카테고리별로 다시 보면 무엇을 먼저 챙겨야 하나

### 에이전트 운영과 코딩 작업면

Codex 스킬, codex-host, claude-mem, fable-advisor, Claude SEO를 먼저 보면 좋다. 이 그룹은 에이전트를 단발성 답변 도구가 아니라 기억·역할·모델·브라우저를 조정하는 작업 운영 구조로 읽게 한다.

### MCP·브라우저·연결 계층

WebMCP와 MCP 연동 자료는 도구를 더 많이 모으는 법보다, AI가 외부 시스템을 어떤 경계와 규칙으로 다뤄야 하는지 생각하게 한다. 자동화 전에 권한과 검토 지점을 먼저 정할 때 특히 유용하다.

### 문서·공공 보고서·레이아웃

한국형 레이아웃 구성, HWP 작업법, HWPX 전환을 함께 읽으면 문서 자동화의 실제 병목이 보인다. 파일을 요약하는 단계에서 멈추지 않고, 보존·변환·재사용 가능한 결과물로 넘기는지가 기준이다.

### 로컬 음성·번역·영상 제작

VoiceStudio, AirTranslate, 영상 설명 스킬, MoneyPrinterTurbo, video-use를 묶어 보면 콘텐츠 제작 루프를 설계할 수 있다. 비용, 로컬 처리, 자막, 전사, 배포까지 한 번에 보되, 직접 반복 가능한 구간부터 작게 시작하는 편이 좋다.

### 오픈소스와 개인 작업 환경

Xournal++, Concat, OpenDisplay, GenOffice, DURU, Unlazy, abogen 같은 프로젝트는 “내 컴퓨터와 내 자료로 어디까지 작업면을 만들 수 있는가”라는 질문을 던진다. 커뮤니티의 코드를 그대로 믿기보다 유지보수 상태, 권한, 데이터 보관 방식을 확인하고 가져오는 것이 기본이다.

## 마지막 링크 표는 어떻게 읽어야 하나

이번 표는 카테고리별 보관함이 아니라, 작업을 시작하는 위치를 고르는 지도다. 먼저 `에이전트 운영`에서 조정 구조를 보고, `MCP·브라우저`에서 연결 경계를 확인한 뒤, `문서`나 `미디어` 중 실제로 줄이고 싶은 반복 마찰을 골라보면 된다. 마지막에는 오픈소스 프로젝트를 통해 그 흐름을 내 환경에 남길 수 있는지 검토한다.

### 먼저 보면 좋은 링크

- 작업 조정부터 보기: Codex 스킬, codex-host, claude-mem, fable-advisor
- 연결 경계 확인하기: WebMCP, MCP 연동, AirTranslate
- 현장 파일 다루기: 한국형 레이아웃 구성, HWP 작업법, VoiceStudio
- 반복 루프 만들기: video-use, MoneyPrinterTurbo, polish-doc, Unlazy
- 내 환경으로 가져오기: DURU, GenOffice, OpenDisplay, Xournal++

이 순서로 읽으면 “어떤 도구가 제일 좋은가”보다 “내 작업면에서 어디를 먼저 연결해야 하는가”가 더 빨리 보인다.

## 복사용 링크 표

| 카테고리 | 주제 | 제목 | 원본 링크 | 릴리스 공개 링크 |
|---|---|---|---|---|
| OpenAI Codex와 코딩 에이전트 운영 | Codex 스킬 | GitHub - LiamGvchi/gc-minimal-zine-poster: Codex skill for generating quiet minimal zine-style edito | [원본](https://github.com/LiamGvchi/gc-minimal-zine-poster) | [LilysAI 요약](https://lilys.ai/digest/11228827/13238324?s=1&noteVersionId=9839722) |
| OpenAI Codex와 코딩 에이전트 운영 | Codex 호스트 | codex-host/docs/README.ko.md at main · BytePioneer-AI/codex-host · GitHub | [원본](https://github.com/BytePioneer-AI/codex-host) | [LilysAI 요약](https://lilys.ai/digest/11176649/13172369?s=1&noteVersionId=9771816) |
| Claude Code와 에이전트 자동화 | 지속 메모리 | claude-mem/docs/i18n/README.ko.md at main · thedotmack/claude-mem · GitHub | [원본](https://github.com/thedotmack/claude-mem) | [LilysAI 요약](https://lilys.ai/digest/11228685/13238135?s=1&noteVersionId=9839526) |
| Claude Code와 에이전트 자동화 | 모델 오케스트레이션 | GitHub - DannyMac180/fable-advisor: Claude Fable as an orchestrator for Opus, GPT and Grok · GitHub | [원본](https://github.com/DannyMac180/fable-advisor) | [LilysAI 요약](https://lilys.ai/digest/11225780/13234242?s=1&noteVersionId=9835520) |
| Claude Code와 에이전트 자동화 | SEO 자동화 | Claude SEO 분석 도구 | [원본](https://github.com/AgriciDaniel/claude-seo) | [LilysAI 요약](https://lilys.ai/digest/11218747/13225066?s=1&noteVersionId=9826075) |
| Claude Code와 에이전트 자동화 | MCP 입문 | 클로드 코드 쓰면서 MCP 모르면 안 되는 이유 \| API와의 차이부터 구글·카톡 연동까지 | [원본](https://www.youtube.com/watch?v=cskMc7hcdsg) | [LilysAI 요약](https://lilys.ai/digest/11203368/13205766?s=1&noteVersionId=9806210) |
| MCP·브라우저·도구 연결 | WebMCP | MCP만큼 큰 변화가 또 옵니다, 이번엔 WebMCP | [원본](https://www.youtube.com/watch?v=sOLFEc63US4) | [LilysAI 요약](https://lilys.ai/digest/11225818/13234295?s=1&noteVersionId=9835574) |
| 업무 문서와 공공 보고서 자동화 | 레이아웃 | GitHub - worlyung/korean-layout-compositions: 한국형 레이아웃 구성 도감 277종 | [원본](https://github.com/worlyung/korean-layout-compositions) | [LilysAI 요약](https://lilys.ai/digest/11228744/13238207?s=1&noteVersionId=9839600) |
| 업무 문서와 공공 보고서 자동화 | HWPX | 클로드코드 한글파일(HWP) 작업법, MCP 서버 설치부터 공공기관 HWPX 전환까지 | [원본](https://editor870508.tistory.com/entry/클로드코드-한글파일HWP-작업법-MCP-서버-설치부터-공공기관-HWPX-전환까지) | [LilysAI 요약](https://lilys.ai/digest/11197548/13198386?s=1&noteVersionId=9798544) |
| AI 서비스 운영과 제품 전략 | 3D 프리비즈 | GitHub - NomaDamas/CozyClay: Open source previs software in the browser | [원본](https://github.com/NomaDamas/CozyClay) | [LilysAI 요약](https://lilys.ai/digest/11228702/13238153?s=1&noteVersionId=9839545) |
| 로컬 AI와 개인 개발환경 | 로컬 음성 AI | 음성 AI 로컬 설치부터 API 자동화까지 (17GB·7분·크레딧 0원) | [원본](https://www.youtube.com/watch?v=OlE4mpwjiPU) | [LilysAI 요약](https://lilys.ai/digest/11203359/13205752?s=1&noteVersionId=9806196) |
| 콘텐츠 제작·발표·번역 자동화 | 실시간 번역 | GitHub - himomohi/AirTranslate: AirTranslate macOS app · GitHub | [원본](https://github.com/himomohi/AirTranslate) | [LilysAI 요약](https://lilys.ai/digest/11197582/13198434?s=1&noteVersionId=9798593) |
| 플랫폼·OS와 사용자 생산성 | 디자인 스킬 | 클로드 역대급 디자인 스킬 업데이트 /design | [원본](https://www.youtube.com/watch?v=QWMIQFJye-A) | [LilysAI 요약](https://lilys.ai/digest/11175259/13170698?s=1&noteVersionId=9770094) |
| 오픈소스와 개발자 커뮤니티 | 필기 | Xournal++ - Xournal++: 오픈소스 노트 필기 소프트웨어 | [원본](https://xournalpp.github.io/) | [LilysAI 요약](https://lilys.ai/digest/11230745/13240951?s=1&noteVersionId=9842450) |
| 오픈소스와 개발자 커뮤니티 | 영상 편집 | GitHub - jub0t/Concat: Free & Open-Source CapCut replacement. · GitHub | [원본](https://github.com/jub0t/Concat) | [LilysAI 요약](https://lilys.ai/digest/11230734/13240935?s=1&noteVersionId=9842433) |
| 오픈소스와 개발자 커뮤니티 | 카카오톡 백업 | Windows Kakao Auto: 윈도우즈 환경에서 카카오톡 PC 자동 대화 수집 및 백업 도구 | [원본](https://github.com/AidanKR/kakao-auto) | [LilysAI 요약](https://lilys.ai/digest/11228792/13238274?s=1&noteVersionId=9839670) |
| 오픈소스와 개발자 커뮤니티 | 문서 다듬기 | GitHub - albertrim/polish-doc · GitHub | [원본](https://github.com/albertrim/polish-doc) | [LilysAI 요약](https://lilys.ai/digest/11228617/13238052?s=1&noteVersionId=9839439) |
| 오픈소스와 개발자 커뮤니티 | 에이전트 CLI | Upstage Cli | [원본](https://github.com/VectorSophie/upstage-cli) | [LilysAI 요약](https://lilys.ai/digest/11217035/13222758?s=1&noteVersionId=9823691) |
| 오픈소스와 개발자 커뮤니티 | 보조 모니터 | OpenDisplay — Turn your spare Apple devices into second monitors for your Mac | [원본](https://opendisplay.app/) | [LilysAI 요약](https://lilys.ai/digest/11216936/13222647?s=1&noteVersionId=9823576) |
| 오픈소스와 개발자 커뮤니티 | 설명 영상 | 음성 해설 기반의 설명 영상 제작하는 에이전트 스킬 | [원본](https://github.com/Vincentwei1021/video-talkcraft) | [LilysAI 요약](https://lilys.ai/digest/11214583/13219913?s=1&noteVersionId=9820748) |
| 오픈소스와 개발자 커뮤니티 | 로컬 문서 AI | GitHub - leeryong/DURU: DURU — 두루 돕는 AI | [원본](https://github.com/leeryong/DURU) | [LilysAI 요약](https://lilys.ai/digest/11213545?s=1) |
| 오픈소스와 개발자 커뮤니티 | 작업 완료 규율 | Unlazy Skill: 완료 규율 스킬-할 일을 정하고 반드시 그 일을 끝내야 한다. | [원본](https://github.com/Leonxlnx/unlazy) | [LilysAI 요약](https://lilys.ai/digest/11210376/13214428?s=1&noteVersionId=9815107) |
| 오픈소스와 개발자 커뮤니티 | 오디오북 | GitHub - denizsafak/abogen: Generate audiobooks from EPUBs, PDFs and text with synchronized captions | [원본](https://github.com/denizsafak/abogen) | [LilysAI 요약](https://lilys.ai/digest/11205230/13207991?s=1&noteVersionId=9808497) |
| 오픈소스와 개발자 커뮤니티 | 컬러 팔레트 | GitHub - Northstrix/nof-go: A petite color palette generator | [원본](https://github.com/Northstrix/nof-go) | [LilysAI 요약](https://lilys.ai/digest/11202531/13204677?s=1&noteVersionId=9805066) |
| 오픈소스와 개발자 커뮤니티 | 오피스 | GenOffice: MS Office 무료 오픈소스 대안 | [원본](https://github.com/genspark-ai/genoffice) | [LilysAI 요약](https://lilys.ai/digest/11202464/13204597?s=1&noteVersionId=9804979) |
| 오픈소스와 개발자 커뮤니티 | 영상 자동화 | MoneyPrinterTurbo/README-en.md at main · harry0703/MoneyPrinterTurbo · GitHub | [원본](https://github.com/harry0703/MoneyPrinterTurbo) | [LilysAI 요약](https://lilys.ai/digest/11197388/13198183?s=1&noteVersionId=9798335) |
| 오픈소스와 개발자 커뮤니티 | 에이전트 패턴 | AI Design Pattern: AI 에이전트가 효율적으로 문제를 해결하도록 돕는 도구 | [원본](https://github.com/LilMGenius/paperthin) | [LilysAI 요약](https://lilys.ai/digest/11196823/13197501?s=1&noteVersionId=9797631) |
| 오픈소스와 개발자 커뮤니티 | 음성 AI | VoiceStudio: ElevenLabs의 오픈소스 대안 | [원본](https://github.com/debpalash/VoiceStudio) | [LilysAI 요약](https://lilys.ai/digest/11186216/13183969?s=1&noteVersionId=9783743) |
| 오픈소스와 개발자 커뮤니티 | 지형 편집 | GitHub - vibe-stack/super-terrain: mesh terrain editing for threejs · GitHub | [원본](https://github.com/vibe-stack/super-terrain) | [LilysAI 요약](https://lilys.ai/digest/11184535/13181909?s=1&noteVersionId=9781623) |
| 오픈소스와 개발자 커뮤니티 | 영상 편집 에이전트 | GitHub - browser-use/video-use: Edit videos with coding agents · GitHub | [원본](https://github.com/browser-use/video-use) | [LilysAI 요약](https://lilys.ai/digest/11177966/13174002?s=1&noteVersionId=9773505) |
| 오픈소스와 개발자 커뮤니티 | 멀티에이전트 | GitHub - wilgon456/Paseobility · GitHub | [원본](https://github.com/wilgon456/Paseobility) | [LilysAI 요약](https://lilys.ai/digest/11176590/13172297?s=1&noteVersionId=9771741) |
| AI 에이전트와 코딩 워크플로우 | 스킬 디렉터리 | The Agent Skills Directory | [원본](https://www.skills.sh/) | [LilysAI 요약](https://lilys.ai/digest/11228614/13238045?s=1&noteVersionId=9839432) |
| AI 에이전트와 코딩 워크플로우 | 암묵지 자산화 | 암묵지 자산화를 위한 딥트윈 에이전트의 전체 원리와 설계 프로세스 | [원본](https://www.youtube.com/watch?v=I_c8R_PckJ8) | [LilysAI 요약](https://lilys.ai/digest/11175294/13170738?s=1&noteVersionId=9770136) |
| 기타 참고 자료 | 개발 기초 | 70대도 이해시키는 개발 개념 강의는 이게 유일할거에요 | [원본](https://www.youtube.com/watch?v=jW9Pit6ppAo) | [LilysAI 요약](https://lilys.ai/digest/11230775/13240988?s=1&noteVersionId=9842489) |
| 기타 참고 자료 | AI 윤리 | 에이전틱 AI에 필요한 윤리 원칙: 정부의 대한민국 AI윤리원칙 제정 | [원본](https://ai.kisdi.re.kr/aieth/main/contents.do?menuNo=400058) | [LilysAI 요약](https://lilys.ai/digest/11216486/13222092?s=1&noteVersionId=9823009) |
| 기타 참고 자료 | 웹 기술 | 한큐에 설명하는 HTML, CSS, Javascript, HTTPS, NginX, Next.js, Python, FastAPI, PostgreSQL, Docker, K8s | [원본](https://www.youtube.com/watch?v=fx7nNPn98Nk) | [LilysAI 요약](https://lilys.ai/digest/11213613/13218788?s=1&noteVersionId=9819573) |
| 기타 참고 자료 | 캘린더 위젯 | New Features \| Calendar Widget: Modern/Shadcn Style, Date Range Selection, Booked Dates and More | [원본](https://www.youtube.com/watch?v=QwAg3S1W2Tk) | [LilysAI 요약](https://lilys.ai/digest/11203386/13205792?s=1&noteVersionId=9806237) |
| 기타 참고 자료 | 공공데이터 | 보조금24 데이터로 내 혜택만 걸러주는 웹앱 만들어봅시다 \| 공공데이터 API | [원본](https://www.youtube.com/watch?v=a-oG2FJwTz0) | [LilysAI 요약](https://lilys.ai/digest/11203363/13205756?s=1&noteVersionId=9806200) |
| 기타 참고 자료 | 데이터베이스 | 데이터베이스 Supabase, Firebase 왜 쓰는지 아시나요? | [원본](https://www.youtube.com/watch?v=yk7Gg4KYelg) | [LilysAI 요약](https://lilys.ai/digest/11187666/13185772?s=1&noteVersionId=9785583) |
| 기타 참고 자료 | 업무 자동화 | 안티그래비티로 쌀먹하기 | [원본](https://www.youtube.com/watch?v=HNxqccXxSVA) | [LilysAI 요약](https://lilys.ai/digest/11175303/13170749?s=1&noteVersionId=9770147) |

## 용어 정리

| 용어 | 쉬운 설명 | 일상 예시 |
|---|---|---|
| AI 에이전트 | 목표를 받고 여러 단계를 스스로 처리하는 AI 도구입니다. | 여행지를 말하면 항공권, 숙소, 일정 후보를 차례로 알아봐 주는 비서와 비슷합니다. |
| CLI | 마우스 대신 글자 명령어로 프로그램을 실행하고 제어하는 방식입니다. | 음식점 키오스크 버튼을 누르는 대신 직원에게 '김밥 두 줄 포장'이라고 말하는 것에 가깝습니다. |
| MCP | AI가 외부 도구나 데이터 소스와 약속된 방식으로 연결되도록 돕는 통신 규격입니다. | 여러 전자제품을 같은 충전 케이블로 꽂을 수 있게 맞춘 표준 포트처럼 이해하면 쉽습니다. |
| HWPX | 한글 문서의 내용을 XML 기반 구조로 저장하는 문서 형식입니다. | 겉으로는 한글 문서지만 안쪽은 정리된 부품 상자처럼 문장, 표, 서식이 나뉘어 있는 형태입니다. |
| GitHub | 코드와 문서를 저장하고 협업하는 개발자용 온라인 작업 공간입니다. | 여러 사람이 같은 문서함을 보며 수정 이력과 담당 작업을 관리하는 공유 캐비닛과 비슷합니다. |

## 마무리

이번 40개를 한 문장으로 줄이면 이렇다.

> 이제 중요한 것은 AI 도구를 하나 더 아는가가 아니라, 서로 다른 도구를 하나의 작업면에 연결하고 그 결과를 다시 쓸 수 있는 구조로 남기는가에 더 가깝다.

에이전트는 작업을 조정하고, MCP와 브라우저는 바깥 세계와 연결하고, 문서와 미디어 도구는 결과물을 만들고, 오픈소스는 그 작업면을 내 환경으로 가져올 선택지를 넓힌다. 그 사이에서 사람이 해야 할 일은 줄어드는 것이 아니라 더 선명해진다. 무엇을 연결할지, 어디서 멈출지, 무엇을 확인한 뒤 공유할지를 결정하는 일이다.

이번 글의 링크 표도 그 판단을 다시 시작하기 위한 출발점으로 남겨둔다.
