## 홈페이지 설명

# 홈페이지 V3 추가사항
- 메인 화면에서 who is hm21글씨, 이름 등등 부분을 클릭하거나 휠을 움직이면 이벤트 추가
- daily부분에 time table 글씨와 daily 클릭하면 이동할 것인지 확인 하는 창 추가
- movie 클릭시 이미지 3개 각각 마우스를 올리면 사진 변경(onmouseover, onmouseout 이용)
- movie 예고편을 window.open() 링크로 변경 그리고 예고편 자체를 추가 
- moive 클릭시 나타나는 콤보박스, 라디오 박스를 클릭해서 다른페이지로 이동( JS의 onchange를 사용)
- X-Mas 초대장에 클릭 해달라는 문구를 추가하고 클릭시 문구 나오게 함(alert 이용)
- Calculator 부분에 클릭 해달라는 문구 추가후, 곱셈 퀴즈 추가
- 즐겨찾기 링크를 클릭시 이동 할 것인지 묻는 문구 추가
- 홈페이지 메인 우측 하단에 현재 시간 날짜 요일이 추가 ( 초단위 변경)
- 동호회 가입에 제출하기 누르면 제출 되었다고 알림(alert사용)
- 홈페이지 메인에서 로그인 버튼을 누르면 로그인 


# 홈페이지 V2
- Semantic tag로 화면 layout 구성 하였다.
- 기본화면을 hm21 : 나는 누구인가? 로 설정, [hm21's Homepage]를 클릭하면 who is hm21? 과 연결.
- 홈페이지 hm21_rpt02.html 를 실행해도 초기화면은 who is hm21? 이다.
- 상단 메뉴를 누르면 중앙 iframe에 연결된 내용이 뜸
- Dayily에 table,th,td 을 이용해 추가하고 Time Table 글씨를 누르면 나의 시간표도 table,th,td 를 이용해서 구현
- 영화, 여행지 3개를 선택하여 추가했고 list를 통해 영화, 여행 을 선택하거나 그림을 선택하면 이동, 그리고 li 에 이미지를 넣어서 나타냄
- 동호회 모집 form 을 추가, Web form, fieldset tag 를 사용하여 동호회 모집 정보,가입하기 등을 추가
- 7주에 만든 카드로 초대장을 만들고, Table 을 이용해 나타냄
- 즐겨찾는 사이트를 새창에 나올수있게 링크를 사용
- iframe 를 통해 현재 날씨를 볼수있는 사이트를 연결
- 홈페이지 하단에 나의 이름을 표시했고 각종 애니메이션과 style 이용해서 색상 변경
- 글씨는 style 를 이용해 color, background 를 이용해 배경색과 글씨색을 설정 
- 애니메이션은 @keyframes 와 animation ,hover, transform, translate, focus 등을 이용해 움직임
(마우스를 올리면 색상변경, 이동, 커짐 등등)
- 그림과 음악은 media folder 에 저장하였고 영상은 link로 처리해서 연결
