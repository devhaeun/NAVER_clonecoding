# NAVER_clonecoding
네이버 메인 페이지를 HTML/CSS를 이용해 구현한다.
2024.07.11. 시작

## 페이지 분할
- 양쪽에 최소 margin을 가지고 중앙 정렬되는 부분을 id=center-contents로 감싼다.
- 최상단 메뉴 아이콘부터 검색창과 그 아래 소형 바로가기 아이콘 메뉴를 포함하는 부분을 top 메뉴(id=bf-main)로 구분한다.
- 로그인 상자부터 배경이 하얀 부분을 main 메뉴(<main>)로 구분한다.
- 회색 배경에 광고와 공지사항, Partners, Developers 등을 포함하는 부분은 <footer>로 구분한다.

### 문제점
- 검색창 하단의 작은 아이콘들(<div id="nav">)의 위치 맞추기