## React <br>
**✨ 리액트 사용 이유 : 컴포넌트 재사용성, 단방향 데이터 흐름, 가상 DOM(Virtual DOM)**

## **리액트 시작하기**
1. node.js 최신 버전 설치(cmd에서 node -v, npm -v 버전 확인)
2. vscode에서 작업할 폴더 열기
3. 터미널 열고(ctrl+shift+`) ```npx creat-react-app '프로젝트명'```
4. Success가 뜨면 프로젝트 생성 완료!
5. 폴더 열기 -> 생성된 하위 프로젝트 열어서 App.js(메인 페이지에 들어갈 HTML 짜는 곳)에 코딩 시작!
6. public/index.html 파일이 메인페이지
- public : static 파일 보관함/src : 소스코드 보관함/package.json : 설치한 라이브러리 목록

코드 짠 걸 미리 확인하기 위해서 터미널 열고 ```npm start``` 작성하면(프로젝트 명 꼭 확인하고!) 새 창으로 열림

**✨ node.js 설치 이유 : create-react-app 라이브러리 때문**
- node.js 설치하면 npm(Node Package Manager)을 통해 다양한 라이브러리와 모듈을 손쉽게 관리할 수 있음
- npm으로 create-react-app 이용
  
**✨ 데이터 바인딩**
- 변수에 넣기
- state에 넣기
- 이벤트 핸들러를 통한 데이터 바인딩
- Props를 이용한 데이터 바인딩

**✨ state** 
- state(state가 변경되면 HTML이 재렌더링 됨)
1. 변수 대신 쓰는 데이터 저장공간
2. useState()를 이용해 만들어야함 ```[state 데이터, state 데이터 변경 함수]```
- state 사용하기
1. {useState} 상단에 첨부 ```import React, { useState } from 'react';```
2. useState(데이터)
3. 문자, 숫자, array, object 다 저장가능 <br>
```let [글제목, 글제목변경] = useState(['여자 옷 추천', '수원 맛집']);```
{글제목[1]} -> 하면 여자 옷 추천 출력 <br>
<자주 바뀌는, 중요한 데이터를 변수 말고 state로 저장해서 쓰기>

**✨ onClick** <br>
```onClick={클릭될 때 실행할 함수}``` <br>
```onClick ={()=>{실행할 내용}}```


## **✨ Selector 선택자** <br>
**✨ Selector 사용 이유 : DOM(Document Object Model)을 사용하여 HTML 문서의 요소에 접근하고 조작할 수 있게 해주고, 각각의 메서드는 특정 조건에 맞는 요소를 선택하여 JavaScript를 통해 동적인 변경이나 상호작용을 할 수 있도록 함**
**✨ Selector 종류** <br>
