# 한국어로 된 지번주소 or 도로명주소 를 경도,위도로 바꾸는 시스템

팀프로젝트를 하면서 경도,위도를 통해 지도 위에 위치를 찍는 모델을 만들었다.

문제는 엑셀 자료 중 해당 주소에 해당되는 경도,위도를 알려주지 않는 자료도 있다는 사실!

이 경우 어떻게 해결해야되나 고민하는 중,

조원 한 분께서 해결방법을 알려주셨다.

`http://www.gisdeveloper.co.kr/?p=4784`

이 url로 들어가기를 바란다.

여기서 알려주는 방법 그대로 수행하기만 하면 해당 주소에 해당되는 경도,위도를 알 수 있다.

작성자께서 성실하셔서 오류사항이나 질문을 답글로 달면,

2017년부터 최근(2021.06)까지 친절하게 알려주신다.

필자가 사용해본 결과 너무나도 쉽게 사용가능하며 정보도 정확하게 나오는 프로그램이다.

단, 유의사항이 있다.

- csv로 저장된 함수여야만 한다.
- 지번주소, 도로명 주소 어느거나 사용해도 상관없다.
- 한국어 주소만 가능하다.
- 결과 SHP 파일이라고 써있는 부분에 파일명을 꼭 작성해주어야 된다. 
- 결과 SHP 파일은 UFT-8 옆에 있는 ...을 이용해서 지정해주어야 된다. 
- 결과 SHP 파일은 파일명이 겹치면 안된다.
- 제일 중요한 것! 오전10시부터 밤10시까지만 사용 가능하다. 오후 11시 사용하다가 당황했다..

실습결과는 첨부하겠다!

