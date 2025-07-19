# 📚 BookMakase

## 📝 프로젝트 개요

여러분은 책을 구매할 때 어떤 기준으로 구매하시나요?
북마카세 서비스를 이용하여 에디터의 감성과 전문성이 담긴 큐레이션 서비스를 제공받아 보세요!

어떤 도서를 구매해야할지 고민될 때 추천 도서를 통해 내가 생각하지 못한 책을 접할 기회를 얻을 수 있습니다.

- **기간**: 2025.06.26 ~ 2025.07.09
- **목표**: 단순한 책 구매를 넘어 몰입형 콘텐츠 경험 제공
- **기획 의도**: 단순한 알고리즘 추천을 넘어, 에디터의 감성과 전문성이 담긴 큐레이션 서비스를 제공합니다.

---

## 🚀 배포 링크

👉 [북마카세](https://bookmakase.com)

---

## 👥 팀원 소개

<table>
  <tr>
    <td align="center"><a href="https://github.com/calendar2"><img src="https://avatars.githubusercontent.com/calendar2" width="130px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/anpang1999"><img src="https://avatars.githubusercontent.com/anpang1999" width="130px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/junesung1004"><img src="https://avatars.githubusercontent.com/junesung1004" width="130px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/sandy-castle"><img src="https://avatars.githubusercontent.com/sandy-castle" width="130px;" alt=""></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/calendar2"><b>차민재</b></a><br>LEAD<br>FRONT-END<br>BACK-END<br>INFRA</td>
    <td align="center"><a href="https://github.com/anpang1999"><b>안광언</b></a><br>FRONT-END<br>BACK-END<br>INFRA</td>
    <td align="center"><a href="https://github.com/junesung1004"><b>박준성</b></a><br>FRONT-END<br>BACK-END</td>
    <td align="center"><a href="https://github.com/sandy-castle"><b>성다은</b></a><br>FRONT-END</td>
  </tr>
</table>

---

## ✨ 주요 기능

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

## 🏛 서비스 아키텍처

---

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

## 🛠 사용 툴 및 기술 스택

| 💻 Frontend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 🚀 Backend                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 🤝 Collaboration Tools                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)<br> ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)<br> ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)<br> ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)<br> ![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=Zustand&logoColor=white)<br> ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)<br> ![Zod](https://img.shields.io/badge/Zod-3178C6?style=for-the-badge&logo=zod&logoColor=white)<br> ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)<br> ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-007396?style=for-the-badge&logo=spring&logoColor=white)<br> ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)<br> ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)<br> ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)<br> ![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)<br> ![Amazon Route 53](https://img.shields.io/badge/Amazon%20Route%2053-FF9900?style=for-the-badge&logo=amazon-route-53&logoColor=white)<br> ![Amazon ELB](https://img.shields.io/badge/Amazon%20ELB-FF9900?style=for-the-badge&logo=amazon-elastic-load-balancing&logoColor=white)<br> ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSONWebTokens&logoColor=white)<br> ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)<br> ![Lombok](https://img.shields.io/badge/Lombok-FFA500?style=for-the-badge&logo=java&logoColor=white) | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)<br> ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)<br> ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)<br> ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)<br> ![erdcloud](https://img.shields.io/badge/ERDCloud-00C853?style=for-the-badge&logo=cloud&logoColor=white)<br> ![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white) |

---

## 📜 라이선스

이 프로젝트의 라이선스는 팀 내부 논의 후 추가될 예정입니다.
