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
- 데이터 수정 방법
1. 기존 state 카피본 만들기
2. 카피본에 수정사항 반영하기
3. 변경함수()에 집어넣기

**✨ onClick** <br>
```onClick={클릭될 때 실행할 함수}``` <br>
```onClick ={()=>{실행할 내용}}```


## **✨ Component** <br>
- 리액트에서의 Component는 UI를 구성하는 요소로서 독립적이고 재사용 가능한 코드 블록
- 각각의 컴포넌트는 자체적으로 상태(state)와 속성(props)을 가질 수 있으며, 이를 통해 동적이고 유연한 UI를 만들 수 있음
- Component 만드는 법(funtcion App() 끝나는 부분에 작성, function App()도 일종의 Component)
1. 함수 만들고 이름짓고
2. 축약을 원하는 HTML 넣고
3. 원하는 곳에서 <함수명/>
- Component 유의사항
1. 이름은 대괄호
2. return() 안에 있는건 태그하나로 묶어야함
3. 하나의 div 태그로 묶기 싫다면 <>, </>로 묶기
- Component로 묶으면 좋은 것
1. 반복 출현하는 HTML 덩어리들
2. 자주 변경되는 HTML UI들


**✨ Component 타입**
- 함수형 컴포넌트 (Functional Components): ES6의 화살표 함수나 일반 함수를 사용하여 정의되며, 주로 상태나 생명주기 메서드가 필요하지 않은 단순한 컴포넌트에 사용됨

- 클래스형 컴포넌트 (Class Components): ES6의 클래스를 사용하여 정의되며, 상태나 생명주기 메서드 등의 기능을 활용할 수 있음




**✨ Selector 종류** <br>
