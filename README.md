# <div align="center">**여긴어때**</div>

## PartyRoom

# 📌 프로젝트 소개
+ **프로젝트 명** : 여긴어때 (파티룸 예약 사이트)

+ **개발취지**
현재 국내 숙박어플의 독점장사로 파티룸 예약 사이트의 다양성이 필요하다고 느꼈다.
기존 숙박어플과는 차별화된 서비스를 제공하여 신선함으로 마케팅을 하며 고객 유치를한다.

+ **프로젝트 목적**
요새 인기 부업주제인 파티룸 대여 서비스를 제공하는 전문 사이트를 제작한다.
회원들은 옵션(생일파티, 브라이덜 샤워)등을 선택함으로써 파티의 컨셉에 맞게 꾸며진 파티룸에서 프라이빗한 파티를 즐길 수 있다.


+ **차별점**
기존의 서비스들은 파티룸 컨셉에 맞게 꾸며달라고 추가 부탁을 할 수 없어 컨셉에 맞는 방을 직접 고르고 선택해야 하지만,
프로젝트로 개발된 사이트의 경우 옵션을 선택하여 파티룸 대여시 다양한 선택의 폭을 가질 수 있어 이용객들에게 편리함을 제공한다.


## 📌기간 : 2023.07.17 ~ 2023.08.01 , 2023.08.21 ~ 2023.08.30 
<img src="https://github.com/5seokjin/moya100/assets/131237772/4ae59f3d-691b-416e-8da3-63cb93fe8a06" width="800" height="300"/><br><br>
<img src="https://github.com/5seokjin/moya100/assets/131237772/2956b100-2158-4b69-85cb-e6482876f90b" width="800" height="300"/><br>

# 📌 팀 소개
<img src="https://github.com/5seokjin/moya100/assets/131237772/aceab4c0-d44b-4f74-80fd-5f35f2dbdc9e" width="800" height="300"/><br>

## 📌 백엔드 및 프론트엔드 

### 프론트
1. 메인페이지 제작
2. 회사소개/오시는길 제작
3. 회원가입,로그인 페이지 제작
4. 파티룸 전체보기 페이지 제작
5. 파티룸 종류별 페이지 제작
6. 예약페이지 제작
7. 마이페이지(내정보/예약목록/내가쓴리뷰/내가쓴문의사항)제작
8. 커뮤니티 페이지(공지사항/Q&A/회원게시판)제작
9. 관리자페이지(회원관리,파티룸관리,예약관리,커뮤니티관리,월 별 통계)제작
10. 찜목록페이지
</br>

### 백
1. DB설계
2. 파티룸 조회 구현
3. 페이지별 CRUD 구현
4. 파일 업로드 구현
5. 결제API 검증 및 환불 구현
6. 로그인세션/로그아웃 기능 구현
7. 비밀번호 5회 오류시 계정 비활성화 구현
8. 비동기 중복확인 및 회원가입 기능 구현
9. 비밀번호 암호화 구현
10. 비동기 찜하기 기능 구현
11. 네이버 메일 본인인증 구현
12. 네이버 메일 임시비밀번호 발급 구현
13. 조회수기능 구현
14. 대댓글 기능 구현
15. 페이징 기능 구현
</br>

## 📌 개발 환경

<img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black"/>
<img src="https://img.shields.io/badge/ORACLE-F80000?style=flat-square&logo=oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jQuery&logoColor=white"/>
<img src="https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>
<img src="https://img.shields.io/badge/RStudio-75AADB?style=flat-square&logo=rstudio&logoColor=white"/>

</br>

