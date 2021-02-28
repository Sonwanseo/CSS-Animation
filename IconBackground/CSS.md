# CSS Of IconBackground

- white-space: 요소가 공백 문자를 처리하는 법을 지정한다.

  - normal: 연속 공백을 하나로 합침  
    개행 문자도 다른 공백 문자와 동일하게 처리  
    한 줄이 너무 길어서 넘칠 경우 자동으로 줄을 바꿈
  - nowrap: 연속 공백을 하나로 합침  
    줄 바꿈은 \<br> 요소에서만 발생
  - pre: 연속 공백 유지  
    줄 바꿈은 개행 문자와 \<br> 요소에서만 발생
  - pre-wrap: 연속 공백 유지  
    줄 바꿈은 개행 문자와 \<br> 요소에서만 발생  
    한 줄이 너무 길어서 넘칠 경우 자동으로 줄을 바꿈
  - pre-line: 연속 공백을 하나로 합침  
    줄 바꿈은 개행 문자와 \<br> 요소에서만 발생  
    한 줄이 너무 길어서 넘칠 경우 자동으로 줄을 바꿈
  - break-space: 다음 차이점을 제외하면 pre-wrap과 동일
    연속 공백이 줄의 끝에 위치하더라도 공간을 차지  
    연속 공백의 중간과 끝에서도 자동으로 줄 바꿈 가능  
    유지한 연속 공백은 pre-wrap 요소와 달리 바깥으로 넘치지 않으며, 공간도 차지하므로 박스의 본질 크기에 영향을 줌

  참고: [MDN](https://developer.mozilla.org/ko/docs/Web/CSS/white-space)

- user-select: 사용자가 텍스트를 선택할 수 있는지 지정한다.

  - none: 선택 불가
  - auto: 링크 참고
  - text: 선택 가능
  - all: 요소의 콘텐츠가 원차적으로 선택됨
  - contain: 선택의 시작을 이 요소 안에서 한 경우, 범위가 요소 바깥으로 벗어날 수 없음

  참고: [MDN](https://developer.mozilla.org/ko/docs/Web/CSS/user-select)
