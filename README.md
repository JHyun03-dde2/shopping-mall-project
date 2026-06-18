# Humi Shopping Mall

실제 온라인 마켓 운영 경험을 바탕으로 기획하고 구현한 **Spring Boot 기반 마켓형 의류 쇼핑몰 웹 프로젝트**입니다.

* **프로젝트 형태**: 개인 프로젝트
* **개발 기간**: 2025년 9월 ~ 지속 개선 중
* **배포 링크**: https://shopping-mall-production.up.railway.app
* **도메인**: 미설정
* **서비스 컨셉**: 힙한 러블리 무드의 마켓형 의류 쇼핑몰

---

## 1. 프로젝트 소개

**Humi Shopping Mall**은 실제 에이블리 마켓 운영 경험을 바탕으로 제작한 의류 쇼핑몰 웹 프로젝트입니다.

단순히 쇼핑몰 화면을 따라 만드는 것이 아니라, 사용자가 상품을 탐색하고 구매하는 흐름과 관리자가 상품, 주문, 회원, 문의를 운영하는 흐름을 함께 구현하는 데 중점을 두었습니다.

사용자는 상품 목록 조회, 상품 상세 확인, 찜, 장바구니, 주문/결제, 마이페이지 기능을 이용할 수 있으며, 관리자는 상품 등록·수정·삭제, 주문 관리, 회원 관리, 문의 및 공지사항 관리를 할 수 있도록 구성했습니다.

또한 Railway 배포, Cloudinary 이미지 저장, 배송 추적 API 연동을 적용하며 실제 서비스 운영에 가까운 개발 흐름을 경험했습니다.

---

## 2. 사용 기술

### Backend

* Java
* Spring Boot
* JPA / Hibernate
* MyBatis
* Lombok

### Frontend

* JSP
* JSTL
* HTML
* CSS
* JavaScript

### Database

* MySQL
* Railway Cloud Database

### Infra / External Service

* Railway
* Cloudinary
* tracker.delivery

### Tools

* Git
* GitHub
* MySQL Workbench
* Notion

---

## 3. 내가 맡은 역할

이 프로젝트는 개인 프로젝트로 진행했기 때문에 기획, 화면 설계, DB 설계, 백엔드 개발, 프론트엔드 구현, 배포, 운영 이슈 대응까지 전체 흐름을 직접 수행했습니다.

| 역할        | 수행 내용                                                       |
| --------- | ----------------------------------------------------------- |
| 서비스 기획    | 실제 마켓 운영 경험을 바탕으로 사용자 쇼핑 흐름과 관리자 운영 흐름 정의                   |
| UI/UX 설계  | 상품 목록, 상품 상세, 장바구니, 주문/결제, 마이페이지, 관리자 화면 구성                 |
| DB 설계     | 회원, 상품, 이미지, 찜, 장바구니, 주문, 문의, 리뷰, 재입고 알림 데이터 구조 설계          |
| 백엔드 개발    | Spring Boot 기반 Controller, Service, Repository/Mapper 구조 구현 |
| 프론트엔드 구현  | JSP, JSTL, HTML, CSS, JavaScript를 활용한 사용자/관리자 화면 구현         |
| 외부 서비스 연동 | Cloudinary 이미지 저장, tracker.delivery 배송 추적, Railway 배포 적용    |
| 운영 이슈 대응  | DB 접속 문제, 이미지 저장 방식, 환경변수 관리, 보안키 관리 등 개선                   |

---

## 4. 주요 기능

### 사용자 기능

* 회원가입, 로그인, 로그아웃
* 상품 목록 조회
* 카테고리별 상품 조회
* 상품 상세 조회
* 상품 찜 등록 및 해제
* 장바구니 상품 추가, 수량 변경, 삭제
* 주문/결제 흐름 구성
* 주문 내역 확인
* 마이페이지 관리
* 상품 문의 및 공지사항 확인
* 품절 상품 재입고 알림 신청

### 관리자 기능

* 관리자 대시보드
* 상품 등록, 수정, 삭제
* 상품 이미지 관리
* 상품 카테고리 관리
* 주문 목록 및 주문 상세 관리
* 회원 목록 및 회원 정보 관리
* 상품 문의 확인 및 답변 관리
* 공지사항 등록 및 관리
* 클레임 및 환불 관련 운영 흐름 관리

### 외부 연동 기능

* Cloudinary를 활용한 상품 이미지 저장
* tracker.delivery를 활용한 배송 추적
* Railway를 활용한 웹 서비스 배포

---

## 5. 실행 화면 또는 캡처 이미지

### 메인 화면

![메인 화면](./docs/images/main.png)

### 상품 목록 화면

![상품 목록 화면](./docs/images/product-list.png)

### 상품 상세 화면

![상품 상세 화면](./docs/images/product-detail.png)

### 장바구니 화면

![장바구니 화면](./docs/images/cart.png)

### 주문/결제 화면

![주문 결제 화면](./docs/images/order.png)

### 마이페이지 화면

![마이페이지 화면](./docs/images/mypage.png)

### 관리자 대시보드

![관리자 대시보드](./docs/images/admin-dashboard.png)

### 관리자 상품 관리 화면

![관리자 상품 관리 화면](./docs/images/admin-product.png)

### 관리자 주문 관리 화면

![관리자 주문 관리 화면](./docs/images/admin-order.png)
