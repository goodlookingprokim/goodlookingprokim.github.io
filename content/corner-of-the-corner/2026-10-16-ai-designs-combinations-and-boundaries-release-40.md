---
title: "2026-10-16 · AI는 도구보다 조합과 경계를 설계한다 · 릴리스 40건"
description: "Grok Bot, Herdr, Baton, 로컬 개발환경, 제작 스킬, REA·ARTEX·MiroFish를 함께 읽으며 AI가 팀·도구·작업환경으로 넓어질 때 필요한 조합과 검증의 경계를 정리했다."
tags:
  - curation
  - ai-trends
  - ai-agents
  - ai-governance
  - local-ai
  - ai-education
  - corner-of-the-corner
created: "2026-10-16"
modified: "2026-10-16"
publish: true
cssclasses:
  - quick-note
---

# 2026-10-16 · AI는 도구보다 조합과 경계를 설계한다 · 릴리스 40건

## 먼저 결론

- 이번 40건의 공통점은 AI가 답변창을 넘어 **팀·개발환경·메일·문서·시뮬레이션·보안 검증**으로 넓어지고 있다는 점입니다.
- 중요한 것은 도구를 많이 붙이는 일이 아니라, 과업마다 어떤 모델과 도구를 조합할지, 그리고 사람의 승인·비용 한도·되돌리기·권한 규칙을 어디에 둘지 정하는 일입니다.
- 제작 스킬과 디자인 가이드는 AI 출력의 품질을 높이지만, 결과물을 그대로 믿게 만드는 장치가 아니라 반복 가능한 기준과 검수 절차를 만드는 장치로 읽어야 합니다.
- 로컬 AI와 독립적인 작업환경은 개인정보·비용·연속성의 선택지를 넓혀 줍니다. 대신 설치 가능 여부만이 아니라 백업, 호환성, 성능, 라이선스까지 함께 봐야 합니다.
- REA·ARTEX·MiroFish처럼 분석·침투 테스트·시뮬레이션을 다루는 자료는 가능성보다 허가 범위와 실증 조건을 먼저 확인하게 합니다.

이번 글은 2026년 10월 16일 최신순으로 모은 40개 노트를 다시 읽은 정리입니다. 원본 주소는 현재 확인된 것만 연결했고, 확인되지 않은 항목에 임의의 주소나 공개 요약 링크를 만들지 않았습니다. 따라서 이 글의 링크 표는 릴리스 공개 링크 목록이 아니라, 확인 가능한 원본을 다시 찾아갈 수 있는 목록입니다.

## 읽는 방법

- 각 항목은 LilysAI 노트의 첫 요약과 본문을 바탕으로 핵심을 줄였습니다.
- `원본: 확인되지 않음` 항목은 원본 페이지와 동일성을 확인하지 못했으므로 원본으로 간주하지 않았습니다.
- 이번 글에는 공개 요약 링크를 임의로 만들지 않고, 현재 확인 가능한 원본 주소만 연결했습니다.

## 이번 묶음을 한 문장으로 읽기

- **에이전트가 답변을 넘어 업무를 이어받는다.** Grok Bot, Herdr, Argo, Baton, Claude Code Mods와 마케팅 에이전트 자료가 팀 구성·도구 연결·이메일 처리·검토 흐름으로 확장되는 모습을 보여준다. 다음 실험은 PR 승인, 비용 한도, 되돌리기처럼 사람이 통제할 지점을 먼저 설계하는 것이다.
- **제작 비용은 작업별 모델 조합으로 낮춘다.** Gemini 평가, GPT 이미지 API, 디오라마 제작 사례는 속도·품질·비용의 균형을 비교한다. 한 모델에 모두 맡기기보다 코딩·이미지·판단 과업을 나눠 동일한 기준으로 측정할 수 있다.
- **개발환경은 로컬과 연결형 도구 사이에서 넓어진다.** Linux에서 iOS 빌드, Apple Silicon 로컬 학습, Windows 가상화, NEO와 이음오피스가 기기 선택지를 넓힌다. 이때 설치 가능 여부뿐 아니라 백업·호환성·개인정보 처리를 확인해야 한다.
- **AI 출력의 품질을 가이드와 시각화로 다듬는다.** Taste, Anatomy, Bookforge, Excalidraw, Transitions.dev는 결과물을 더 일관되고 이해하기 쉽게 만드는 반복 가능한 기준을 제공한다.
- **리버스 엔지니어링과 시뮬레이션은 검증·책임 범위를 함께 묻는다.** REA와 ARTEX는 분석 능력을, GenIA와 MiroFish는 입력 정렬·가상 시뮬레이션을 다룬다. 가능성 주장과 실증 결과를 구분하고 허가·저작권·안전 경계를 지켜야 한다.
- **아이디어 씨앗:** 교사 업무 자동화에서 역할별 에이전트가 자료 조사·초안·검수를 나누되, 개인정보는 로컬 문서 도구에 남기고, Supabase RLS로 사용자별 자료 접근을 시험하는 작은 파일럿을 설계할 수 있다.

## OpenAI Codex와 코딩 에이전트 운영

### 10. AI CLI AUTO Manager

