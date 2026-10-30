---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

## Scope

`index.html` 한 장: 시작, 문제 5개, 결과. 방문자 모드는 Operate(폰에서 퀴즈를 끝까지 푼다). 코드 주도 빌드.

## Audience and task

교회 성도·청년이 단톡방 링크로 폰에서 혼자 푼다. 할 일: 네 문장 중 성경에 없는 하나를 고르고, 출처를 확인하고, 점수를 공유한다.

## Direction contract

THESIS: 듀오링고 수준으로 다듬은 표준 퀴즈 앱. 크림 종이·금색·성경 이모지의 '성경 지면' 기본값을 버리고, 누구나 바로 아는 퀴즈 조작으로 말씀 감별에만 집중시킨다.

OWN-WORLD: 흰 바탕, 잉크 #111827, 주색 파랑 #3b5bfd. 정답 초록, 오답 빨강은 상태에만 쓴다. Pretendard 한 가족. 2px 테두리에 아래 4px 두께가 있는 눌리는 보기 타일과 버튼, 누르면 2px 내려앉는다. 아이콘은 직접 그린 2.25px 선 SVG.

STORY: 시작 화면의 예시 한 줄로 '성경처럼 들리지만 성경에 없는 문장'이 무엇인지 바로 이해하고, 다섯 문제를 고르고 확인하며 진짜 구절마다 장절을 보고, 결과에서 다섯 문제를 다시 훑은 뒤 공유한다.

FIRST VIEWPORT: 390x844 기준. 위에 워드마크, 큰 제목 "틀린 구절 하나를 찾아라", 설명 두 줄, 예시 타일 하나("하나님은 스스로 돕는 자를 도우시느니라" + 성경에 없어요 표시), 5문제·4지선다·개역개정 사실 한 줄. 주 행동 "시작하기"는 엄지 닿는 하단 고정 바.

FORM: 카테고리 표준(canon), 사용자가 직접 선택. 기준 제품: 듀오링고. 고르기 → 확인하기 → 하단에서 올라오는 초록/빨강 피드백 시트 → 계속하기. seed:7389e53eb335ccaf

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Unresolved

없음.
