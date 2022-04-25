# F&F Dashboard

Discovery, MLB 브랜드를 보유한 패션기업 입니다. 프로세스팀에서 프론트엔드 개발자로 인턴십을 진행했습니다.

2022.01 - 2022.02

[구현영상](https://www.youtube.com/watch?v=A85Y6BtZaqw) | [Github](https://github.com/Seokho0120/wecode-ojt-fnf-frontend.git) | [Figma](https://www.figma.com/file/8K2hK5wnxGR2xn0fJYR62O/wecode%3A%3AF%26F-Dash) | [회고](https://velog.io/@leesegho/%EC%97%90%ED%94%84%EC%95%A4%EC%97%90%ED%94%84-%ED%9B%84%EA%B8%B0) | [Style Guide](https://www.notion.so/STYLE-GUIDE-901c8c2fe15c4665a6cc5e8821465239) | [Schedule](https://www.notion.so/F-F-Schedule-4389ca3ecb264c1d8261cf3fcc89fd91)

## 인원

프론트엔드 4명 | 백엔드 3명

## Tech Stack

JavaScript(ES6) | React | React Router | Styled-component | Recoil | Rechart.js | Material-ui

## Overview

각기 다른 Coverage의 데이터를 Mix & Match하여 구성하고, **데이터 시각화를 통한 비지니스 인사이트 도출** 미션을 수행했습니다.

VanillanJS로 개발된 사내 직원을 위한 데이터 대시보드를 **React**로 개량하는 프로젝트의 프로토타입을 구현했습니다.

## What did I do

### 카테고리 파트의 마켓 검색량 페이지, 스타일랭킹 파트의 검색 필터 페이지 담당

- Recoil을 사용해 전역 상태 관리를 경험하고, 버튼 클릭 시 API 호출 및 데이터에 맞는 차트와 테이블을 구현했습니다.
- 영문 데이터 키값을 한글로 가공하여 각기 다른 차트 및 테이블에 적용했습니다.

### Button, PageTitle 공통 컴포넌트 구현

- 받아오는 데이터에 따라 페이지의 Title이 무분별하게 반복되는 것을 발견하여, Title 공통 컴포넌트를 구현했습니다.
- 현업에서도 예상하지 못한 재사용이 가능한 파트가 있으면 빠르게 공유하고 효율적인 해결책을 제시해야겠다는 생각을 했습니다.

### 재사용 컴포넌트 관리의 중요성 경험 [(자세한 내용 보러가기)](https://velog.io/@leesegho/FF-Components-%EC%9E%AC%EC%82%AC%EC%9A%A9%EC%97%90-%EB%8C%80%ED%95%9C-%EA%B3%A0%EB%AF%BC%EA%B3%BC-%EA%B2%BD%ED%97%98)

- 작은 단위의 컴포넌트부터 bottom-up 방식으로 개발하였으며, 컴포넌트를 조합하여 재사용성을 높였습니다.
- Button 공통 컴포넌트를 구현했지만, 각자 다른 컬러와 props를 사용하고 props를 다양하게 받다보니 관리 측면에서 어려웠습니다.
- 모든 컴포넌트를 재사용할 수 없다는 것을 배웠고, 적절한 재사용에 관한 고민과 설계의 중요성을 느꼈습니다.

### Recharts(LineChart, ComposedChart, PieChart) & Material-ui(Table) 시각화 라이브러리 활용

- 현업에서 자주 사용되고, 공식 문서 및 커스텀 관련 자료가 많아 Recharts와 MUI를 선택했습니다.

### 스타일 가이드 공유 및 일관성있는 프로젝트 방향 제안 [(자세한 내용 보러가기)](https://www.notion.so/STYLE-GUIDE-901c8c2fe15c4665a6cc5e8821465239)

- 직관적인 레이아웃과 컬러 및 폰트 등 스타일 가이드를 제안해 통일된 디자인을 유지했습니다.

## 구현 결과

카테고리 파트의 **검색 데이터 페이지** 입니다.
데이터 키값을 가공 및 적용하여 각기 다른 차트 및 테이블을 구현했습니다.

![검색량](https://user-images.githubusercontent.com/93597794/159906934-9425f11e-9c79-4600-bcf4-a317a6118f0b.png)

스타일 랭킹 파트의 **조건부 검색 필터 페이지** 입니다.
오른쪽의 조건부 필터 페이지를 맡았습니다. 버튼 클릭 시 조건에 맞는 API호출 및 데이터에 맞는 차트 및 테이블을 구현했습니다.

![스타일랭킹_데이터_조회_레이아웃](https://user-images.githubusercontent.com/93597794/159906948-8dc9e091-35d3-44f1-900e-cd129c2210ed.png)
