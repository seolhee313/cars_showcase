## Cars Showcase

RapidAPI의 "Cars by API-Ninjas" API에서 제공하는 자동차 카탈로그를 검색할 수 있습니다.
제조업체, 모델, 연료 등과 같은 여러 기준에 따라 자동차를 필터링할 수 있습니다.

![image](https://github.com/seolhee313/cars_showcase/assets/125417882/bc28e469-7663-4ce2-add4-6ea594c97ed6)

- Live Demo : https://sitecheon-cars-showcase.netlify.app/
- 작업 기간 : 3일

## 정보

- 이 프로젝트는 Javascript Mastery 의 튜토리얼을 기반으로 합니다.
- 새로운 앱 라우터와 서버 측 렌더링을 실험하기 위해 NextJS 애플리케이션 작업에 익숙해지기 위해 이 프로젝트를 시작했습니다.
- Dialog, Transition 및 ComboBox와 같은 구성 요소를 통합하여 HeadlessUI 구성 요소 라이브러리를 사용하였습니다.
- 이 프로젝트는 TailwindCS를 스타일링에 적용하고 TypeScript를 타이핑에 적용하는 데 대한 지식을 강화할 수 있는 기회를 제공했습니다.

## 사용 스택 (클라이언트)

- React 18.2.0
- Typescript 5.1.6
- NextJS 13.4.9
- HeadlessUI 1.7.15
- TailwindCSS 3.3.2

## 특징

- 자동차 카탈로그를 통한 브라우저
- 특정 자동차 검색
- 결과 필터링 (fuel, gas, electricity, 년도 등)
- 특정 자동차에 대한 자세한 정보 읽기

## Screenshots

![Example screenshot](https://i.ibb.co/w01Tx1t/carshowcase.jpg)

## 학습

- NextJS, Typescript 및 TailwindCSS를 사용하여 앱 설정
- Next.js 이미지 구성 요소 사용
- 서버와 클라이언트 구성 요소를 구분합니다("클라이언트 사용"). "비동기" 구성 요소 사용
- Layout.tsx에서 메타데이터 조정
- Transition, Combobox 및 Modal과 같은 헤드리스 UI 구성 요소 및 스타일링 통합
- 서버 측 렌더링을 활용하기 위한 URL 매개변수 조작
- 페이지네이션 구현
- NextJS 애플리케이션에서 환경 변수 처리
- 서버 구성 요소를 사용한 스크롤과 관련된 작은 버그로 인해 앱을 순수한 클라이언트 측 렌더링으로 변환합니다. 서버 측 렌더링과 클라이언트 측 렌더링 간의 구체적인 차이점과 장단점을 이해하는 데 도움이 되었습니다.

## 개발 환경 프로젝트 실행 방법 (Cars API 요청)

1. **레포지토리 클론 :** `git clone https://github.com/seolhee313/cars_showcase.git`
2. **종속성 설치 :** `npm install`
3. **환경 변수 세팅 :** `NEXT_PUBLIC_RAPID_API_KEY` 입력 ([ API-Ninjas ](https://api-ninjas.com/api/cars)에서 API Key 발급 필요)
4. **프로젝트 시작 :** `npm run dev`

## 감사의 말

- 이 프로젝트는 [Javascript Mastery](https://www.youtube.com/@javascriptmastery)의 [튜토리얼](https://www.youtube.com/watch?v=pUNSHPyVryU)을 기반으로 합니다.
