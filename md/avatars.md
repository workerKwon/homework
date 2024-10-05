## float 배치

-   각각의 이미지들을 span으로 감싸고 span에 float: left 속성을 줘서 배치되도록 함
-   줄 바꿈이 일어날 5번째 span에 clear: both 속성으로 다른 float 속성에 영향을 받지 않도록 함.
-   span에 position: relative 속성으로 ::after 선택자의 상위 요소로 적용되도록 함
-   span::after 가상 선택자를 접속상태를 표시하는 용도로 사용하기 위해 position:absolute를 주고 top, bottom 속성으로 위치를 조정함
-   각 상태마다 class name을 login, logout으로 부여하여 배경색을 추가함

## flex 배치

-   `div>div*2>span*4>img` 구조로 이미지를 4개씩 감싸는 div 2개와 그 div 2개를 flex속성으로 조정하기 위한 상위 div하나로 감싸서 만들었음
-   최상위 div에 display: flex 속성을 주고, flex-direction: column-reverse 속성으로 내부 2개 div를 역순으로 진행되도록 함.

### 폰트 사이즈 0

-   font-size: 0 속성으로 인라인 요소의 간격 공백을 제거함
