<img width="303" alt="login" src="https://github.com/hyeiiin/home-work/assets/126502807/ac2f5214-7e7d-41e9-9d90-0f1f061282bf">

.login\_\_box: 로그인 폼을 감싸는 컨테이너 역할을 하는 <div> 요소

<h1>로그인</h1>: 로그인 폼의 제목을 나타내는 <h1> 요소
  
.login__formbox: 로그인 폼을 감싸는 박스 역할을 하는 <div> 요소
  
.login__form: 실제 로그인 폼이 있는 <form> 요소
  
.id_form: 아이디 입력 필드와 레이블을 감싸는 <div> 요소
  
<label for="id">아이디</label>: 아이디 입력 필드에 대한 레이블
  
<label for="password">비밀번호</label>: 비밀번호 입력 필드에 대한 레이블
  
아이디랑 비밀번호 사용자에게 입력받을 수 있게 Input태그
  
placeholder사용해서 사용자가 무엇을 입력해야 하는지 알 수 있게 힌트 제공
  
.line: 하이퍼링크를 포함하는 <div> 요소
  
<ul>: 목록을 나타내는 <ul> 요소
  
로그인 버튼을 나타내는 <button> 요소 
  
type속성이 "submit"으로 설정, class 속성이 "formInput__button"으로 지정

.login**box: 로그인 전체 박스에 대한 스타일. 배경색, 그림자 효과, 크기 및 여백 등이 포함
.login**box h1: 로그인 제목 텍스트에 대한 스타일. 폰트 크기, 색상 및 여백이 포함
.login**form: 로그인 폼 박스에 대한 스타일. 배경색, 크기, 모서리 반경 등이 포함
.id_form: 간격 조절을 위한 스타일.
fieldset label: 아이디와 비밀번호 텍스트에 대한 스타일. 폰트 크기, 색상, 크기 등 포함
.login**form input: 아이디와 비밀번호 입력 필드에 대한 스타일. 크기, 테두리, 배경색 등이 포함
.id_form::after: 아이디 폼을 정렬하기 위한 스타일.
clear: both를 사용하여 float 된 요소 뒤에 위치한 요소들을 정렬
.login**form button: 로그인 버튼에 대한 스타일. 크기, 배경색, 색상 등이 포함.
position: absolute를 사용하여 위치를 조정
.login**box ul: 회원가입 및 아이디/비밀번호 찾기 링크를 포함하는 목록에 대한 스타일
.line: 구분선에 대한 스타일
.login\_\_box a: 회원가입 및 아이디/비밀번호 찾기 링크에 대한 스타일

box-shadow 그림자 효과를 추가
border-radius 박스의 모서리 둥글게
position: relative 폼 박스를 상위 요소를 기준으로 배치할 수 있도록 설정
float 속성을 사용하여 왼쪽으로 정렬
position: absolute는 버튼을 절대적인 위치에 배치
border: none는 버튼의 테두리를 삭제

- 마크업 순서 1. 로그인(제목), 2. 아이디 레이블과 입력서식, 3. 비밀번호 레이블과 입력서식, 4. 로그인 버튼, 5. 회원가입 및 아이디/비밀번호 찾기 링크 순
- 일부 요소의 배치를 position 속성을 활용
- 회원가입, 아이디/비밀번호 찾기 영역은 float을 활용
