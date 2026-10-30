---
name: "말씀일까?"
description: "네 문장 중 성경에 없는 하나를 고르는 5문제 퀴즈. 듀오링고 수준으로 다듬은 표준 퀴즈 앱."
colors:
  bg: "#ffffff"
  ink: "#111827"
  ink-2: "#374151"
  ink-3: "#6b7280"
  line: "#e5e7eb"
  line-2: "#d1d5db"
  wash: "#f3f4f6"
  pri: "#3b5bfd"
  pri-edge: "#2541d8"
  pri-soft: "#eef1ff"
  pri-ink: "#2338c4"
  ok: "#0e8241"
  ok-edge: "#0a6332"
  ok-soft: "#e6f6ec"
  ok-ink: "#0a5a2e"
  "no": "#d42f36"
  no-edge: "#a5222a"
  no-soft: "#fdeced"
  no-ink: "#9c1c24"
typography:
  display:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "clamp(32px, 9vw, 42px)"
    fontWeight: 800
    lineHeight: 1.18
    letterSpacing: "-0.035em"
  score:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "64px"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.04em"
    fontFeature: "tnum"
  headline:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "28px"
    fontWeight: 800
    lineHeight: 1.3
    letterSpacing: "-0.03em"
  title:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "24px"
    fontWeight: 800
    lineHeight: 1.35
    letterSpacing: "-0.03em"
  verdict:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "21px"
    fontWeight: 800
    letterSpacing: "-0.02em"
  subhead:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "18px"
    fontWeight: 800
    letterSpacing: "-0.02em"
  wordmark:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "19px"
    fontWeight: 800
    letterSpacing: "-0.03em"
  option:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "17px"
    fontWeight: 600
    lineHeight: 1.55
    letterSpacing: "-0.01em"
  button:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    letterSpacing: "-0.01em"
  lede:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.65
  body:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  secondary:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "14px"
    fontWeight: 600
  fine:
    fontFamily: "Pretendard Variable, Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.7
rounded:
  tile: "16px"
  control: "12px"
  key: "9px"
  segment: "6px"
spacing:
  segment: "6px"
  stack: "12px"
  inline: "14px"
  pad: "16px"
  gutter: "20px"
  gutter-narrow: "16px"
components:
  button-primary:
    backgroundColor: "{colors.pri}"
    textColor: "{colors.bg}"
    typography: "{typography.button}"
    rounded: "{rounded.tile}"
    padding: "0 20px"
    height: "54px"
  button-primary-disabled:
    backgroundColor: "{colors.line}"
    textColor: "{colors.ink-3}"
  button-ok:
    backgroundColor: "{colors.ok}"
    textColor: "{colors.bg}"
  button-no:
    backgroundColor: "{colors.no}"
    textColor: "{colors.bg}"
  button-ghost:
    backgroundColor: "{colors.bg}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.tile}"
    padding: "0 20px"
    height: "54px"
  button-ghost-hover:
    backgroundColor: "{colors.wash}"
  option-tile:
    backgroundColor: "{colors.bg}"
    textColor: "{colors.ink}"
    typography: "{typography.option}"
    rounded: "{rounded.tile}"
    padding: "14px 16px 13px"
  option-tile-selected:
    backgroundColor: "{colors.pri-soft}"
  option-tile-fake:
    backgroundColor: "{colors.ok-soft}"
  option-tile-miss:
    backgroundColor: "{colors.no-soft}"
  option-tile-rest:
    textColor: "{colors.ink-2}"
  option-key:
    textColor: "{colors.ink-3}"
    rounded: "{rounded.key}"
    size: "30px"
  option-key-selected:
    textColor: "{colors.pri}"
  option-key-fake:
    backgroundColor: "{colors.ok}"
    textColor: "{colors.bg}"
  option-key-miss:
    backgroundColor: "{colors.no}"
    textColor: "{colors.bg}"
  progress-segment:
    backgroundColor: "{colors.line}"
    rounded: "{rounded.segment}"
    height: "10px"
  progress-segment-now:
    backgroundColor: "{colors.pri}"
  progress-segment-ok:
    backgroundColor: "{colors.ok}"
  progress-segment-no:
    backgroundColor: "{colors.no}"
  action-bar:
    backgroundColor: "{colors.bg}"
    padding: "16px 20px"
  feedback-sheet-ok:
    backgroundColor: "{colors.ok-soft}"
    textColor: "{colors.ok-ink}"
    typography: "{typography.secondary}"
    padding: "16px 20px"
  feedback-sheet-no:
    backgroundColor: "{colors.no-soft}"
    textColor: "{colors.no-ink}"
    typography: "{typography.secondary}"
    padding: "16px 20px"
  badge-ok:
    backgroundColor: "{colors.ok}"
    textColor: "{colors.bg}"
    size: "28px"
  badge-no:
    backgroundColor: "{colors.no}"
    textColor: "{colors.bg}"
    size: "28px"
  icon-button:
    textColor: "{colors.ink-3}"
    rounded: "{rounded.control}"
    size: "40px"
  icon-button-hover:
    backgroundColor: "{colors.wash}"
    textColor: "{colors.ink}"
  toast:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.bg}"
    rounded: "{rounded.control}"
    padding: "11px 16px"
