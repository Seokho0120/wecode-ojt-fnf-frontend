# F&F Dashboard

프로세스팀 프론트엔드 개발 인턴

2022.01 - 2022.02

[구현영상](https://www.youtube.com/watch?v=A85Y6BtZaqw) | [Github](https://github.com/Seokho0120/wecode-ojt-fnf-frontend.git) | [Figma](https://www.figma.com/file/8K2hK5wnxGR2xn0fJYR62O/wecode%3A%3AF%26F-Dash) | [회고](https://velog.io/@leesegho/%EC%97%90%ED%94%84%EC%95%A4%EC%97%90%ED%94%84-%ED%9B%84%EA%B8%B0) | [Style Guide](https://www.notion.so/STYLE-GUIDE-901c8c2fe15c4665a6cc5e8821465239) | [Schedule](https://www.notion.so/F-F-Schedule-4389ca3ecb264c1d8261cf3fcc89fd91)

## 인원

프론트엔드 4명 | 백엔드 3명

## Tech Stack

JavaScript(ES6) | React | React Router | Styled-component | Axios | Recoil | Rechart.js | Material-ui | React-custom-scrollbars

## Overview

각기 다른 Coverage의 데이터를 Mix & Match하여 구성하고, **데이터 시각화를 통한 비지니스 인사이트 도출** 미션을 수행했습니다.

VanillanJS로 개발된 사내 직원을 위한 데이터 대시보드를 **React**로 개량하는 프로젝트의 프로토타입을 구현했습니다.

## What did I do

✔️ **경험 및 배운점**

- **[Components 재사용에 대한 고민과 경험](https://www.notion.so/F-F-Dashboard-3124e755a1104bdb8ecb891435a6818c)**
- 유지보수와 가독성을 중점으로 **Components 사용**
- 전달받는 데이터에 따라 보여지는 **기능과 페이지를 기준**으로 컴포넌트 분리
- 전역 상태관리 라이브러리 **Recoil의 기본 사용법** 학습 및 **atom, useRecoilValue, useRecoilState** 경험
- 차트 라이브러리 **Recharts**의 **LineChart, ComposedChart, PieChart** 사용 및 스타일링 커스텀
- **MUI의 Table** 컴포넌트 사용 및 데이터 시각화

✔️ **역할 및 구현**

- Category 페이지의 **검색 데이터 페이지** 구현
- Style Ranking 페이지의 **조건부 검색 필터 페이지** 구현
- 재사용 가능한 **Button, PageTitle 공통 컴포넌트** 구현
- **[스타일 가이드](https://www.notion.so/STYLE-GUIDE-901c8c2fe15c4665a6cc5e8821465239)** 공유 및 일관성있는 **프로젝트 방향 제시**(디자인 및 레이아웃, 컬러 등)

## 구현 결과
![검색량](https://user-images.githubusercontent.com/93597794/159906934-9425f11e-9c79-4600-bcf4-a317a6118f0b.png)

카테고리 파트의 **검색 데이터 페이지** 입니다.
데이터 키값을 가공 및 적용하여 각기 다른 차트 및 테이블을 구현했습니다.

![스타일랭킹_데이터_조회_레이아웃](https://user-images.githubusercontent.com/93597794/159906948-8dc9e091-35d3-44f1-900e-cd129c2210ed.png)

스타일 랭킹 파트의 **조건부 검색 필터 페이지** 입니다.
오른쪽의 조건부 필터 페이지를 맡았습니다. 버튼 클릭 시 조건에 맞는 API호출 및 데이터에 맞는 차트 및 테이블을 구현했습니다.
