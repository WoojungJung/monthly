# SpringBoot-Project-MONTHLY
스프링부트 프로젝트
<br>

![로고 ](https://github.com/dafssdf/Spring_Portfoilo/assets/95078635/0e830cb0-bcd1-4da5-b0d9-d3d770321fcf)

## 🖥️ 프로젝트 소개
구독 서비스 중심 이커머스 플랫폼
<br>

## 🕰️ 개발 기간
* 23.06.04일 - 23.07.17일

### 🧑‍🤝‍🧑 팀원 구성
 - 팀장: 정우정 : 판매자 페이지(로그인, 판매자정보수정, 브랜드 등록, 주문배송 관리, 제품등록, 제품수정 제품리스트관리), 판매장 신청 페이지
 - 부팀장: 김준혁 : 정기결제, 구독관리, 제품 상세 페이지, 댓글,회원정보 수정(배송지,비밀번호,회원탈퇴) 
 - 팀원1: 박은서 : 관리자 페이지(차트페이지,회원관리,상품관리,구독자관리), 결제날짜 문자 발송 기능
 - 팀원2: 강승연 : 메인 페이지, 브랜드 페이지, 상품 페이지, 더보기 사이드바, 상품검색
 - 팀원3: 김덕수 : 로그인, 회원가입, 아이디/비밀번호 찾기, 카카오,네이버 로그인 api

### ⚙️ 개발 환경
- `Java 11`
- `JDK 1.8.0`
- **IDE** : IntelliJ 2021.x
- **Framework** : Springboot(2.x)
- **Database** : Oracle DB(11xe)
- **ORM** : Mybatis

### 🧾MONTHLY 포트폴리오(PDF)
[monthly포트폴리오용.pdf](https://github.com/WoojungJung/monthly/files/12236039/monthly.pdf)


## 📌 내가 맡은 기능
#### 판매자 신청  <a href="https://github.com/WoojungJung/monthly/wiki/%F0%9F%93%A9-%ED%8C%90%EB%A7%A4%EC%9E%90-%EC%8B%A0%EC%B2%AD" >상세보기 - WIKI 이동</a>
- 아이디 중복 검사
- 아이디, 비밀번호, 이메일 정규표현식
- 주소검색 api  
#### 판매자 로그인  <a href="https://github.com/WoojungJung/monthly/wiki/%F0%9F%99%8E%E2%80%8D%E2%99%80%EF%B8%8F%F0%9F%99%8E%E2%80%8D%E2%99%82%EF%B8%8F%ED%8C%90%EB%A7%A4%EC%9E%90-%EB%A1%9C%EA%B7%B8%EC%9D%B8" >상세보기 - WIKI 이동</a>
- 판매자, 관리자 탭으로 로그인 경로 처리
- 로그인 Interceptor 

#### 판매자 메인 : 주문, 배송 관리  <a href="https://github.com/WoojungJung/monthly/wiki/%F0%9F%93%8B-%EB%A9%94%EC%9D%B8-:-%EC%A3%BC%EB%AC%B8%EB%B0%B0%EC%86%A1%EA%B4%80%EB%A6%AC" >상세보기 - WIKI 이동</a>
- 주문상태, 주문번호, 날짜 조건 검색
- 주문, 배송 정보 변경 비동기 저장
- 검색 후 리스트 페이징 처리

#### 브랜드 & 판매자 정보 관리  <a href="https://github.com/WoojungJung/monthly/wiki/%F0%9F%95%8D-%EB%B8%8C%EB%9E%9C%EB%93%9C-&-%ED%8C%90%EB%A7%A4%EC%9E%90-%EC%A0%95%EB%B3%B4-%EA%B4%80%EB%A6%AC" >상세보기 - WIKI 이동</a>
- 브랜드 정보 등록 및 수정
- 대표 이미지 파일 처리
- 판매자 정보 비동기 조회,수정, 저장
- Daum 주소 api 활용

#### 제품 등록  <a href="https://github.com/WoojungJung/monthly/wiki/%E2%9C%8F-%EA%B5%AC%EB%8F%85-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%A0%9C%ED%92%88-%EB%93%B1%EB%A1%9D" >상세보기 - WIKI 이동</a>
- 새로운 구독 서비스 제품 등록
- 대표 이미지 및 상세 이미지 파일 저장 처리, 이미지 미리보기
- 썸머노트 api로 내용 등록 처리

#### 제품 관리  <a href="https://github.com/WoojungJung/monthly/wiki/%F0%9F%8E%81-%EC%A0%9C%ED%92%88-%EB%A6%AC%EC%8A%A4%ED%8A%B8-:-%EC%A0%9C%ED%92%88-%EA%B2%80%EC%83%89,-%ED%8C%90%EB%A7%A4%EC%83%81%ED%83%9C-%EB%B3%80%EA%B2%BD" >상세보기 - WIKI 이동</a>
- 제품 리스트, 제품 조건 검색, 리스트 페이징 처리
- 제품 판매 상태 변경 비동기 저장
- 제품 상세 페이지로 이동

#### 제품 수정  <a href="https://github.com/WoojungJung/monthly/wiki/%F0%9F%93%9D-%EC%A0%9C%ED%92%88-%EC%83%81%EC%84%B8-%EC%A0%95%EB%B3%B4-%EC%88%98%EC%A0%95" >상세보기 - WIKI 이동</a>
- 제품 상세 정보 조회, 수정, 저장
- 이미지 파일 저장 처리, 썸머노트 api 이용

### 주요 서비스 화면
- 메인페이지
![monthly_main편집본](https://github.com/WoojungJung/monthly/assets/126428419/df1431ab-2714-41c5-8243-020bca55c2e0)
- 제품상세페이지
![monthly_product편집본](https://github.com/WoojungJung/monthly/assets/126428419/b7ec8dbc-c4f0-4b0b-bc3d-9e4c5f016d93)
- 마이페이지
![monthly_mypage](https://github.com/WoojungJung/monthly/assets/126428419/d5dcc106-fd3a-44e1-9d60-5538c0ba457f)
- 판매자 주문관리
![주문관리](https://github.com/WoojungJung/monthly/assets/126428419/0eae74c6-ba4f-4081-8e67-bcdf10688f59)
- 판매자 브랜드관리
![브랜드관리편집본](https://github.com/WoojungJung/monthly/assets/126428419/7855c9c2-404e-4539-9cac-750efdf3b553)
- 제품관리
![제품관리](https://github.com/WoojungJung/monthly/assets/126428419/d8924865-434d-424e-9e72-3529c8be3c14)
- 제품등록 및 수정
![상품수정](https://github.com/WoojungJung/monthly/assets/126428419/ed8f0bd1-9c2f-423a-b11f-be7237ce64bd)