---

# Design System: 말씀일까?

## Overview

**Creative North Star: "눌리는 답안지"**

말씀일까?는 누구나 이미 손에 익은 퀴즈 앱의 문법을 그대로 쓴다. 흰 바탕 위에 보기 타일 네 장이 놓이고, 하나를 눌러 고른 뒤 하단 바의 '확인하기'로 채점하면, 그 바가 초록이나 빨강 시트로 바뀌어 올라온다. 낯선 장치가 없어야 사용자의 주의가 '이 문장이 성경에 있었나'라는 한 가지 판단에 온전히 남는다. 듀오링고는 완성도의 기준일 뿐 빌려 올 브랜드가 아니다. 캐릭터, 초록 브랜드색, 전용 서체는 쓰지 않는다.

시스템의 성격은 '눌리는 것'에서 나온다. 보기 타일과 버튼은 아래쪽 테두리가 4px로 두꺼워 바닥에 놓인 판처럼 보이고, 누르면 2px 내려앉는다. 그 밖의 모든 것(제목, 설명, 결과 목록, 피드백 시트)은 평평한 글과 면이다. 두께는 이 두 컴포넌트만의 것이어서, 화면에서 두께가 보이면 그것이 보기이거나 버튼이다.

밀도는 한 손, 폰 세로 화면에 맞춘다. 600px 한 단, 20px 여백, 17px 보기 글자, 엄지가 닿는 하단 고정 바. 색은 절제한다. 파랑은 행동과 현재 위치에, 초록과 빨강은 채점 결과에만 나온다. 크림 종이, 금색, 성경 이모지 같은 '성경 지면' 장식은 의도적으로 버렸다.

**Key Characteristics:**
- 흰 바탕, 거의 검은 잉크, 주색은 파랑 하나
- 초록과 빨강은 채점 상태 전용
- 2px 테두리와 아래 4px 두께의 눌리는 보기 타일·버튼, 누르면 2px 내려앉음
- Pretendard 한 가족, 제목은 모두 800
- 직접 그린 선 아이콘(렌더 굵기 약 2px, 둥근 끝과 이음)
- 주 행동과 채점 피드백은 늘 같은 하단 고정 바에

## Colors

밝은 쿨그레이 중립색 위에 파랑 하나, 그리고 상태 전용 초록과 빨강. 세 색 계열은 모두 기본·edge(눌림 두께)·soft(바탕)·ink(색 바탕 위 글자) 네 단계가 짝을 이룬다.

