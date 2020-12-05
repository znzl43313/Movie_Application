# 박스오피스 주간 순위 확인 앱

### 실행 과정

실행시키면 로그인 페이지가 나오며, 로그인 버튼을 누르면 링크창과 버튼이 있는 창으로 넘어간다. </br>
'박스오피스 주간 순위 확인' 버튼을 클릭하면 박스오피스 주간 TOP 10의 순위가 누적관객수와 함께 카드뷰 리스트로 나오게 된다.


### ?

박스오피스 영화 목록을 일간에서 주간으로 바꿨으며, 기존에 있던 ImageView를 제거하고 TextView를 만들어 순위를 표시하게 하였다. </br>
movieNm를 통해 영화 제목을 표시하고, audiCnt를 통해 누적관객수를 표시하였으며 rank로 영화의 순위를 표시하였다.


### UI

전체적으로 딱딱한 느낌보다는 부드럽고 깔끔한 느낌을 주기를 원해, 그것을 토대로 스타일을 바꾸었다.

- 리스트 페이지 </br></br>
박스오피스 주간 순위 확인 버튼 :  width, height 값을 주어 크기를 지정했으며,
btn.xml을 만들어 버튼에 테두리를 추가하였고 corners 를 추가해 모서리를 둥글게 하여 각진 느낌을 없앴다.
또한, 테두리 색과 버튼의 백그라운드 색도 변경하였는데 명도가 높은 색을 지정하여 더욱 부드러운 느낌을 주었다. </br></br>
순위 텍스트 : font style을 Bold로 지정하고 font color를 레드로 지정하여 더욱 눈에 띄기 쉽게 변경하였다. </br></br>

- 로그인 페이지 </br></br>
로그인 버튼 : 더욱 깔끔한 디자인을 위해 통일성 있게 순위 확인 버튼과 동일하게 만들었다.
