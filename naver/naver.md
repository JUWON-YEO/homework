


## 네이버 로그인 과제 

### HTML
- picture > source 태그를 사용하여 svg를 지원하지 않는 브라우저 대응

- 아이디 비밀번호 input에는 필수 입력을 받을 수 있도록 required 속성 추가

- ip보안 클릭 시 ip_secruity.html 파일을 열기 위해 a태그에 파일 링크 추가 후 새창에서 여는 속성 target="_blank" 추가 후 rel ="noopener noreferrer" 속성을 사용하여 _blank 문제점 보완

- ip보안 on/off 기능을 구현하기 위해 checkbox 타입으로 구현

***

 ### CSS

  > 공통 CSS
- 반응형 공통 스타일 먼저 지정
- :focus 속성으로 포커스 스타일 지정
- login-info영역을 레이아웃 구현을 위해 display:flex 속성 추가 <br/><br/>

> 모바일 CSS
- 미디어 쿼리를 사용해 768px 이하 사이즈에서 반응형 레이아웃 구현을 위해 login-form 영역에 max-width 지정  
- ip 보안 영역은 모바일에서 안보이게 처리 후 로그인 상태 유지 영역을 flex 영역 마지막에 배치 <br/><br/>

>데스트탑 CSS
- 미디어 쿼리를 사용하여 768px 이상 사이즈에서 레이아웃 구현
- login-form 영역을 width를 500px로 고정

