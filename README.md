###BUILD SETUP

```

react-native init 프로젝트명 --template typescript
리액트네이티브 프로젝트 생성 with typescript

npm install --save styled-components
스타일드컴포넌트 라이브러리
npm install --save-dev @types/styled-components
타입스크립트를 위한 스타일드컴포넌츠의 타입 정의 파일

npm install --save-dev babel-plugin-root-import
리액트네이티브는 기본적으로 상대경로를 쓰는데(../../../Button)
babel-plugin-root-import 를 사용하면 절대경로 사용이 가능하다(~/Button)

```