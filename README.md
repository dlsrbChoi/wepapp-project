# webapp-miniproject

부트스트랩(Bootstrap)
- 다양한 크기의 사용자 디바이스에 최적의 웹 화면 UI를 구현할 수 있도록 제공되는 반응형 웹 프론트엔드 디자인 툴킷
- HTML + CSS + JAVASCRIPT

기능요약
- Layout : 화면 레이아웃(구조)를 구성, 특히 반응형 웹을 처리
- Content : 타이포그래피, 이미지, 테이블 등
- Forms : 사용자 입력 처리와 관련된 디자인 (input, select, checkbox, radio 등)
- Components : Forms를 제외한 화면 UI 요소
- Helpers : UI 요서에 대한 위치, 비율 , 보이기/감추기 등
- Utilities : 보더, 색상, 사이즈, 정렬 등
- Extend : 아이콘

웹서버 구축
- mkdir server
- npm init
- npm i express --save
- npm i express-session --save
- npm i mysql --save

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 1. 개발환경 설정
- 개발 툴 및 필요 프로그램 설치
- API 서버 프로젝트 클론

## 2. Vue CLI 프로젝트 생성
- Prettier
- ESLint
- jsconfig

## 3. 뷰 라우터 및 컴포넌트 설계
- ```<router-link>```
- ```<router-view>```
- ```mode: history```와 서버 배포시 주의 사항
- 코드 스플리팅 ```component: () => import('경로')```

## 4. 회원 가입 페이지 개발
- 사용자 폼 처리
- async & await
- axios
- swagger API 문서 보는 방법

## 5. 실무 환경 구성
- ```axios.create()```
- env 파일 설정 방법
- Vue CLI 버전 3 이상에서의 env 파일 규칙

## 6. 로그인 페이지 개발
- 사용자 폼 처리 기능 구현
- async & await 에러 처리 방법
- 사용자 폼 유효성 검사

## 7. 로그인 상태 관리
- Vuex를 이용한 사용자 아이디 관리
- ```this.$router.push('/main')```

## 8. API 인증 처리를 위한 토큰 관리
- JSON Web Token
- ```Authorization``` 토큰 값으로 API 인증을 받는 방법
- ```axios.interceptors```

## 9. 학습 노트 데이터 조회
- 학습 노트 목록 표시 기능 구현
- 목록 아이템 컴포넌트화
- 스피너를 이용한 데이터 로딩 상태 표시

## 10. 브라우저 저장소를 이용한 인증 값 관리
- 쿠키를 이용한 로그인 인증 값 저장
- actions를 이용한 컴포넌트 로직 정리

## 11. 학습 노트 데이터 생성
- 학습 노트 생성 기능 구현
- 학습 노트 본문 길이 유효성 검사
