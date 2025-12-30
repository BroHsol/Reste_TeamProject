# [Reste]
> [모던한 스타일의 소파 쇼핑몰]

## 1. 프로젝트 소개
* **설명:** 기획부터 디자인, 개발까지 직접 참여하였으며, **Mock Data(JSON)**를 활용해 실제 커머스 로직을 구현한 SPA 쇼핑몰 프로젝트입니다.
* **진행 기간:** 2025.12.17 ~ 2025.12.29 (13일)
* **개발 인원:** FrontEnd 5인 (Team Project)
* **배포 링크:** [바로가기 URL 클릭]

## 2. 사용 기술 스택 (Tech Stack)
* **Language:** JavaScript (ES6+)
* **Framework:** React.js
* **Styling:** SCSS
* **Data Handling:** Custom Mock Data (JSON)
* **Design & Tool:** **Figma**, Git, GitHub, Blender, Photoshop, Illustrator

## 3. 기획 및 디자인 (Planning & Design)
* **Tool:** Figma
* **Concept:** 사용자 직관성을 고려한 UI/UX 설계 및 와이어프레임 제작

## 4. 디렉토리 구조
```text
src
├── assets        # 이미지, 폰트 및 JSON 데이터
├── components    # 재사용 가능한 공통 UI 컴포넌트
├── pages         # 라우팅 페이지 (Main, Detail, Cart...)
├── section       # 라우팅 페이지의 하위 섹션 페이지 (Main-Video, Best-Item...)
└── layout        # Header, Footer 등 레이아웃

## 5. 담당 역할

[기획 및 디자인]
* Figma를 활용한 전체 와이어프레임 및 프로토타입 제작
* 공통 컬러 팔레트 및 컴포넌트 스타일 가이드 정립

[개발: nav 기능]
* Header, Footer 제작
* Header 안 nav 를 숨겨놨다가 메뉴 버튼을 hover 했을 때, nav가 상단에서 하단으로 내려옴
* nav에 마우스 Enter 상황일 때 nav 를 사용하고, nav에 마우스 Leave 시 nav가 보이지 않게 처리
* 그 외 대부분의 페이지 scss를 수정

## 6. 주요 기능
상품 데이터 처리: JSON 데이터를 활용한 비동기 통신 모방
장바구니 관리: 배열을 활용한 장바구니 추가/수정/삭제
필터링: 배열 메서드를 활용한 카테고리/가격순 정렬

## 7. 트러블 슈팅
문제 1. 간략한 내용
상황: 와이어 프레임 제작 후 디자인 페이지 제작 중에 팀원들 각자 생각하고 있던 기능이 각각 달라서 제작이 더뎌졌다.
해결: 현 상황을 모두에게 알리고 짧은 재회의를 통해 기준을 명확하게 잡았다.
과정: 각자 본인이 생각했던 기능을 차례로 얘기하고, 모두가 마음에 드는 절충안을 뽑아 새롭게 디자인했다.

## 8. 실행 화면