Codex·Claude Code 등 코딩 CLI의 설치·업데이트·디스크 사용량을 관리하고, 업데이트 위험과 불필요한 파일을 다루는 도구다. 변경 전후와 복구 경로를 확인하며 써야 한다.

- 주제: AI CLI AUTO Manager
- 원본: 확인되지 않음

## Claude Code와 에이전트 자동화

### 6. Claude Code 용 Antigravity 플러그인

Claude Code가 Antigravity CLI의 Gemini를 협업 하위 에이전트로 실행하도록 연결한다. 역할 분담과 모델 라우팅으로 비용과 교차 검증을 조절하는 접근이다.

- 주제: Claude Code 용 Antigravity 플러그인
- 원본: [원본](https://github.com/yuting0624/antigravity-for-claude-code)

### 24. Anatomy Skill

Anatomy는 기술 개념을 인터랙티브한 아이소메트릭 3D 피규어로 설명하는 Claude Code 스킬이다. 시각적 설명이 개념 이해에 주는 이득과 구현 부담을 비교해 볼 수 있다.

- 주제: Anatomy Skill
- 원본: 확인되지 않음

### 25. "마케팅의 판도가 바뀐다" 클로드 코드로 기획부터 집행까지 에이전틱하게 끝내는 법 | 빌더 조쉬 김승권 대표 | 맠해팅 EP.11

기획·리서치·카피라이팅에 역할별 에이전트를 배치해 마케팅 파이프라인을 구성한다. 자동화가 전략 판단을 대신하지 않도록 사람 검토 지점을 남기는 것이 핵심이다.

- 주제: "마케팅의 판도가 바뀐다" 클로드 코드로 기획부터 집행까지 에이전틱하게 끝내는 법 | 빌더 조쉬 김승권 대표 | 맠해팅 EP.11
- 원본: [원본](https://www.youtube.com/watch?v=w4nNR3olvow)

### 35. 클로드 코드 Mods, 실제 예시로 처음부터 끝까지

Claude Code Mods는 훅·이벤트로 작업 과정에 개입해 화면과 동작을 하는 작은 프로그램이다. 위험 명령 차단, 상태판 등 활용과 권한 승인 경계를 구분한다.

- 주제: 클로드 코드 Mods, 실제 예시로 처음부터 끝까지
- 원본: [원본](https://www.youtube.com/watch?v=N-djs9BCIyE)

## Hermes와 개인 에이전트 런타임

### 37. 클로드 코드 앱·코덱스 앱·헤르메스, 이제 플러그인 하나로 연결됩니다 (baton)

Baton은 Claude·Codex·Hermes 사이의 작업 전달과 협업을 돕는 플러그인으로 소개된다. 앱 간 연결에서 권한·실행 환경·전달 결과를 추적하는 방법이 관건이다.

- 주제: 클로드 코드 앱·코덱스 앱·헤르메스, 이제 플러그인 하나로 연결됩니다 (baton)
- 원본: 확인되지 않음

## MCP, 브라우저, 도구 연결

### 27. 요즘 대세인 supabase를 제대로 쓰기 위해 바이브코더가 반드시 알아야 할 supabase 꿀팁 4가지

Supabase에서 브라우저가 DB와 스토리지에 직접 연결될 수 있으므로 RLS 정책을 표와 파일에 일관되게 적용해야 한다. 개발 편의보다 사용자별 권한과 테스트가 먼저다.

- 주제: 요즘 대세인 supabase를 제대로 쓰기 위해 바이브코더가 반드시 알아야 할 supabase 꿀팁 4가지
- 원본: [원본](https://www.youtube.com/watch?v=15cFKxlaQzo)

### 28. 모빈(Mobbin) MCP 하나로 리서치·기획·제안서까지 다 나옵니다. (실전: 온보딩 사용자 경험 기획하기)

Mobbin의 실제 앱 화면을 MCP로 검색·비교해 온보딩 패턴을 조사하고 제안서로 엮는 흐름이다. 빠른 조사보다 원본 화면과 맥락을 근거로 남기는 점이 중요하다.

- 주제: 모빈(Mobbin) MCP 하나로 리서치·기획·제안서까지 다 나옵니다. (실전: 온보딩 사용자 경험 기획하기)
- 원본: [원본](https://www.youtube.com/watch?v=3W8hJr3DUzI)

## 업무 문서와 공공 보고서 자동화

### 2. 신비한 건축 사전 따라하기: 건축 디오라마 영상 실험실

이미지 생성과 코드 애니메이션을 결합해 조명·그래프·한글 주석이 들어간 건축 디오라마 영상을 제작한다. 은 1분당 약 800원이라는 저비용 경로를 소개한다.

- 주제: 신비한 건축 사전 따라하기: 건축 디오라마 영상 실험실
- 원본: [원본](https://funnellabs-diorama-lab.vercel.app/#skills)

### 7. 이음오피스: 한글부터 PDF까지, 한 창에서 여는 무료 오피스

한글·워드·엑셀·PDF 등을 한 앱에서 열고 편집하는 무료 오피스다. 문서는 로컬에서 다루고, AI는 표 채우기나 문장 다듬기처럼 필요한 작업에 선택적으로 사용하며 비용 발생도 통제한다.

- 주제: 이음오피스: 한글부터 PDF까지, 한 창에서 여는 무료 오피스
- 원본: [원본](https://ieumoffice.vercel.app/)

## AI 서비스 운영과 제품 전략

### 11. [시즌 4] 게임 코드는 Opus 5.5로, 이미지 제작만 GPT를 시키면? 파워 요금 절약! GPT API 사용 + 게임 제작 가이드

게임 로직은 코딩 모델에 맡기고 이미지 생성은 GPT API 종량제로 분리해 구독 비용을 낮추는 제작 흐름을 설명한다. 실제 비용은 이미지 수·모델·사용량으로 다시 계산해야 한다.

- 주제: [시즌 4] 게임 코드는 Opus 5.5로, 이미지 제작만 GPT를 시키면? 파워 요금 절약! GPT API 사용 + 게임 제작 가이드
- 원본: [원본](https://www.youtube.com/watch?v=mT7XSJRPKvA)

### 26. 복잡한 기능 싹 뺀, 오직 글쓰기에만 집중하는 작가 전용 워드프로세서 NEO.

NEO는 복잡한 편집 기능과 온라인 계정·구독을 덜어내고 글쓰기 자체에 집중하는 로컬 워드프로세서다. 단순함과 내보내기·백업 기능을 함께 평가할 수 있다.

- 주제: 복잡한 기능 싹 뺀, 오직 글쓰기에만 집중하는 작가 전용 워드프로세서 NEO.
- 원본: [원본](https://www.youtube.com/watch?v=68zimAoOTcM)

### 29. Grok Bot 개발 워크플로｜AI 팀 구성부터 PR 검증까지

Grok Bot 팀이 코딩·도구 연동·PR 검증을 장시간 처리하는 운영 흐름을 설명한다. 자율성보다 명확한 역할, 검토 가능한 변경, 중단·복구 규칙이 신뢰성을 좌우한다.

- 주제: Grok Bot 개발 워크플로｜AI 팀 구성부터 PR 검증까지
- 원본: [원본](https://www.youtube.com/watch?v=t9dRQVVZRyM)

### 30. 맥북에 윈도우 깔아서 같이 쓰는 방법🍎 구독없이 무료로도 가능합니다

UTM과 Windows 11 ARM 설치 미디어로 Mac에서 가상 Windows 환경을 구성한다. 호환성·성능·라이선스와 저장 공간을 확인해야 한다.

- 주제: 맥북에 윈도우 깔아서 같이 쓰는 방법🍎 구독없이 무료로도 가능합니다
- 원본: [원본](https://www.youtube.com/watch?v=Ud_22gwjQYE)

## 로컬 AI와 개인 개발환경

### 18. GitHub - scasella/nanochat-mlx: Train your own ChatGPT on Apple Silicon — MLX port of nanochat · Git

nanochat-mlx는 Apple Silicon에서 데이터 준비부터 토크나이저, 학습, 미세 조정, 채팅까지 실행하는 개인 실험용 파이프라인이다. 로컬 메모리와 학습 시간 한계를 고려해야 한다.

- 주제: GitHub - scasella/nanochat-mlx: Train your own ChatGPT on Apple Silicon — MLX po
- 원본: 확인되지 않음

### 21. FilmCraft: 프리미어 프로 오픈 소스 대안 도구

FilmCraft는 Rust 기반의 오픈소스 영상 편집 도구로 macOS·Windows·Linux·웹을 대상으로 한다. 소개 문서의 기능 설명과 실제로 안정된 편집·내보내기 기능을 구분해 보아야 한다.

- 주제: FilmCraft: 프리미어 프로 오픈 소스 대안 도구
- 원본: 확인되지 않음

### 22. Insomnia: macOS 메뉴바-맥 덮개를 닫아도 깨어있는 상태 만들기

Insomnia는 시간 제한, 덮개 닫힘, 디스플레이·앱·오디오 상태를 조절해 Mac을 깨어 있게 한다. 발열·환기와 배터리 영향을 고려해 필요한 시간만 사용해야 한다.

- 주제: Insomnia: macOS 메뉴바-맥 덮개를 닫아도 깨어있는 상태 만들기
- 원본: 확인되지 않음

### 31. 10월10일 줌미팅 세미나(코너속의 코너-Grok Bot, 쓱님의 앱 소개)

세미나는 GitPark의 저장소 주차장 방식과 Grok Bot·AI 에이전트 사례를 소개한다. 여러 프로젝트를 온라인에 보관하고 필요한 것만 로컬에 두는 개발환경 아이디어가 중심이다.

- 주제: 10월10일 줌미팅 세미나(코너속의 코너-Grok Bot, 쓱님의 앱 소개)
- 원본: [원본](https://www.youtube.com/watch?v=2zbDdLuLFLE)

## 콘텐츠 제작, 발표, 번역 자동화

### 13. Exploring Herdr Plugins: Multi-Agent Orchestration and Workflows

Herdr Projects는 코디네이터와 여러 작업 에이전트의 병렬 처리를, Dagger는 워크플로 진행 상황의 시각화를 지원한다. 역할·상태·의존성을 나누는 오케스트레이션 사례다.

- 주제: Exploring Herdr Plugins: Multi-Agent Orchestration and Workflows
- 원본: [원본](https://www.youtube.com/watch?v=82S8fmes9T0)

## 플랫폼·OS와 사용자 생산성

### 8. Omarchy Linux를 통해 iPhone App 개발: Flutter iOS 앱 빌드

Omarchy Linux에서 SwiftUI·Flutter iOS 앱을 빌드하고 iPhone에 배포하는 개발 환경을 소개한다. Xcode나 macOS에 대한 의존을 줄이는 접근이지만 실제 서명·배포 제약은 별도 확인이 필요하다.

- 주제: Omarchy Linux를 통해 iPhone App 개발: Flutter iOS 앱 빌드
- 원본: [원본](https://github.com/joshuaswarren/omarchy-apple-dev)

### 32. PiDurableKit: 아이폰에서 에이전트를 구축하도록 돕는 Swift 라이브러리

PiDurableKit은 대화·모델 응답·도구 호출 상태를 저장해 앱 종료 뒤에도 작업을 이어가는 Apple 플랫폼용 에이전트다. 복구 가능한 상태와 도구 실행 기록이 핵심이다.

- 주제: PiDurableKit: 아이폰에서 에이전트를 구축하도록 돕는 Swift 라이브러리
- 원본: 확인되지 않음

## 오픈소스와 개발자 커뮤니티

### 14. GitHub 오픈소스 1위 REA 직접 검증해봤습니다 | Reverse Engineer Anything

REA는 AI 에이전트가 바이너리 앱의 동작을 조사하도록 분석 도구와 절차를 묶는다. 최신 모델이 자체 분석하는 경우와 비교해 REA의 실질적인 안내·자동화 이점을 평가한다.

- 주제: GitHub 오픈소스 1위 REA 직접 검증해봤습니다 | Reverse Engineer Anything
- 원본: [원본](https://www.youtube.com/watch?v=rwCDPZP_Zk4)

### 15. 소프트웨어는 끝났다는 REA 직접 검증해봤습니다 | GitHub 트렌딩 1위

REA 유무를 비교한 실험과 DX-Ball·Notion 사례를 통해 리버스 엔지니어링의 가능성과 한계를 살핀다. 기술 데모와 저작권·서비스 약관을 분리해 해석해야 한다.

- 주제: 소프트웨어는 끝났다는 REA 직접 검증해봤습니다 | GitHub 트렌딩 1위
- 원본: [원본](https://www.youtube.com/watch?v=rwCDPZP_Zk4)

## AI 에이전트와 코딩 워크플로우

### 12. 빅테크 AI 에이전트 3종 vs 한국인 1인 개발 앱 | 에이전트를 팀으로 쓰는 법

Argo는 역할별 에이전트와 사람을 한 협업 공간에서 연결하는 팀형 앱으로 소개된다. AI를 개인 비서에서 회의·업무를 함께하는 팀원으로 하는 사례다.

- 주제: 빅테크 AI 에이전트 3종 vs 한국인 1인 개발 앱 | 에이전트를 팀으로 쓰는 법
- 원본: [원본](https://www.youtube.com/watch?v=MwhVh7yzC_k)

### 33. 그록봇 AI 에이전트가 전용 이메일을? | Gmail 자동 포워딩 이용해서 완벽한 나만의 AI 비서 만들기!

Grok Bot 전용 이메일로 전달 대상을 선별해 개인 메일함을 보호하고 업무 맥락을 전달한다. 자동 전달은 허용된 메일만 보내도록 필터와 테스트 절차를 함께 설계해야 한다.

- 주제: 그록봇 AI 에이전트가 전용 이메일을? | Gmail 자동 포워딩 이용해서 완벽한 나만의 AI 비서 만들기!
- 원본: [원본](https://www.youtube.com/watch?v=Vrf5gjwPhqA)

### 34. Transitions.dev: 재사용 가능한 CSS 트랜지션을 모아놓은 라이브러리

Transitions.dev는 복사 가능한 CSS 전환 예제를 모으고 CLI·에이전트 스킬·Refine 도구로 개발 흐름에 연결한다. 예제를 실제 프로젝트의 접근성·성능 기준에 맞게 조정해야 한다.

- 주제: Transitions.dev: 재사용 가능한 CSS 트랜지션을 모아놓은 라이브러리
- 원본: 확인되지 않음

### 36. MiroFish: 가상으로 시뮬레이션 해서 서비스 사용을 예측

MiroFish는 현실 자료로 디지털 세계를 구성하고 다수 에이전트의 상호작용을 시뮬레이션해 미래 시나리오를 탐색한다. 결과는 예측의 확정값이 아니라 가정에 민감한 시뮬레이션으로 읽어야 한다.

- 주제: MiroFish: 가상으로 시뮬레이션 해서 서비스 사용을 예측
- 원본: 확인되지 않음

### 40. ARTEX: 에이전트가 자율적으로 침투 테스트를 수행하는 시스템, 방어자가 AI 공격의 작동 원리를 이해하고 탐지 및 차단 역량을 기르도록 돕는 데 목적이 있음

ARTEX 한국어판은 멀티 에이전트 기반 침투 테스트 시스템을 방어자의 이해·탐지 훈련에 연결한다. 실제 사용은 명시적으로 허가된 격리 실습 환경에 한정해야 한다.

- 주제: ARTEX: 에이전트가 자율적으로 침투 테스트를 수행하는 시스템, 방어자가 AI 공격의 작동 원리를 이해하고 탐지 및 차단 역량을 기르도록 돕는
- 원본: 확인되지 않음

## 기타 참고 자료

### 1. Organizing my life with Grok Bot

Grok Bot으로 일정, 건강 활동, X 북마크, 일기를 묶어 매일 아침 개인화된 종이 브리핑을 인쇄하면 디지털 기기 사용을 줄이고 오프라인에서 하루를 계획할 수 있다.

- 주제: Organizing my life with Grok Bot
- 원본: [원본](https://www.youtube.com/watch?v=zRNY93MtwFs)

### 3. [시즌 4] Gemini 4 아르곤 마이아파(?)

Gemini 4 아르곤은 토큰 효율과 속도에서 장점이 있지만 복잡한 시각 표현과 의도 파악이 약하다는 평가다. 비용 효율이 중요한 단순 작업과 창의적 작업을 나눠 시험할 필요가 있다.

- 주제: [시즌 4] Gemini 4 아르곤 마이아파(?)
- 원본: [원본](https://www.youtube.com/watch?v=gOChDHa0s3k)

### 4. Taste Skill: 디자인을 다듬고 싶을 때 필요한 스킬

Taste-Skill은 AI가 만든 프런트엔드의 간격·애니메이션·시각 품질을 다듬는 디자인 지침 모음이다. 디자인 기준과 수정 방향을 재사용 가능한 스킬로 제공한다.

- 주제: Taste Skill: 디자인을 다듬고 싶을 때 필요한 스킬
- 원본: 확인되지 않음

### 5. Jev에 대해 쉽게 설명

Jev는 문장 생성보다 빠른 분류와 결정을 목표로 하는 System One 모델로 소개된다. 낮은 지연 시간과 비용은 자동화에 유용할 수 있지만, 성능·정확도 주장은 독립 검증이 필요하다.

- 주제: Jev에 대해 쉽게 설명
- 원본: [원본](https://yozm.wishket.com/magazine/detail/3989/?data=rWJMMfLmOq4cCV%2FziGcLPyb3uYyX8rdFRTJiMIy1yoc%3D)

### 9. Play Store adding ‘personal library’ to access your vibe-coded apps

Google Play의 개인 라이브러리는 AI Studio 등으로 만든 개인 앱을 한곳에서 관리하고 여러 기기에 설치·복원하도록 돕는 기능으로 소개된다.

- 주제: Play Store adding ‘personal library’ to access your vibe-coded apps
- 원본: [원본](https://9to5google.com/2026/10/13/google-play-vibe-coded/)

### 16. Bookforge: 전자책 PDF 자동생성 스킬

원고나 한 줄 주제로 표지·목차·본문을 갖춘 전자책 PDF를 만든다. 스타일 팩과 조판 규칙, 밀도·레이아웃 품질 게이트를 두어 산출물 검수를 자동화한다.

- 주제: Bookforge: 전자책 PDF 자동생성 스킬
- 원본: 확인되지 않음

### 17. REA 깃허브 스타 16만 개 | 소스 없는 앱을 AI가 뜯어보는 도구 | VibeCoding 365

REA는 소스 없는 프로그램을 AI가 질문 중심으로 분석하도록 돕는 도구다. 별 수는 관심 지표일 뿐 실제 사용성과 신뢰성의 증거로 보지 말아야 한다.

- 주제: REA 깃허브 스타 16만 개 | 소스 없는 앱을 AI가 뜯어보는 도구 | VibeCoding 365
- 원본: 확인되지 않음

### 19. New Note

본문은 18번 nanochat-mlx 노트와 사실상 동일하다. 목록 제목은 New Note로 남아 있으므로 원본 제목과 중복 여부를 정리할 필요가 있다.

- 주제: New Note
- 원본: 확인되지 않음

### 20. (Jev)CCTV 판단 실습

CCTV 상태 판단을 다루는 Jupyter Notebook 소개 노트다. 실제 영상 판단 과제를 만들 때는 허가된 영상과 개인정보 보호 기준을 먼저 정해야 한다.

- 주제: (Jev)CCTV 판단 실습
- 원본: 확인되지 않음

### 23. GenIA: Generative Reconstruction with Test-Time Input Alignment

GenIA는 단일·다중 이미지와 영상에서 3D를 재구성하고, 테스트 시점의 기하·광학 제약으로 입력에 정렬한다. 재학습 없이 얻는 품질과 실패 사례를 함께 살펴볼 연구 자료다.

- 주제: GenIA: Generative Reconstruction with Test-Time Input Alignment
- 원본: 확인되지 않음

### 38. 자연어로 Excalidraw Diagram 생성

Excalidraw Diagram Skill은 자연어 요청으로 주장과 코드 조각을 담은 다이어그램을 만들고, 시각 검사로 배치 문제를 수정한다. 그림의 정확성과 근거를 최종 확인하는 과정이 필요하다.

- 주제: 자연어로 Excalidraw Diagram 생성
- 원본: 확인되지 않음

### 39. Reverse Engineering 도구

REA는 바이너리와 앱의 런타임을 분석해 기능과 동작 원리를 이해하도록 돕는다. 재구현에 앞서 소유권·약관·저작권·허가 범위를 확인해야 한다.

- 주제: Reverse Engineering 도구
- 원본: 확인되지 않음

## 원본 링크 모음

| 카테고리 | 주제 | 제목 | 원본 링크 |
|---|---|---|---|
| OpenAI Codex와 코딩 에이전트 운영 | AI CLI AUTO Manager | AI CLI AUTO Manager | 확인되지 않음 |
| Claude Code와 에이전트 자동화 | Claude Code 용 Antigravity 플러그인 | Claude Code 용 Antigravity 플러그인 | [원본](https://github.com/yuting0624/antigravity-for-claude-code) |
| Claude Code와 에이전트 자동화 | Anatomy Skill | Anatomy Skill | 확인되지 않음 |
| Claude Code와 에이전트 자동화 | "마케팅의 판도가 바뀐다" 클로드 코드로 기획부터 집행까지 에이전틱하게 끝내는 법 \| 빌더 조쉬 김승권 대표 \| 맠해팅 EP.11 | "마케팅의 판도가 바뀐다" 클로드 코드로 기획부터 집행까지 에이전틱하게 끝내는 법 \| 빌더 조쉬 김승권 대표 \| 맠해팅 EP.11 | [원본](https://www.youtube.com/watch?v=w4nNR3olvow) |
| Claude Code와 에이전트 자동화 | 클로드 코드 Mods, 실제 예시로 처음부터 끝까지 | 클로드 코드 Mods, 실제 예시로 처음부터 끝까지 | [원본](https://www.youtube.com/watch?v=N-djs9BCIyE) |
| Hermes와 개인 에이전트 런타임 | 클로드 코드 앱·코덱스 앱·헤르메스, 이제 플러그인 하나로 연결됩니다 (baton) | 클로드 코드 앱·코덱스 앱·헤르메스, 이제 플러그인 하나로 연결됩니다 (baton) | 확인되지 않음 |
| MCP, 브라우저, 도구 연결 | 요즘 대세인 supabase를 제대로 쓰기 위해 바이브코더가 반드시 알아야 할 supabase 꿀팁 4가지 | 요즘 대세인 supabase를 제대로 쓰기 위해 바이브코더가 반드시 알아야 할 supabase 꿀팁 4가지 | [원본](https://www.youtube.com/watch?v=15cFKxlaQzo) |
| MCP, 브라우저, 도구 연결 | 모빈(Mobbin) MCP 하나로 리서치·기획·제안서까지 다 나옵니다. (실전: 온보딩 사용자 경험 기획하기) | 모빈(Mobbin) MCP 하나로 리서치·기획·제안서까지 다 나옵니다. (실전: 온보딩 사용자 경험 기획하기) | [원본](https://www.youtube.com/watch?v=3W8hJr3DUzI) |
| 업무 문서와 공공 보고서 자동화 | 신비한 건축 사전 따라하기: 건축 디오라마 영상 실험실 | 신비한 건축 사전 따라하기: 건축 디오라마 영상 실험실 | [원본](https://funnellabs-diorama-lab.vercel.app/#skills) |
| 업무 문서와 공공 보고서 자동화 | 이음오피스: 한글부터 PDF까지, 한 창에서 여는 무료 오피스 | 이음오피스: 한글부터 PDF까지, 한 창에서 여는 무료 오피스 | [원본](https://ieumoffice.vercel.app/) |
| AI 서비스 운영과 제품 전략 | [시즌 4] 게임 코드는 Opus 5.5로, 이미지 제작만 GPT를 시키면? 파워 요금 절약! GPT API 사용 + 게임 제작 가이드 | [시즌 4] 게임 코드는 Opus 5.5로, 이미지 제작만 GPT를 시키면? 파워 요금 절약! GPT API 사용 + 게임 제작 가이드 | [원본](https://www.youtube.com/watch?v=mT7XSJRPKvA) |
| AI 서비스 운영과 제품 전략 | 복잡한 기능 싹 뺀, 오직 글쓰기에만 집중하는 작가 전용 워드프로세서 NEO. | 복잡한 기능 싹 뺀, 오직 글쓰기에만 집중하는 작가 전용 워드프로세서 NEO. | [원본](https://www.youtube.com/watch?v=68zimAoOTcM) |
| AI 서비스 운영과 제품 전략 | Grok Bot 개발 워크플로｜AI 팀 구성부터 PR 검증까지 | Grok Bot 개발 워크플로｜AI 팀 구성부터 PR 검증까지 | [원본](https://www.youtube.com/watch?v=t9dRQVVZRyM) |
| AI 서비스 운영과 제품 전략 | 맥북에 윈도우 깔아서 같이 쓰는 방법🍎 구독없이 무료로도 가능합니다 | 맥북에 윈도우 깔아서 같이 쓰는 방법🍎 구독없이 무료로도 가능합니다 | [원본](https://www.youtube.com/watch?v=Ud_22gwjQYE) |
| 로컬 AI와 개인 개발환경 | GitHub - scasella/nanochat-mlx: Train your own ChatGPT on Apple Silicon — MLX po | GitHub - scasella/nanochat-mlx: Train your own ChatGPT on Apple Silicon — MLX port of nanochat · Git | 확인되지 않음 |
| 로컬 AI와 개인 개발환경 | FilmCraft: 프리미어 프로 오픈 소스 대안 도구 | FilmCraft: 프리미어 프로 오픈 소스 대안 도구 | 확인되지 않음 |
| 로컬 AI와 개인 개발환경 | Insomnia: macOS 메뉴바-맥 덮개를 닫아도 깨어있는 상태 만들기 | Insomnia: macOS 메뉴바-맥 덮개를 닫아도 깨어있는 상태 만들기 | 확인되지 않음 |
| 로컬 AI와 개인 개발환경 | 10월10일 줌미팅 세미나(코너속의 코너-Grok Bot, 쓱님의 앱 소개) | 10월10일 줌미팅 세미나(코너속의 코너-Grok Bot, 쓱님의 앱 소개) | [원본](https://www.youtube.com/watch?v=2zbDdLuLFLE) |
| 콘텐츠 제작, 발표, 번역 자동화 | Exploring Herdr Plugins: Multi-Agent Orchestration and Workflows | Exploring Herdr Plugins: Multi-Agent Orchestration and Workflows | [원본](https://www.youtube.com/watch?v=82S8fmes9T0) |
| 플랫폼·OS와 사용자 생산성 | Omarchy Linux를 통해 iPhone App 개발: Flutter iOS 앱 빌드 | Omarchy Linux를 통해 iPhone App 개발: Flutter iOS 앱 빌드 | [원본](https://github.com/joshuaswarren/omarchy-apple-dev) |
| 플랫폼·OS와 사용자 생산성 | PiDurableKit: 아이폰에서 에이전트를 구축하도록 돕는 Swift 라이브러리 | PiDurableKit: 아이폰에서 에이전트를 구축하도록 돕는 Swift 라이브러리 | 확인되지 않음 |
| 오픈소스와 개발자 커뮤니티 | GitHub 오픈소스 1위 REA 직접 검증해봤습니다 \| Reverse Engineer Anything | GitHub 오픈소스 1위 REA 직접 검증해봤습니다 \| Reverse Engineer Anything | [원본](https://www.youtube.com/watch?v=rwCDPZP_Zk4) |
| 오픈소스와 개발자 커뮤니티 | 소프트웨어는 끝났다는 REA 직접 검증해봤습니다 \| GitHub 트렌딩 1위 | 소프트웨어는 끝났다는 REA 직접 검증해봤습니다 \| GitHub 트렌딩 1위 | [원본](https://www.youtube.com/watch?v=rwCDPZP_Zk4) |
| AI 에이전트와 코딩 워크플로우 | 빅테크 AI 에이전트 3종 vs 한국인 1인 개발 앱 \| 에이전트를 팀으로 쓰는 법 | 빅테크 AI 에이전트 3종 vs 한국인 1인 개발 앱 \| 에이전트를 팀으로 쓰는 법 | [원본](https://www.youtube.com/watch?v=MwhVh7yzC_k) |
| AI 에이전트와 코딩 워크플로우 | 그록봇 AI 에이전트가 전용 이메일을? \| Gmail 자동 포워딩 이용해서 완벽한 나만의 AI 비서 만들기! | 그록봇 AI 에이전트가 전용 이메일을? \| Gmail 자동 포워딩 이용해서 완벽한 나만의 AI 비서 만들기! | [원본](https://www.youtube.com/watch?v=Vrf5gjwPhqA) |
| AI 에이전트와 코딩 워크플로우 | Transitions.dev: 재사용 가능한 CSS 트랜지션을 모아놓은 라이브러리 | Transitions.dev: 재사용 가능한 CSS 트랜지션을 모아놓은 라이브러리 | 확인되지 않음 |
| AI 에이전트와 코딩 워크플로우 | MiroFish: 가상으로 시뮬레이션 해서 서비스 사용을 예측 | MiroFish: 가상으로 시뮬레이션 해서 서비스 사용을 예측 | 확인되지 않음 |
| AI 에이전트와 코딩 워크플로우 | ARTEX: 에이전트가 자율적으로 침투 테스트를 수행하는 시스템, 방어자가 AI 공격의 작동 원리를 이해하고 탐지 및 차단 역량을 기르도록 돕는 | ARTEX: 에이전트가 자율적으로 침투 테스트를 수행하는 시스템, 방어자가 AI 공격의 작동 원리를 이해하고 탐지 및 차단 역량을 기르도록 돕는 데 목적이 있음 | 확인되지 않음 |
| 기타 참고 자료 | Organizing my life with Grok Bot | Organizing my life with Grok Bot | [원본](https://www.youtube.com/watch?v=zRNY93MtwFs) |
| 기타 참고 자료 | [시즌 4] Gemini 4 아르곤 마이아파(?) | [시즌 4] Gemini 4 아르곤 마이아파(?) | [원본](https://www.youtube.com/watch?v=gOChDHa0s3k) |
| 기타 참고 자료 | Taste Skill: 디자인을 다듬고 싶을 때 필요한 스킬 | Taste Skill: 디자인을 다듬고 싶을 때 필요한 스킬 | 확인되지 않음 |
| 기타 참고 자료 | Jev에 대해 쉽게 설명 | Jev에 대해 쉽게 설명 | [원본](https://yozm.wishket.com/magazine/detail/3989/?data=rWJMMfLmOq4cCV%2FziGcLPyb3uYyX8rdFRTJiMIy1yoc%3D) |
| 기타 참고 자료 | Play Store adding ‘personal library’ to access your vibe-coded apps | Play Store adding ‘personal library’ to access your vibe-coded apps | [원본](https://9to5google.com/2026/10/13/google-play-vibe-coded/) |
| 기타 참고 자료 | Bookforge: 전자책 PDF 자동생성 스킬 | Bookforge: 전자책 PDF 자동생성 스킬 | 확인되지 않음 |
| 기타 참고 자료 | REA 깃허브 스타 16만 개 \| 소스 없는 앱을 AI가 뜯어보는 도구 \| VibeCoding 365 | REA 깃허브 스타 16만 개 \| 소스 없는 앱을 AI가 뜯어보는 도구 \| VibeCoding 365 | 확인되지 않음 |
| 기타 참고 자료 | New Note | New Note | 확인되지 않음 |
| 기타 참고 자료 | (Jev)CCTV 판단 실습 | (Jev)CCTV 판단 실습 | 확인되지 않음 |
| 기타 참고 자료 | GenIA: Generative Reconstruction with Test-Time Input Alignment | GenIA: Generative Reconstruction with Test-Time Input Alignment | 확인되지 않음 |
| 기타 참고 자료 | 자연어로 Excalidraw Diagram 생성 | 자연어로 Excalidraw Diagram 생성 | 확인되지 않음 |
| 기타 참고 자료 | Reverse Engineering 도구 | Reverse Engineering 도구 | 확인되지 않음 |

## 용어 정리

| 용어 | 쉬운 설명 | 일상 예시 |
|---|---|---|
| AI 에이전트 | 목표를 받고 여러 단계를 스스로 처리하는 AI 도구입니다. | 여행지를 말하면 항공권, 숙소, 일정 후보를 차례로 알아봐 주는 비서와 비슷합니다. |
| 멀티 에이전트 | 여러 AI 에이전트가 역할을 나눠 동시에 또는 순서대로 일하는 방식입니다. | 한 명은 자료 조사, 한 명은 글쓰기, 한 명은 검수를 맡는 작은 프로젝트 팀처럼 보면 됩니다. |
| CLI | 마우스 대신 글자 명령어로 프로그램을 실행하고 제어하는 방식입니다. | 음식점 키오스크 버튼을 누르는 대신 직원에게 '김밥 두 줄 포장'이라고 말하는 것에 가깝습니다. |
| MCP | AI가 외부 도구나 데이터 소스와 약속된 방식으로 연결되도록 돕는 통신 규격입니다. | 여러 전자제품을 같은 충전 케이블로 꽂을 수 있게 맞춘 표준 포트처럼 이해하면 쉽습니다. |
| RAG | AI가 답을 만들기 전에 관련 문서나 자료를 먼저 찾아 참고하게 하는 방식입니다. | 시험 답안을 쓰기 전에 책장에서 관련 페이지를 찾아 펴 놓고 쓰는 것과 비슷합니다. |
| HWPX | 한글 문서의 내용을 XML 기반 구조로 저장하는 문서 형식입니다. | 겉으로는 한글 문서지만 안쪽은 정리된 부품 상자처럼 문장, 표, 서식이 나뉘어 있는 형태입니다. |
| 컨텍스트 | AI가 답변할 때 참고하는 대화 내용, 문서, 코드 같은 작업 기억입니다. | 회의 중 칠판에 적어 둔 결정사항과 참고 메모를 보며 다음 말을 이어가는 상황입니다. |
| 오케스트레이션 | 여러 도구나 에이전트의 실행 순서와 역할을 조율하는 일입니다. | 주방장이 여러 요리사에게 재료 손질, 굽기, 플레이팅을 나눠 지시하는 장면과 같습니다. |
| LLM | 글을 이해하고 생성하도록 학습된 대규모 언어 AI 모델입니다. | 수많은 책과 문서를 읽고 문맥에 맞춰 답을 만들어 내는 아주 큰 자동완성 엔진처럼 볼 수 있습니다. |
| GitHub | 코드와 문서를 저장하고 협업하는 개발자용 온라인 작업 공간입니다. | 여러 사람이 같은 문서함을 보며 수정 이력과 담당 작업을 관리하는 공유 캐비닛과 비슷합니다. |
| 바이브코딩 | AI와 대화하며 빠르게 방향을 잡고 코드를 만들어 가는 개발 방식입니다. | 요리책을 한 줄씩 따라가기보다 셰프에게 원하는 맛을 말하며 즉석에서 레시피를 조정하는 방식입니다. |
