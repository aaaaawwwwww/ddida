# DDIDA (뛰다)
### 스프링부트와 JPA를 활용한 RestAPI(OpenAPI 포함) 서버 개발 및 배포
### 주제 : 시설물 관리 및 대여 시스템
#### 프로젝트 기간 : 2024.01.15 - 2024.02.22

## 프로젝트 소개
#### OpenAPI로 받아 온 체육 시설물 정보로,
#### 사용자는 원하는 시설을 예약하고 관련된 문의나 후기를 남기고 
#### 관리자는 시설물 정보와 사용자의 문의/후기를 관리할 수 있도록 서비스를 제공하는
#### 체육시설 예약 사이트입니다.

## **개발환경**<br>
|   |    |
----|----|
**OS**|Windows 10|
**IDE**|Spring Tool Suite 4 4.21.0.RELEASE|
**Front-end**|HTML<br>CSS<br>JavaScript<br>JSP<br>XML<br>Bootstrap 5.3|
**Back-end**|Java 17<br>Spring Framework 5.2.25.RELEASE<br>lombok 1.18.30|
**Database**|MySQL 8.0.22|
<br>

## **팀원별 업무 분담**<br>
|    |**박재용(팀장)**|**김민혜(팀원)**|**노윤건(팀원)**|
|----|---|---|---|
|**Front**|**페이지**<br>- 로그인<br>- 회원가입 <br>- [이용자] 메인 페이지 <br>- [이용자] 뛰맵<br>**컴포넌트**<br>- header<br>- footer|**페이지**<br>- [이용자] 문의 목록/상세/등록<br>- [이용자] 예약 목록/상세<br>-[이용자] 내 정보 조회<br>-[이용자] 비밀번호 변경 <br>**컴포넌트**<br>- 페이지네이션|**페이지**<br>-[관리자] 문의 목록/상세 <br>- [관리자] 회원 목록/상세<br>- [관리자] 시설 목록/상세<br>**컴포넌트**<br>- 검색 그룹|
|**Back**|- 로그인/로그아웃<br>- 회원가입 <br>- 로그인 인증 <br>- [이용자] 메인페이지 시설 검색 <br>- [이용자] 뛰맵 OpenAPI 연동<br>-[이용자] 내 정보 조회<br>- [이용자] 비밀번호 변경|- [이용자] 문의 목록/상세/등록 <br>- [이용자] 문의 수정/삭제<br>- [이용자] 예약 목록/상세 <br>- [이용자] 이용 후기 등록 <br>- 페이지네이션<br>- 검색<br>|- [관리자] 문의 목록/상세 <br>- [관리자] 문의 답변 등록 <br>- [관리자] 회원 목록/상세<br>- [관리자] 시설 목록/상세<br>|

