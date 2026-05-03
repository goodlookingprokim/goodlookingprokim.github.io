# OpenClaw Blog Publishing Template

이 Quartz 템플릿은 OpenClaw가 평범한 마크다운 노트를 푸시해도 읽기 편한 정보 설계형 테크 블로그로 바로 보이도록 구성되어 있습니다.

## 글 작성 규칙

- 새 글은 `content/templates/openclaw-blog-post.md`의 frontmatter와 섹션 순서를 우선 사용합니다.
- 카테고리 인덱스는 `content/templates/openclaw-folder-index.md`를 사용합니다.
- `cssclasses`는 글 성격에 맞게 `field-note`, `playbook`, `quick-note`, `reference` 중 하나를 고릅니다.
- `description`은 OG 이미지와 검색 미리보기에 들어가므로 한 문장으로 완결합니다.
- 태그는 소문자 영문 kebab-case를 기본으로 쓰고, 3-6개 안에 멈춥니다.
- 강한 장식보다 문제, 결론, 절차, 재사용 가능한 판단이 먼저 보이게 씁니다.

## 권장 글 구조

1. 문제나 상황을 한 문단으로 설명합니다.
2. `먼저 결론`에서 재사용 가능한 판단을 먼저 둡니다.
3. 실제 설정, 명령, 오류, 해결 순서를 숨기지 않습니다.
4. 마지막에는 다음 작업에서 바로 쓸 체크리스트나 판단을 남깁니다.

## 지원되는 강조 블록

- `<div class="note-hero">...</div>`: 홈 또는 글 상단의 차분한 소개 블록
- `<p class="kicker">...</p>`: 섹션 성격을 짧게 표시하는 보조 라벨
- `<div class="topic-grid">`와 `<a class="topic-card">`: 3개 내외의 관련 글/주제 카드
- `<ul class="note-list">`: 체크리스트나 재사용 항목
- `<div class="action-row">`: 주요 이동 버튼 묶음

기존 글에 남아 있는 `.neo-*` 클래스는 호환 스타일로 계속 렌더링되지만, 새 글에는 위 클래스명을 사용합니다.

`content/templates`는 Quartz `ignorePatterns`에 포함되어 배포되지 않습니다.
