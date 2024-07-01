# 📚 도서관 및 도서 통합관리 웹
국비 훈련 과정에 진행한 [두 번째 팀 프로젝트](https://github.com/jh91019/syLibrary)를 스프링 프로젝트로 변경한 내용입니다.

<br/>

* * *

## 📑 목차
[1. 프로젝트 개요](#1-프로젝트-개요)
  - [주제 및 목표](#-주제-및-목표)
  - [사용 기술 및 팀 구성](#-사용-기술-및-팀-구성)
  - [팀원별 구현 기능](#-팀원별-구현-기능)
   
[2. 프로그램 구조](#2-프로그램-구조)
  - [ER Diagram](#-er-diagram)
  - [View](#-view)
  - [Usecase Diagram](#-usecase-diagram)
  - [Flow Chart](#-flow-chart)

[3. 개별 페이지 안내](#3-개별-페이지-안내)
  - [관리자 화면](#-관리자-화면)
  - [사용자 화면](#-사용자-화면)

[4. 후기 및 개선점](#4-후기-및-개선점)
  - [개선사항](#-개선사항)
  - [프로젝트 후기](#-프로젝트-후기)

<br/>

* * *

## 1. 프로젝트 개요
### 📅 개발 기간
2024.04.01 ~ 2024.04.19 (약 3주)
- 1주차: 기존 프로젝트를 스프링 프로젝트로 변환. 기능 테스트 후 추가 개발 기능, 에러 등을 바탕으로 회의.
- 2주차: 에러 수정 및 기능 개선, 추가 기능 개발 작업 진행.
- 3주차: 2차 기능 테스트 및 개발 작업 마무리. 발표 자료 업데이트.

<br/>

### 📝 주제 및 목표
**[주제]** 도서관 및 도서 통합관리 웹 사이트

**[목표]**
1. 2차 프로젝트를 Spring 프로젝트로 변환
2. 2차 프로젝트의 피드백을 반영하여 추가기능 개발 및 기능 개선
3. 협업 툴로써 Git, GitHub 도입하여 기본 개념 및 명령어 숙지
4. Front-end & Back-end의 다양한 기술스택을 활용한 웹 애플리케이션 구현 및 훈련기간 동안 학습한 내용의 적용

<br/>

### 💻 사용 기술 및 팀 구성

**[사용 기술 및 개발 환경]**
- OS : Windows11
- Front-end  :  HTML5, CSS3, Javascript
- Back-end : JDK21, OracleDB 23.1.1, Spring Boot
- Tools : Spring Tool Suite 4, SQL Developer, Git, GitHub
- Library : Lombok 1.18.30, MyBatis 3.5.15, Json, Jquery 3.7.1, JSTL, Ajax, Bootstrap 5.3, Sweetalert2, Chart.js 4.4.0, Apache Tomcat 10.1.19

<br/>

### 팀원별 구현 기능
![회원별](https://github.com/jh91019/syLibrary_spring/assets/156145497/84b6090f-d88e-44ed-823f-25ccb72146eb)

* * *

## 2. 프로그램 구조
### ☑ ER Diagram
![erd](https://github.com/jh91019/syLibrary_spring/assets/156145497/efbffe4d-7802-4df4-a6be-18dc3651ca90)

<br/>

### ☑ View
![view](https://github.com/jh91019/syLibrary_spring/assets/156145497/69f0ea9e-4bb2-4497-a7ae-b9d974589c2d)

<br/>

### ☑ Usecase Diagram
![usecase](https://github.com/jh91019/syLibrary_spring/assets/156145497/8ed581ca-1c3c-44dd-9201-9083e5bc6a05)

<br/>

### ☑ Flow Chart
**[관리자]**
![flow_admin](https://github.com/jh91019/syLibrary_spring/assets/156145497/16e4062d-0e96-4300-93cc-a5b9de3a2c23)

**[회원/비회원]**
![flow](https://github.com/jh91019/syLibrary_spring/assets/156145497/9fbcad93-cc66-498b-8a01-d3d6f7040949)

<br/>

* * *

## 3. 개별 페이지 안내(수정 사항 파란 글)
### 📌 관리자 화면
#### 🔸메인 화면
![메인화면](https://github.com/jh91019/syLibrary_spring/assets/156145497/310360db-2f96-4599-89eb-02dbb98113ae)

<br/>

#### 🔸도서 관리
![도서 목록 수정](https://github.com/jh91019/syLibrary_spring/assets/156145497/f7be147a-9dc2-4e54-9b9e-78b1d032ed6e)
![도서 등록](https://github.com/jh91019/syLibrary_spring/assets/156145497/4dd7204e-bce1-4ad2-a97a-9e107ab0e711)
![분류등록](https://github.com/jh91019/syLibrary_spring/assets/156145497/3ef6152e-fe9d-40ea-9064-023a9416e742)

<br/>

#### 🔸대출 반납 및 회원 관리
![도서 대출 반납 목록](https://github.com/jh91019/syLibrary_spring/assets/156145497/b9cfd656-cce4-45f7-9383-0a111db55cd7)
![회원 정보](https://github.com/jh91019/syLibrary_spring/assets/156145497/6def3832-fc0a-4fb5-bbeb-95ced8dbe7cb)

<br/>

#### 🔸희망 도서
![희망 도서 관리](https://github.com/jh91019/syLibrary_spring/assets/156145497/d4669a38-635d-4a52-a923-f9b287b5fbb8)
![희망 도서 상세](https://github.com/jh91019/syLibrary_spring/assets/156145497/b07ec660-4c07-4e94-8ab1-6e8803cac519)

<br/>
<br/>

### 📌 회원/비회원 화면
#### 🔸메인 화면
![메인 검색어](https://github.com/jh91019/syLibrary_spring/assets/156145497/dd48170f-f1fb-4ec3-8037-8fad259b9b0e)

<br/>

#### 🔸회원 및 예약 도서
![비밀번호 찾기](https://github.com/jh91019/syLibrary_spring/assets/156145497/47bebde6-e2f6-429f-8ee6-ed88b08e37e7)
![회원 정보 수정](https://github.com/jh91019/syLibrary_spring/assets/156145497/ee118c46-ff2f-4066-b44e-c18d0f7f5b62)
![예약 신청](https://github.com/jh91019/syLibrary_spring/assets/156145497/49a3f96a-714c-4d87-b26b-84a2569ab11b)

<br/>

#### 🔸희망 도서
![희망도서신청](https://github.com/jh91019/syLibrary_spring/assets/156145497/dd80fa40-3de0-4632-83c8-9f2a1237f8bb)
![희망도서신청내역](https://github.com/jh91019/syLibrary_spring/assets/156145497/f524ddbd-8483-4c0d-a384-2fc0623d35d7)

<br/>

* * *

## 4. 후기 및 개선점
### ⚒ 개선사항
- 회원 등급 개념을 추가 ▶ 서비스 이용시 등급에 따른 각기다른 이용권한 부여
- 비밀번호가 DB에 그대로 저장되었던 문제 ▶ 암호화 방식 적용
- 비밀번호 찾기에서 팝업으로 비밀번호를 알려주는 것이 아닌, 회원가입 시 작성한 메일로 임시 비밀번호를 전송하는 방식으로 개선
- 연체 상태에서도 도서 연장이 가능한 오류 발견 ▶ 연체 여부 확인하는 단계를 추가하여 기능 개선
- 개발기간부족으로 기존에 구현하지 못했던 검색어 자동완성 기능 추가
- 희망도서와 관련된 추가 기능 구현 ▶ 오픈API의 적용 및 이용자는 희망도서 신청 및 취소 서비스를 이용할 수 있고, 관리자는 이용자가 신청한 희망도서의 상태를 변경 가능하도록 추가 기능 개발완료

<br/>

### 🖍 프로젝트 후기 
- 동일 프로젝트를 스프링으로 재구성 하는 것 만으로도 도전적인 과제였습니다. 덕분에 많은 공부가 되었고 한층 성장할 수 있는 시간이었습니다.
- 추가 기능 개발을 포함해 미처 확인하지 못했던 에러나, 아쉬웠던 점 등을 보완하여 완성도를 높은 프로젝트로 발전시킬 수 있었습니다.
- Git을 활용함으로써 SVN과는 다른 방식으로 협업을 경험해 볼 수 있었습니다.

