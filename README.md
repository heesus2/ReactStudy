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


## **✨ Selector 선택자** <br>
**✨ Selector 사용 이유 : DOM(Document Object Model)을 사용하여 HTML 문서의 요소에 접근하고 조작할 수 있게 해주고, 각각의 메서드는 특정 조건에 맞는 요소를 선택하여 JavaScript를 통해 동적인 변경이나 상호작용을 할 수 있도록 함**
**✨ Selector 종류** <br>
1. getElementById('id명')
2. getElementsByClassName('class명')[선택 요소 인덱스] <br>
-> id 선택에는 Element! class 선택에는 Elements! s 기억하기/'' 사이에 .이나 # 안붙이고 클래스명, 아이디명 작성
3. querySelector('.class명')
4. querySelectorAll('.class명')[선택 요소 인덱스] <br>
-> 클래스 선택자: .className
-> 아이디 선택자: #idName
  
