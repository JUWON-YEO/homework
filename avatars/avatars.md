
## HTML/CSS 과제



### 과제 수행 설명 

*HTML* 

- 독립 콘텐츠로 표시하기위해 figure 태그를 사용하고 figcaption 태그로 해당 이미지의 설명을 추가한다.
- 목록 태그인 ul를 이용하여 li 8개와 li태그 안에 이미지를 넣기위해 img태그를 추가 하고 활동여부를 표시하기 위해 span 태그를 추가하였다. 
- span 태그에 aria-label을 추가하여 접근 가능한 설명 텍스트를 입력하였다. 
- 활동 상태를 표시하기위해 활동 중 이미지가 포함되어있는 span태그에 active라는 클래스를 추가하였다. 

* * *

*CSS*

- ul태그에 width속성을 추가한다. width 계산 =  한 줄 (img 사이즈 64px * 4) + (이미지 간격 20px*3) = 314px  / 4번째 8번째 이미지 여백은 제외
- 브라우저 기본 스타일시트 padding 속성을 초기화 시키기 위해 padding:0 추가
- li 리스트 스타일 삭제 및 레이아웃 구현을 위해 float: left 속성을 추가하고 과제 지정 스타일을 추가한다. 활동 여부 표시의 스타일 구현을 위해 position: relative 속성을 추가한다.
- 4번째 li 마다 오른쪽 margin 값이 0이 되도록한다.
- img 원형 이미지 스타일을 구현하기 위해 border-radius : 50%로 지정한다
- span 태그에 position: absolute 속성을 추가하여 li 태그 영역 기준 bottom: 0; right: 0; 으로 스타일을 지정한다.
- active 클래스를 추가한 span 태그 스타일을 구현한다.
- flex를 지원하는 웹 브라우저에서 스타일 구현을 위해 @supports (display: flex) 를 추가한다.
- ul 태그에 display 속성을 추가하고 방향, 콘텐츠 정렬 방식, 콘텐츠 줄넘김 처리를 위한 속성을 추가한다.
- 특정 li 순서를 지정하기위해 구조선택자 :nth-child를 사용하여 order속성을 이용해 특정 순서를 지정한다. 