### Primary
- **선명한 코발트 블루** (#3b5bfd): 주 버튼 채움, 선택한 보기의 테두리와 번호, 진행 막대의 현재 칸, 포커스 링, 워드마크의 물음표와 파비콘. 흰 글자와의 대비 5.12:1.
- **깊은 코발트** (#2541d8): 주 버튼 아래 4px 두께. 버튼 옆면의 그늘 역할만 한다.
- **코발트 안개** (#eef1ff): 선택한 보기 타일의 바탕, 텍스트 선택 영역의 바탕.
- **코발트 잉크** (#2338c4): 옅은 파랑 바탕 위 글자(텍스트 선택 영역의 글자).

### Secondary
상태 전용: 정답, 그리고 '성경에 없는 문장'을 찾아냈다는 표시.
- **판정 초록** (#0e8241): 공개된 정답(가짜) 타일의 테두리와 번호 칸 채움, 맞힌 문제의 진행 칸과 배지, 정답 시트의 버튼. 흰 글자 대비 4.90:1.
- **깊은 초록** (#0a6332): 정답 시트 버튼의 아래 4px 두께.
- **초록 안개** (#e6f6ec): 공개된 정답 타일과 정답 시트의 바탕.
- **초록 잉크** (#0a5a2e): 초록 바탕 위 모든 글자(시트 제목과 설명, 타일의 "성경에 없는 문장"). 초록 안개 위 대비 7.46:1.

### Tertiary
상태 전용: 오답, 그리고 놓친 문제.
- **판정 빨강** (#d42f36): 내가 잘못 고른 타일의 테두리와 번호 칸 채움, 놓친 문제의 진행 칸과 배지, 오답 시트의 버튼. 흰 글자 대비 4.93:1.
- **깊은 빨강** (#a5222a): 오답 시트 버튼의 아래 4px 두께.
- **빨강 안개** (#fdeced): 잘못 고른 타일과 오답 시트의 바탕.
- **빨강 잉크** (#9c1c24): 빨강 바탕 위 모든 글자, 결과 목록의 "내가 고른 문장은 실제 말씀이에요." 강조. 빨강 안개 위 대비 7.06:1.

### Neutral
- **흰 종이** (#ffffff): 페이지, 보기 타일, 하단 바의 바탕. 채운 버튼·배지·토스트 위 글자.
- **먹빛 잉크** (#111827): 제목, 보기 문장, 본문. 토스트의 바탕.
- **진회색** (#374151): 설명 문단, 사실 줄, 채점 뒤 나머지 보기의 문장, 결과 목록의 내가 고른 문장 설명.
- **중간 회색** (#6b7280): 보조 줄, 장절, 문제 번호, 보기 번호, 닫기 아이콘, 고지 글씨, 비활성 버튼 라벨. 흰 바탕 대비 4.83:1로, 글자에 쓰는 가장 옅은 색이다.
- **연한 선** (#e5e7eb): 보기 타일과 번호 칸 테두리, 진행 막대의 빈 칸, 구분선, 하단 바의 2px 윗선, 비활성 버튼 바탕.
- **진한 선** (#d1d5db): 정밀 포인터 hover 시 타일 테두리, 비활성 버튼의 아래 두께, 스크롤바, 사실 줄의 점.
- **옅은 회색 바탕** (#f3f4f6): 아이콘 버튼과 고스트 버튼의 hover 바탕.

### Named Rules
**The State-Only Color Rule.** 초록과 빨강은 채점 결과를 말할 때만 나온다: 공개된 보기 타일, 진행 칸, 피드백 시트, 결과 배지. 장식, 분류, 강조, 링크에는 쓰지 않는다. 시작 화면의 예시 타일도 '정답 공개' 상태를 미리 보여 주는 것이라 이 규칙 안에 있다.

**The One Blue Rule.** 파랑은 행동과 현재 위치(주 버튼, 선택한 보기, 현재 진행 칸, 포커스 링)와 워드마크의 물음표에만 쓴다. 크게 채운 파랑 면은 한 화면에 주 버튼 하나다.

**The Tinted Text Rule.** 색 바탕 위 글자는 회색이 아니라 같은 계열의 ink 단계(ok-ink, no-ink, pri-ink)로 쓴다. 중간 회색(ink-3)은 흰 바탕에서만 쓴다.

## Typography

**Display Font:** Pretendard Variable (with Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Apple SD Gothic Neo, Noto Sans KR, sans-serif)
**Body Font:** Pretendard Variable (같은 가족)

**Character:** 한 가족의 굵기 차이만으로 위계를 만든다. 800의 짧고 단단한 제목과 600의 또렷한 보기 문장이 앱의 목소리를 내고, 400 본문이 해요체 설명을 부드럽게 받친다. 한국어는 어절 단위로 줄을 바꾼다(word-break: keep-all).

### Hierarchy
- **Display** (800, clamp(32px, 9vw, 42px), 1.18, -0.035em): 시작 화면의 큰 제목 한 곳. text-wrap: balance에 더해 줄을 의미 단위로 직접 끊는다.
- **Score** (800, 64px, 1, -0.04em, tabular-nums): 결과 점수 숫자. 뒤의 "/ 5"는 28px 중간 회색, -0.02em.
- **Headline** (800, 28px, 1.3, -0.03em): 결과 제목("훌륭해요, 말씀 탐정!").
- **Title** (800, 24px, 1.35, -0.03em): 문제 질문. 360px 이하에서 22px.
- **Verdict** (800, 21px, -0.02em): 피드백 시트의 판정("정답이에요!", "아쉬워요").
- **Subhead** (800, 18px, -0.02em): 결과 화면의 구역 제목("문제 다시 보기").
- **Wordmark** (800, 19px, -0.03em): "말씀일까?" 워드마크. 물음표만 파랑.
- **Option** (600, 17px, 1.55, -0.01em): 보기 타일의 문장. 360px 이하에서 16px. 화면에서 가장 오래 읽히는 글자다.
- **Button** (800, 17px, -0.01em): 버튼 라벨.
- **Lede** (400, 17px, 1.65): 시작 화면 설명. 결과 설명은 16px에 같은 1.65.
- **Body** (400, 16px, 1.55): 기본 본문. 결과 목록의 가짜 문장은 같은 크기에 600.
- **Secondary** (400, 15px, 1.6): 질문 아래 보조 줄, 피드백 설명(강조는 800). 사실 줄은 600, 문제 번호 "1/5"는 700에 tabular-nums.
- **Label** (600, 14px): 장절 줄. 예시 캡션과 보기 번호는 700(보기 번호는 tabular-nums), 결과 목록 메모는 400에 1.6.
- **Fine** (400, 13px, 1.7): 시작 화면 맨 아래 고지와 저작권 표기.

### Named Rules
**The One Family Rule.** Pretendard 한 가족만 쓴다. 세리프, 손글씨, 모노 같은 둘째 서체를 들이지 않는다. 위계는 크기와 400/600/700/800 굵기로만 만든다.

**The Tightening Rule.** 글이 클수록 자간을 좁힌다: 본문 0, 보기와 버튼 -0.01em, 소제목과 판정 -0.02em, 제목 -0.03em, 시작 제목 -0.035em, 점수 -0.04em. -0.04em이 하한이다.

**The Tabular Count Rule.** 바뀌는 숫자(문제 번호, 보기 번호, 점수)는 tabular-nums로 폭을 고정한다.

## Layout

한 단 구조다. 콘텐츠 폭은 min(600px, 100%), 가운데 정렬, 좌우 여백 20px(360px 이하 16px). 1440px 데스크톱에서도 같은 600px 단이 가운데 놓이고, 하단 바만 화면 폭 전체에 깔리며 안쪽 내용은 다시 600px 단에 맞춘다.

상단 바는 높이 64px. 시작과 결과 화면에는 워드마크, 문제 화면에는 40px 닫기 버튼, 5칸 진행 막대(칸 사이 6px), "1/5" 카운트가 14px 간격으로 놓이고 스크롤해도 위에 붙어 있다(sticky, 흰 바탕).

수직 리듬은 제목 위가 아래보다 넓다. 질문은 위 20px, 아래 4px에 보조 줄, 다시 22px 뒤 보기. 블록 사이는 28~40px(시작 제목 위 28px, 예시 32px, 사실 줄 28px, 고지 40px과 1px 구분선, 결과 목록 36px). 보기 타일 사이 12px, 타일 안 번호와 문장 사이 14px.

채점하면 정답(가짜) 타일을 가장 가까운 위치로 스크롤해 시트 위에 보이게 한다. 320px 폭에서도 정답 타일과 피드백 시트가 함께 보인다.

**The Thumb Bar Rule.** 주 행동은 늘 하단 고정 바에 하나다(결과 화면만 "다시 도전"과 "결과 공유" 두 개가 10px 간격으로 나란히). 채점 피드백도 같은 바가 색을 바꿔 올라온다. 바 높이는 실측해 --bar-h에 쓰고, 본문 아래 여백(--bar-h + 24px), 토스트 위치, scroll-padding이 그 값을 따른다. 바 아래쪽에는 safe-area-inset-bottom을 더한다.

## Elevation & Depth

평평한 시스템이다. 깊이는 그림자가 아니라 두께로 표현한다. 보기 타일과 버튼만 아래쪽 테두리가 4px로 두껍고, 그 두께가 바닥에 놓인 판의 옆면처럼 보인다. 피드백 시트는 그림자 없이 바탕색(초록 안개, 빨강 안개)만으로 화면과 갈리고, 평소의 하단 바는 2px 연한 선 하나로 갈린다.

### Shadow Vocabulary
- **토스트 부유** (`box-shadow: 0 6px 20px rgba(17,24,39,.18)`): 결과 공유 뒤 잠깐 뜨는 토스트 하나. 화면 위에 떠 있는 유일한 요소다.

### Named Rules
**The Press Edge Rule.** 두께는 보기 타일과 버튼 두 컴포넌트의 것이다. 보기 타일과 고스트 버튼은 2px 테두리에 아래 4px, 채운 버튼은 둘레 테두리 없이 아래 4px edge 색 두께만 갖는다. 누르면(:active) translateY(2px), 아래 두께 2px, margin-bottom 2px가 함께 걸려 바닥선은 그대로이고 윗면만 2px 내려앉는다. 주변 배치는 흔들리지 않는다.

**The Single Shadow Rule.** 그림자는 떠 있는 일시적 알림(토스트)에만 쓴다. 타일, 시트, 목록에는 그림자를 주지 않는다.

## Shapes

부드럽지만 동글동글하지는 않은 모서리. 반경은 요소 크기를 따라 줄어든다. 보기 타일과 버튼 16px, 아이콘 버튼·토스트·포커스 링 12px, 보기 번호 칸 9px(30px 정사각형, 2px 테두리), 진행 칸 6px(높이 10px). 판정 배지만 완전한 원(border-radius 50%)으로, 결과 목록 28px, 피드백 시트 34px다.

테두리의 기본 굵기는 2px(타일, 번호 칸, 고스트 버튼, 하단 바 윗선)이고, 1px은 구분선(고지 위, 결과 목록 사이)에만 쓴다.

아이콘은 24 viewBox에 직접 그린 선 SVG다. fill 없음, 둥근 끝과 이음. 렌더 굵기를 약 2px로 맞추기 위해 20~24px 아이콘은 stroke-width 2.25, 15~18px 배지와 번호 칸 안의 작은 체크·엑스는 stroke-width 3을 쓴다.

**The Shrinking Radius Rule.** 반경은 16, 12, 9, 6px 순으로 요소와 함께 작아지고, 원은 판정 배지에만 쓴다. 큰 면에 알약 모양을 쓰지 않는다.

## Components

### Buttons
단단하고 눌리는, 한 줄짜리 행동.
- **Shape:** 16px 모서리, 최소 높이 54px, 폭 가득, 좌우 안쪽 20px. 아이콘이 붙으면 8px 간격.
- **Primary:** 코발트 블루 채움, 흰 17px 800 라벨, 아래 4px 깊은 코발트. "시작하기", "확인하기", "결과 공유".
- **Verdict (ok / no):** 피드백 시트 안의 "계속하기", "결과 보기"는 시트 상태색으로 채운다. 판정 초록과 깊은 초록, 판정 빨강과 깊은 빨강.
- **Ghost:** 흰 바탕, 먹빛 라벨, 2px 연한 선 테두리와 아래 4px. hover에서 옅은 회색 바탕. "다시 도전".
- **Disabled:** 연한 선 바탕, 진한 선 아래 두께, 중간 회색 라벨, not-allowed 커서. 보기를 고르기 전의 "확인하기".
- **Press / Focus:** 누르면 .08s 동안 2px 내려앉는다. 포커스는 3px 코발트 외곽선, 3px 떨어져.
- **Hover:** 채운 버튼의 hover 채움색은 시스템에 정하지 않았다. 흰 라벨 대비 4.5:1을 지키는 값만 쓸 수 있다.

### Option Tile
시스템의 중심 컴포넌트. 고르기, 확인, 공개 세 단계를 한 장이 모두 보여 준다.
- **Structure:** 30px 번호 칸(9px 모서리, 2px 테두리, 14px 700 숫자)과 17px 600 문장. 공개 뒤에는 문장 아래 6px에 장절 줄(14px 600)이 붙는다.
- **Rest:** 흰 바탕, 2px 연한 선 테두리와 아래 4px, 16px 모서리, 안쪽 14px 16px 13px(360px 이하 12px 13px 11px).
- **Hover:** 정밀 포인터에서만. 테두리 진한 선, 바탕은 거의 흰 파랑빛(#fafbff).
- **Pressed:** 2px 내려앉음.
- **Selected:** 코발트 안개 바탕, 코발트 테두리, 번호 칸 테두리와 숫자도 코발트. aria-pressed로 표시한다.
- **Revealed, fake:** 초록 안개 바탕, 판정 초록 테두리, 번호 칸이 초록으로 채워지고 흰 체크, 장절 자리에 "성경에 없는 문장"을 초록 잉크로.
- **Revealed, miss:** 내가 고른 진짜 구절. 빨강 안개 바탕, 판정 빨강 테두리, 번호 칸 빨강 채움과 흰 엑스, 장절 줄 빨강 잉크.
- **Revealed, rest:** 연한 선 테두리, 문장 진회색, 장절 중간 회색.
- **Motion:** 바탕과 테두리 색은 .15s, 눌림은 .08s.
- 시작 화면의 예시 타일은 같은 컴포넌트의 '공개된 정답' 상태를 정적으로 보여 준다.

### Progress Bar
- 5칸 그리드, 칸 사이 6px, 칸 높이 10px, 6px 모서리. 빈 칸 연한 선, 현재 칸 코발트, 지난 문제는 맞힘 초록 / 놓침 빨강. 색 전환 .3s, --ease.
- 결과 화면에서는 같은 막대가 최대 260px 폭으로 점수 아래에 놓이고, 120ms 뒤부터 칸마다 110ms 간격으로 차례로 채워진다.

### Feedback Sheet
하단 바가 그대로 시트가 된다.
- 채점하면 하단 바의 바탕이 초록 안개 또는 빨강 안개로 바뀌고 윗선이 사라지며, .38s 동안 아래에서 올라온다(translateY 40%, 투명도 .4에서 시작, --ease).
- 34px 원형 배지(흰 18px 아이콘)와 21px 800 판정, 그 아래 15px 1.6 설명(강조 800), 맨 아래 상태색 버튼.
- 시트 안 글자는 모두 그 상태의 ink 단계다.

**The Sheet-Not-Modal Rule.** 채점 피드백은 모달이나 팝업이 아니라 하단 바가 색을 바꿔 올라오는 시트다. 문제와 보기는 시트 위에 그대로 보인다.

### Review List
- 결과 화면의 "문제 다시 보기". 32px 배지 열과 본문 열, 12px 간격, 위아래 16px, 항목 사이 1px 연한 선.
- 28px 원형 배지(판정 초록/빨강, 흰 15px 아이콘), 가짜 문장 16px 600, 메모 14px 중간 회색. 놓친 문제는 빨강 잉크 700의 "내가 고른 문장은 실제 말씀이에요."로 시작하고 고른 구절과 장절을 진회색으로 잇는다.

### Navigation
- 높이 64px 상단 바. 시작과 결과 화면은 19px 800 워드마크만 둔다.
- 문제 화면: 40px 닫기 아이콘 버튼(24px 엑스, 중간 회색, 12px 모서리, hover 시 옅은 회색 바탕과 먹빛 아이콘), 진행 막대, 문제 번호. 흰 바탕으로 위에 붙는다.

### Toast
- 먹빛 바탕, 흰 15px 600, 12px 모서리, 안쪽 11px 16px, 하단 바 위 14px. 시스템의 유일한 그림자를 갖는다.
- .3s 동안 아래 8px에서 떠오르고(--ease), 2.4초 뒤 사라진다.

### Browser Surfaces
- 텍스트 선택은 코발트 안개 바탕에 코발트 잉크 글자, 포커스 링은 3px 코발트에 3px 간격, 스크롤바는 진한 선, theme-color는 흰색, 탭 하이라이트는 투명.

## Do's and Don'ts

### Do:
- **Do** 보기 타일과 버튼에 아래 4px 두께를 주고, 누르면 translateY(2px)와 두께 2px로 바닥선을 고정한 채 윗면만 내려앉힌다.
- **Do** 초록과 빨강은 채점 결과(공개된 타일, 진행 칸, 피드백 시트, 결과 배지)에만 쓴다.
- **Do** 색 바탕 위 글자는 같은 계열의 ink 단계(ok-ink, no-ink, pri-ink)로 쓴다.
- **Do** 진짜 구절이 공개되면 언제나 장절 줄(14px 600)을 붙인다.
- **Do** 채운 버튼의 흰 라벨은 hover를 포함한 모든 상태에서 대비 4.5:1 이상을 지킨다.
- **Do** 아이콘은 24 viewBox에 직접 그린 선 SVG로, 둥근 끝과 이음, 렌더 굵기 약 2px(20~24px 아이콘 stroke-width 2.25, 15~18px 칸 안 아이콘 3)로 그린다.
- **Do** 주 행동과 채점 피드백은 하단 고정 바 하나에 두고, 바 높이(--bar-h)를 실측해 본문 여백과 맞춘다.
- **Do** prefers-reduced-motion에서는 모든 애니메이션과 전환을 끈다.

### Don't:
- **Don't** 크림 종이, 금색, 성경 이모지 같은 '성경 지면' 장식을 들이지 않는다.
- **Don't** 듀오링고의 캐릭터, 초록 브랜드색, 전용 서체를 빌리지 않는다.
- **Don't** 눌림 깊이를 box-shadow로 흉내 내지 않는다. 두께는 테두리여야 누를 때 접힌다.
- **Don't** 보기 타일과 버튼이 아닌 컨테이너(결과 목록, 설명 상자, 시트)에 아래 두께를 빌려 주지 않는다.
- **Don't** 중간 회색(ink-3)을 색 바탕 위 글자로 쓰지 않는다.
- **Don't** Pretendard 밖의 서체를 더하지 않는다.
- **Don't** 유니코드 기호나 이모지를 아이콘 대신 쓰지 않는다.
- **Don't** 제목 위에 키커나 아이브로 라벨을 얹지 않는다. 시작 화면 예시 타일 위의 캡션은 그림 설명이지, 제목을 꾸미는 패턴이 아니다.
