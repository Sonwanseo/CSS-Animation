# CSS of CupOfTea

- box-sizing: 요소의 너비와 높이를 계산하는 방법을 지정  
  기본 값에서 지정한 너비와 높이는 요소의 콘텐츠 박스 크기에만 적용된다.  
  요소에 테두리나 안쪽 여백이 있으면 너비와 높이에 더해서 화면에 그린다.  
  따라서 크기를 설정할 때, 원하는 크기를 얻으려면 테두리나 안쪽 여백을 고려해야 한다.

  즉, box-sizing이 content-box일 때는, 너비나 높이를 지정했을 때 content의 크기에만 영향을 주고,  
  box-sizing이 border-box일 때는, 너비나 높이를 지정했을 때 content 뿐만 아니라 border까지 계산해서 크기가 지정된다.

  참고: [MDN](https://developer.mozilla.org/ko/docs/Web/CSS/box-sizing)

- background linear-gradient: 두 개 이상의 색이 직선을 따라 점진적으로 변화하는 이미지를 생성한다.  
  내부에 전달할 수 있는 값

  - \<side-or-corner>: 그레디언트 축의 시작점.  
    지정할 경우 최대 두 개의 방향을 나타내는 키워드를 사용할 수 있다.
  - \<angle>: 그레디언트 축의 방향.  
    0deg는 to top과 같다.
  - \<linear-color-stop>: 색상 정지점의 \<color> 값 하나 혹은 두 개의 선택적인 정지점 위치
  - \<color-hint>: 두 인접한 색상 정지점에서 그레디언트가 진행하는 방식을 지정하는 보간 힌트

  참고: [MDN](<https://developer.mozilla.org/ko/docs/Web/CSS/linear-gradient()>)

- transform rotate: 요소를 회전시키거나 확대/축소하거나 비트는 등 형태를 변형시킬 수 있다.  
   rotate(angle)  
  angle에는 각의 크기를 입력한다.  
  단위는 deg, rad, grad, turn 등을 사용한다.

  참고: [Coding Factory](https://www.codingfactory.net/12593)

- animation: 애니메이션 속성의 약식 속성이다.  
  border: 0; border-top: 15px; border-right: 15px;을 border: 15px 15px 0 0;이라 표현하는 것과 유사하다.  
  애니메이션의 다양한 속성을 하나의 식으로 표현할 수 있다.

  animation: name duration timing-function delay iteration-count direction fill-mode play-state;  
  linear은 애니메이션이 처음부터 끝까지 일정한 속도로 진행되게 한다.  
  infinite는 애니메이션의 반복횟수를 무한으로 설정한다.

  참고: [W3School](https://www.w3schools.com/cssref/css3_pr_animation.asp)

- filter: 속성 흐림 효과나 색상 변형 등 그래픽 효과를 요소에 적용한다.

  blur 값은 주어진 이미지에 가우시간 블러를 적용한다(흐리게 보인다, 값이 커질수록 더 흐려짐).
  외에도 많은 효과를 추가할 수 있다.

  참고: [MDN](https://developer.mozilla.org/ko/docs/Web/CSS/filter)

- style: --i:n은 사용자 지정 속성이다.

  사용자 지정 속성의 값을 사용할 때에는 일반적인 값의 자리에 var() 함수를 지정하고, 그 매개변수로는 사용자 지정 속성의 이름을 제공한다.

  참고: [MDN](https://developer.mozilla.org/ko/docs/Web/CSS/Using_CSS_custom_properties)
