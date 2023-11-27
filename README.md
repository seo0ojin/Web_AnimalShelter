# Web_AnimalShelter

스프링부트 + JPA

## 🖥️ 프로젝트 소개
유기견동물보호소 + 유기견동물 관련상품 판매 사이트입니다.
<br>

## 🕰️ 개발 기간
* 23.10.16일 - 23.11.15일

### 🧑‍🤝‍🧑 멤버구성
 - 팀장  : 허승범 - 로그인, 회원가입, ID찾기, PW찾기, 마이 페이지(내정보,마이펫,쿠폰), 실종/제보 게시판(CRUD,댓글 쓰기,수정,삭제), 발표
 - 팀원1 : 장희주 - 로그인, 회원가입, ID찾기, PW찾기, 마이 페이지(내정보,마이펫,쿠폰), 실종/제보 게시판(CRUD,댓글 쓰기,수정,삭제)
 - 팀원2 : 전아현 - 메인 페이지, 상품(CRUD), 상품정렬, 위시리스트(CRUD), 카트(CRUD), 로고 제작, PPT제작
 - 팀원3 : 박서진 - 메인 페이지, 상품(CRUD), 상품정렬, 위시리스트(CRUD), 카트(CRUD)
 - 팀원4 : 윤호진 - 주문하기, 주문내역
 - 팀원5 : 최재용 - 보호센터(CRUD),상품평(CRUD)
 - 팀원6 : 이다영 - 입양(CRUD)
 - 팀원7 : 김숙현 - 봉사(CRUD),견학(CRUD)

### ⚙️ 개발 환경
- `Java 8`
- `JDK 1.8.0`
- **IDE** : STS 3.9
- **Framework** : Springboot(2.x)
- **Database** : Oracle DB(11xe)
- **ORM** : JPA

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

#### 입양,봉사,견학 예약
- 날짜 선택(달력으로 지정) 및 시간 선택
- 보호센터 선택
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