## 📌 프로젝트 상세
<ul>
    <li><h3>메인화면</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/33d97ed6-7089-472d-b499-6da70609c501" width="800" height="450"/><br>
    • 메인화면<br>   
    • 회사소개<br>
    • 오시는길(카카오API를 이용한 지도 구현)<br>
    <br><br>
    <li><h3>회원가입</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/d9f1bd4d-58f9-45ae-82c5-284f8183bc4b" width="800" height="600" /><br>
    • 네이버 SMTP를 이용한 본인인증<br>
    • AJAX를 이용한 비동기 메일인증,중복체크<br>
    • Spring Security를 이용한 비밀번호 암호화<br>
    <br><br>
    <li><h3>로그인/로그아웃</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/e2c697bc-a8d0-4dd2-8d74-2c75218e9034" width="800" height="600" /><br>
    • 로그인 세션 등록<br>
    • 관리자와 사용자 계정 분리<br>
    • 아이디 찾기 기능<br>
    • 네이버 SMTP를 이용한 임시비밀번호 발급<br>
    • 비밀번호 5회 오류시 계정 비활성화(메일인증으로 활성화) <br>
    <br><br>
    <li><h3>파티룸 조회</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/e19aa199-d606-4665-8e08-05008588c205" width="800" height="450"/><br>
    • 파티룸 전체 조회 가능<br>
    • 파티룸 종류 별 조회 가능<br>
    • 파티룹 침대,노래방 유무 검색 가능<br>
    • 페이징 기능
    <br><br>
    <li><h3>파티룸 상세 보기</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/e9222a45-e79c-44e8-bc6f-2663ea9dd459"/><br>
    • 파티룸 사진 및 정보 조회<br>
    • AJAX를 이용한 비동기 찜하기<br>
    • 해당 파티룸 포토리뷰 조회(사진 클릭 시 확대)<br>
    • 찜목록보기 클릭 시 팝업창 출력<br>
    <br><br>
    <li><h3>파티룸 예약</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/fb73c270-09fe-4fc1-8787-ae87ae436c6a" width="800" height="450"/><br>
    • 인원수,옵션,결제수단 선택<br>
    • 옵션에 따른 실시간 가격변경<br>
    • 날짜에 따라 예약가능시간 버튼 활성화<br>
    • 아임포트를 이용한 검증 및 결제<br>
    <br><br>
    <li><h3>예약목록</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/72506186-d8b3-41db-93bb-9771d1c37c4b" width="800" height="450"/><br>
    • 예약목록 조회<br>
    • 예약 상세보기<br>
    • 예약 취소 및 환불(이용일 하루 전까지만 가능)<br>
    • 이용일 다음날 부터 리뷰작성 버튼 활성화
    • 이용당일,전날 또는 리뷰작성시 리뷰작성 버튼 비활성화
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>공지사항</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/4c0ada28-7ad9-4d4a-8247-2b816c2d13fb" width="800" height="230"/><br>
    • 공지사항 리스트 조회 <br>
    • 공지사항 상세 조회 <br>
    • 조회수 기능<br>
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>문의사항</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/78151734-3176-40e2-8124-bcea67fac5b3" width="800" height="450"/><br>
    • 문의사항 작성/삭제 <br>
    • 문의사항 조회(답변 상태 조회) <br>
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>회원게시판</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/3fdef9c3-6f00-4471-a79e-7fae653fb63c" width="800" height="230"/><br>
    • 대댓글 기능 <br>
    • 본인 글 삭제버튼 출력, 다른회원 글 답변버튼 출력 <br>
    • 글 작성, 답변 시 모달 입력창 출력 <br>
    • 검색기능 <br>
    <br><br>
    <li><h3>포토리뷰</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/af4a2dba-8eb3-4005-8fd1-18a4d08e6039" width="800" height="300"/><br>
    • 포토리뷰 조회/입력/변경/삭제 <br>
    • 파일 업로드 기능(실시간 출력)<br>
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>마이페이지</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/e5a04a33-0b48-4cd5-bd62-156592f2c091" width="800" height="350"/><br>
    • 내정보 조회/수정 <br>
    • 회원탈퇴 <br>    
    <br><br>
    <li><h3>관리자-회원정보,파티룸정보</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/16825dea-72b2-49ce-9a37-8dec28587775" width="800" height="450"/><br>
    • 회원정보 조회/수정/탈퇴 <br>
    • 파티룸정보 조회/추가/수정/삭제 <br>
    • 파일 업로드 기능(실시간 출력) <br>
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>관리자-공지사항</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/79b5c9d1-ab66-47d4-a617-7e6995ea73d6" width="800" height="450"/><br>
    • 공지사항 조회/추가/수정/삭제 <br>
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>관리자-문의사항</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/eeaa7c62-c237-483c-9cdd-13bdce9fde35" width="800" height="450"/><br>
    • 문의사항 답변달기/삭제 <br>
    • 문의사항 조회(답변 상태 조회) <br>
    • 페이징,검색기능 <br>
    <br><br>
    <li><h3>관리자-월 별 예약통계</h3>
    <img src="https://github.com/5seokjin/moya100/assets/131237772/2e60aec1-c90c-4892-8c3f-101e5881e46d" width="800" height="450"/><br>
    • 룸 종류별 예약횟수 조회 <br>
    • 옵션 종류별 예약횟수 조회 <br>    
    <br><br>
        
</ul>

## 📌데이터베이스

<br/>


![ERD](https://github.com/5seokjin/moya100/assets/131237772/19d7f647-e652-4e3b-8512-b23c97925a9f)




<br/>

## 📌효과 및 전망

컨셉에 맞는 파티룸 대여를 원하는 소비자의 수요를 옵션 설정등으로 충족시킴,
장소대여 시장에 대한 경쟁력을 선점할 것으로 기대

## 📌향후 업데이트 사항

1. 소셜로그인 기능 추가 예정


   
