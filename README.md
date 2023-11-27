# Web_AnimalShelter

스프링부트 + JPA

## 🖥️ 프로젝트 소개
유기견동물보호소 + 유기견동물 관련상품 판매 사이트입니다.
<br>

## 🕰️ 개발 기간
* 23.10.15일 - 23.11.15일

### 🧑‍🤝‍🧑 멤버구성
 - 팀장  : 허승범 - 로그인, 회원가입, ID찾기, PW찾기, 마이 페이지(내정보,마이펫,쿠폰), 실종/제보 게시판(CRUD,댓글 쓰기,수정,삭제), 발표
 - 팀원1 : 장희주 - 로그인, 회원가입, ID찾기, PW찾기, 마이 페이지(내정보,마이펫,쿠폰), 실종/제보 게시판(CRUD,댓글 쓰기,수정,삭제)
 - 팀원2 : 전아현 - 메인 페이지, 상품(CRUD), 상품정렬, 위시리스트(CRUD), 카트(CRUD), 로고 제작, PPT제작
 - 팀원3 : 박서진 - 메인 페이지, 상품(CRUD), 상품정렬, 위시리스트(CRUD), 카트(CRUD)
 - 팀원4 : 윤호진 - 주문하기, 주문내역, 입양동물(CRUD), 동물정렬
 - 팀원5 : 최재용 - 보호센터(CRUD),상품평(CRUD)
 - 팀원6 : 이다영 - 입양(CRUD)
 - 팀원7 : 김숙현 - 봉사(CRUD),견학(CRUD)

### ⚙️ 개발 환경
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://camo.githubusercontent.com/bc9be2d5f2cd9023c12067484478eba2228d9f6e0861d6d1ad3839d0f4c4959f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f61706163686520746f6d6361742d4638444337353f7374796c653d666f722d7468652d6261646765266c6f676f3d617061636865746f6d636174266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&amp;logo=apachetomcat&amp;logoColor=white" style="max-width: 100%;">
<img src="https://camo.githubusercontent.com/85b327c3aeb9db239bb1aa4a792223c3afa67d1cb8aac87a6640c7d21882ba5b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f537072696e672044617461204a50412d3243323235353f7374796c653d666f722d7468652d6261646765266c6f676f3d616d617a6f6e646f63756d656e746462266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/Spring Data JPA-2C2255?style=for-the-badge&amp;logo=amazondocumentdb&amp;logoColor=white" style="max-width: 100%;">
<img src="https://camo.githubusercontent.com/bbd5d3ebdffeb4494f3d8d4ae3bf47c8494adf9f0b8738869ddf92008e171d55/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5468796d656c6561662d3030354630463f7374796c653d666f722d7468652d6261646765266c6f676f3d5468796d656c656166266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&amp;logo=Thymeleaf&amp;logoColor=white" style="max-width: 100%;">


## 📌 주요 기능
#### 로그인
- DB값 검증
- ID찾기, PW찾기
- 로그인 시 세션(Session) 생성

#### 회원가입
- 주소 API 연동
- ID 중복 체크

#### 마이 페이지
- 주소 API 연동
- 회원정보 변경
- 마이펫 등록,수정,삭제
- 주문내역
- 입양내역
- 봉사내역

#### 상품
- 상품 목록
- 상세페이지
- 상품 검색
- 카테고리별 정렬

#### 장바구니
- 장바구니 목록
- 선택주문 및 삭제

#### 위시리스트
- 위시리스트 목록
- 선택삭제

#### 주문
- 선택주문
- 포인트, 쿠폰 사용
- 주소 API 연동

#### 입양동물
- 동물 목록
- 카테고리별 정렬

#### 입양,봉사,견학 예약
- 날짜 선택(달력으로 지정) 및 시간 선택
- 보호센터 선택
- 보호센터 지도 API 연동
- 예약 완료

#### 메인 페이지
- 실종/제보 게시판 나열(클릭시 해당 게시글로 이동)
- 입양 가능한 동물 나열(클릭시 해당 동물 입양신청 페이지로 이동)

#### 실종/제보 게시판
- 글 작성, 읽기, 수정, 삭제(CRUD)
- 댓글작성,수정,삭제(로그인 상태에서만 가능)

#### 관리자 페이지 
- 회원탈퇴
- 상품 추가
- 보호센터 추가
- 입양 가능한 동물 추가
- 입양, 봉사, 견학 상태 변경
- 봉사 완료 시, 포인트 적립
- 주문 배송상태 변경
