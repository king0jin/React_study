# React_study
React프로젝트 생성해서 실행해보기

## React
1. User Interface를 효율적으로 구성하는 JavaScript라이브러리이다
2. Web SAP를 구현해주는 Front-End JavaScript프레임워크이다

### 핵심 기술
+ Virtual DOM : 실제 DOM을 가상으로 표현한 것으로 빠르고 간편하게 UI를 렌더링한다

### 프론트엔드 템플릿 엔진
+ 서버에서 처리한 데이터를 클라이언트가 받아서 자바스크립트 객체들과 조합해서 DOM으로 구성하여 제공한다

### 서버에서 데이터를 받아오는 것 - React 자체 기능이 아니므로 할 수 없다
1. ajax, fetch API, web socket, sse등은 직접 구현하여 데이터 받아오기
2. 별도의 라이브러리를 이용하여 데이터 받아오기

## React 프로젝트 생성하기 전 필요한 환경 설정
+ Node.js 설치 - 공식 웹사이트에서 다운로드
  + Node.js : JavaScript 런타임 환경으로, 서버에서도 JavaScript를 실행할 수 있게한다
  + 설치확인 : **node --version**
+ npm 설치 - Node.js를 설치하면 기본적으로 npm도 함께 설치된다
  + 패키지 관리도구로 사용한다
  + 설치확인 : **npm --version**
+ yarn 설치
  + npm과 유사한 패키지 관리 도구이다
  + 속도와 캐싱 성능이 뛰어나다
  + 설치하기 : **npm install --global yarn**
  + 설치확인 : **yarn --version**

## React 프로젝트 생성하기
**yam create react-app 앱이름**

## React 프로젝트 실행하기
앱이름이 있는 디렉토리로 이동해서 프로젝트 실행하기
**yam start**
![image](https://github.com/user-attachments/assets/39a27dc4-d80c-4b3f-b0b7-e96ac167d645)


### 배포파일 생성하기
**yarn build**
+ build 디렉토리가 생성되며 배포 가능한 번들파일(HTML, CSS, JavaScript 파일)을 생성한다
+ build 디렉토리의 파일들을 웹 서버에 업로드하여 실제 서비스 환경에서 사용할 수 있다.

#### 일반적인 배포 방법
AWS S3, Netlify, Vercel, GitHub Pages 등으로 배포한다 
