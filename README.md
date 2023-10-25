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

### 경쟁사 마켓 검색량 데이터 시각화

- 기존 데이터 값을 수정하면 안되는 기업 방침으로 불필요하고 영문으로만 구성된 데이터를 전달받아야 하는 이슈<br/>
→ 각 화면마다 필요한 키값들을 구분하고 한글로 가공하여 사용
- 컴포넌트의 뎁스가 깊어지면서 Props Drilliing이 예상되어 전역 상태관리의 필요성을 느낌<br/>
→ 팀원의 역량과 경험수준이 다양했기 때문에 러닝커브가 가장 낮다고 판단되는 Recoil 도입

### 재사용 가능한 컴포넌트 개발

- 화면마다 무분별하게 중복되는 컴포넌트 이슈<br/>
→ 재사용성을 극대화하기 위해 공통 컴포넌트를 개발
- 짧은 기간안에 빠르게 차트와 테이블을 구현할 수 있는 Recharts와 MUI 라이브러리를 활용하여 화면마다 필요한 스타일 커스텀 및 공유
- 재사용 컴포넌트 관리의 중요성 경험 [(상세 보기)](https://velog.io/@leesegho/FF-Components-%EC%9E%AC%EC%82%AC%EC%9A%A9%EC%97%90-%EB%8C%80%ED%95%9C-%EA%B3%A0%EB%AF%BC%EA%B3%BC-%EA%B2%BD%ED%97%98)

### UI/UX 디자인 및 기획 [(상세 보기)](https://www.notion.so/STYLE-GUIDE-901c8c2fe15c4665a6cc5e8821465239)
- UI/UX 디자인과 기획 리딩, 스타일 가이드 공유

## 구현 결과

카테고리 파트의 **검색 데이터 페이지** 입니다.
데이터 키값을 가공 및 적용하여 각기 다른 차트 및 테이블을 구현했습니다.

![검색량](https://user-images.githubusercontent.com/93597794/159906934-9425f11e-9c79-4600-bcf4-a317a6118f0b.png)

스타일 랭킹 파트의 **조건부 검색 필터 페이지** 입니다.
오른쪽의 조건부 필터 페이지를 맡았습니다. 버튼 클릭 시 조건에 맞는 API호출 및 데이터에 맞는 차트 및 테이블을 구현했습니다.

![스타일랭킹_데이터_조회_레이아웃](https://user-images.githubusercontent.com/93597794/159906948-8dc9e091-35d3-44f1-900e-cd129c2210ed.png)
