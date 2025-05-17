![image](https://github.com/user-attachments/assets/fa00936b-1448-492a-9b95-62a98232c97a)

---
# 📚 프로젝트 소개

## 개요

**목차**
- 개발 환경
- 프로그램 구조 및 ERD
- 구현한 기능

---

## 🛠 개발 환경

- **개발언어**: HTML5, CSS3, JS(ES6), jQuery, JAVA, MySQL  
- **개발 OS**: Windows(10, 11), Mac  
- **WAS**: Apache Tomcat 9.0  
- **사용 API**:
  - 네이버, 카카오 로그인
  - 네이버 지도
  - 카카오 결제
  - 다음 우편번호
  - tinymce 텍스트 에디터  
- **개발 툴**:
  - Eclipse, MySQL, Visual Studio Code

---

## 🏗 프로그램 구조

<details>
<summary>📂 프로그램 구조 보기</summary>

![프로그램 구조](./assets/structure.png)

</details>

<details>
<summary>🧩 ERD 보기</summary>

![ERD](./assets/erd.png)

</details>

---

## ✅ 구현한 기능

### 🏠 메인화면

![메인화면](./assets/main-page.png)

- 레시피, 스토어 품목 중 평점 상위 3개 출력  
- 공지사항 출력  
- 게시판 게시글 중 조회수 상위 5개 출력  

---

### 🍳 레시피

![레시피](./assets/recipe.png)

- 레시피 CRUD  
- tinymce 텍스트 에디터 적용  
- 카테고리별 조회 및 검색  
- 레시피 리뷰 작성 기능  

---

### 🛒 스토어

![스토어](./assets/store.png)

- 밀키트 CRUD  
- 카테고리별 조회 및 검색  
- 밀키트 리뷰 작성 기능  

---

### 🗂 게시판

![게시판](./assets/board.png)

- 공지사항 / 자유게시판 / 공유게시판 CRUD  
- 공유게시판에 네이버 지도 API 연동  
- 게시글 검색 기능  

---

### 👤 회원 관리

![회원관리](./assets/user.png)

- 네이버/카카오 로그인 API 적용  
- 다음 우편번호 API 활용한 주소 입력  
- 회원정보 수정/탈퇴  
- 작성한 콘텐츠 관리 (레시피, 스토어, 리뷰 등)  
- 주문 내역 및 등록 품목 관리  
- 최근 본 항목 및 찜한 목록 조회  
- 장바구니 기능 지원  

---

### 💳 결제화면

![결제화면](./assets/payment.png)

- 회원 정보 출력 및 수정  
- 다음 우편번호 API 적용  
- 카카오 결제 API 연동  

---

## 🧩 추가 클래스

- [`DBConnector.java`](https://github.com/euneick/FoodJoa/blob/main/src/Common/DBConnector.java)  
  → DB 연결 반복 방지를 위한 클래스  

- [`FileIOController.java`](https://github.com/euneick/FoodJoa/blob/main/src/Common/FileIOController.java)  
  → 파일 등록/삭제, 경로 삭제 등 파일 관리  

- [`StringParser.java`](https://github.com/euneick/FoodJoa/blob/main/src/Common/StringParser.java)  
  → 문자열 파싱 유틸 클래스

---

💡 이 마크다운 문서는 GitHub `README.md`에 문제없이 저장되고,  
이미지는 `assets` 폴더에 직접 넣어야 합니다.

더 많은 개발 노하우와 마크다운 작성법은 [GPT 온라인](https://gptonline.ai/ko/)에서도 확인하실 수 있어요 😊
