
## apple 과제 

### HTML
- grid 스타일을 적용시키기 위해 전체 묶는 div태그 사용.

- 각각의 컴포넌트는 article태그를 사용.

- 컴포넌트 제목은 h2태그로 작성하고, 부제목은 em 태그를 사용.

- '출시일 추후 공개' 문구는 일부 컴포넌트에만 적용시키기 위해 클래스를 추가.

- 컴포넌트 내용을 flex로 스타일링 하기 위해 링크 2개를 div로 묶음.

***

 ### CSS

  > 공통 CSS
- 1024px이하 스타일 먼저 적용

- 전체를 감싸는 card-wrap클래스에 `gird`속성을 지정하고 `grid-template-columns` 속성은 1024px이상 레이아웃 구현을 위해 2열로 나누고 사이즈는 1fr로 지정

- card-component 영역 내부 레이아웃 구현을 위해 'flex' 속성 추가 

- `background-image`, `background-size`, `background-position` 공통 스타일 지정 

- `grid-column` 속성 값을 'span 2'로 추가

- 해상도별 이미지 사이즈 적용하기 위해 `background-image: image-set` 속성 사용 <br/><br/>


> 1024px 이상 레이아웃 변경 
- .iphone-15, .watch, .macbook-air, .airpod-pro 영역 레이아웃을 2행으로 구현하기 위하여 `grid-column` 속성 값을 'span 1' 로 변경

- 화면 크기에 따라 `backgorund-image`를 변경하기 위하여 필요 컴포넌트 클래스마다 `background-image` 속성 추가  <br/><br/>

> 과제후기
- 변수사용이 처음엔 어려웠는데 이젠 많이 익숙해져서 편하게 사용할 수 있게 되었다!

- flex속성에 비하여 grid는 많이 사용하지 않은 상태라 손에 익히기 위해 다양한 컴포넌트를 만들어봐야할 것 같다. (아직은 어려운 grid...)

- 시멘틱 마크업과 웹 접근성에 고민하는 시간이 점점 많아지고있다. 하지만 아직도 정확하기 알지 못하는 부분이 많은것같아서 자료를 많이 찾아보는게 좋을 것 같다. <br/><br/> 


![과제 영상](Apple.gif)
