# 📚 BookMakase
React + Spring Boot 기반 온라인 도서 판매 플랫폼

---

## 🚀 배포 링크
👉 [배포링크추가](배포링크추가)

---

## 👥 팀원 및 역할 분담
BookMakase는 4명의 팀원이 협업하여 개발한 온라인 도서 판매 플랫폼입니다.

| 이름         | 담당 기능                                                   |
|--------------|--------------------------------------------------------------|
| 🛠 차민재 | 인프라 구축, 도서 상세/주문내역 구현, 리뷰/댓글/주문 로직 구현|
| 🛠 성다은 | 장바구니 페이지, GitHub README 작성                          |
| 🛠 박준성 | 로그인/회원가입/마이페이지, 인증/인가 로직 구현              |
| 🛠 안광언 | 관리자 페이지, 추천 도서 로직, 도서 CUD 로직 구현            |

---

## 📝 프로젝트 개요
BookMakase는 사용자 친화적인 UI와 강력한 백엔드를 통해  
온라인에서 책을 검색하고 구매할 수 있는 웹 애플리케이션입니다.

- **기간**: 2025.06.26 ~ 2025.07.09
- **목표**: 단순한 책 구매를 넘어 몰입형 콘텐츠 경험 제공
- **기획 의도**: 단순한 알고리즘 추천을 넘어, 에디터의 감성과 전문성이 담긴 큐레이션 서비스를 제공합니다.

---

## 🎥 메인 시연 영상
![BookMakase 메인 시연](이미지자리)

---

## 💡 서비스 기획 배경

> 📌 **큐레이션의 필요성**  
수많은 도서가 쏟아지는 시대, 독자들은 *“무엇을 읽어야 할지”* 고민합니다.  
믿을 수 있는 에디터의 추천을 통해 선택의 피로를 줄이고, 보다 만족스러운 독서 경험을 제공합니다.

> 📌 **기계적 추천의 한계 극복**  
알고리즘 기반 추천은 사용자의 취향을 완전히 반영하지 못하고, 반복적인 추천을 남기기 쉽습니다.  
에디터의 감성과 전문성을 더한 *“의도 있는 추천”* 으로 차별화된 서비스를 제공합니다.

> 📌 **콘텐츠 중심의 구매**  
책은 단순한 상품이 아니라, 콘텐츠와 스토리를 담고 있는 문화적 경험입니다.  
에디터가 책의 가치와 배경을 소개하여 *“몰입형 구매 경험”* 을 제공합니다.

---

## ✨ 주요 기능 (Features)

### ✅ 사용자
- 회원가입 / 로그인 (JWT 인증)
- 도서 검색 및 상세 페이지 조회
  - ![도서 리뷰 관련 시연](이미지자리)
- 장바구니 기능 (수량 조절, 선택 삭제)
  - ![장바구니 시연](이미지자리)
- 결제 및 주문 내역 확인
  - ![결제 페이지 시연](이미지자리)

---

### ✅ 관리자
- 도서 CRUD(등록/수정/삭제)
  - ![도서관리 시연](이미지자리)
- 주문 관리
  - ![주문관리 시연](이미지자리)
- 회원 관리
  - ![회원관리 시연](이미지자리)

---

## 🛠 사용 툴 및 기술 스택

| 💻 Frontend                                                                                           | 🚀 Backend                                                                                             | 🤝 Collaboration Tools                                                           |
|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)<br> ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)<br> ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)<br> ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)<br> ![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=Zustand&logoColor=white)<br> ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)<br> ![Zod](https://img.shields.io/badge/Zod-3178C6?style=for-the-badge&logo=zod&logoColor=white)<br> ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)<br> ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-007396?style=for-the-badge&logo=spring&logoColor=white)<br> ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)<br> ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)<br> ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)<br> ![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)<br> ![Amazon Route 53](https://img.shields.io/badge/Amazon%20Route%2053-FF9900?style=for-the-badge&logo=amazon-route-53&logoColor=white)<br> ![Amazon ELB](https://img.shields.io/badge/Amazon%20ELB-FF9900?style=for-the-badge&logo=amazon-elastic-load-balancing&logoColor=white)<br> ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSONWebTokens&logoColor=white)<br> ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)<br> ![Lombok](https://img.shields.io/badge/Lombok-FFA500?style=for-the-badge&logo=java&logoColor=white) | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)<br> ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)<br> ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)<br> ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)<br> ![erdcloud](https://img.shields.io/badge/ERDCloud-00C853?style=for-the-badge&logo=cloud&logoColor=white)<br> ![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white) |

---

## 🏛 시스템 아키텍처

### 📡 인프라
Amazon EC2, ELB, Route 53  
Docker로 컨테이너화된 서비스 관리

### 🎨 Frontend
Next.js 기반 CSR  
Zustand, TanStack Query 상태 관리

### 🛠 Backend
Spring Boot REST API  
PostgreSQL DB 연동

---

## 📜 라이선스
이 프로젝트의 라이선스는 팀 내부 논의 후 추가될 예정입니다.
