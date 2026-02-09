## 👋 김정환

백엔드 개발자를 지향하며  
**확장성·성능·명확한 설계**에 관심이 많습니다.

- 🔭 현재: [무엇을 공부/개발 중인지]
- 🌱 관심 분야: [Backend, Database, Distributed System]
- 💬 사용 기술: [Java / Spring / MySQL / Redis 등]
- 📫 Contact: [hwan20202@gmail.com]

---

## 🛠 Tech Stack

### Backend
- Java, Spring Boot, JPA, Spring Data
- REST API, MVC Architecture

### Database
- MySQL (InnoDB)
- Redis

### Infra / DevOps
- Docker
- AWS (EC2, S3)

### Tools
- Git, GitHub
- IntelliJ IDEA

### ETC
- Notion

---

## 📌 Featured Projects

### 🔹 lesson-platform
> 실시간 온/오프라인 강의(커피챗, 과외, 강연 등)을 위한 플랫폼

- 기간: 2026.1.6 ~ 2026.1.22 (약 2주)
- 기술 스택: Spring Boot, JPA, MySQL
- 역할: 백엔드 개발
  - ERD 설계
  - 강의 도메인 구현
  - 스케쥴 도메인 구현
  - 결제 도메인 구현
   
- 핵심 구현
  - 1:1 멘토링 기능에서 재고 관리 시 DB insert 과정에서 발생하는 동시성 이슈룰 해결하기 위해서 Mysql 네임드락을 사용하여 해결
  - Spring MVC에서 결제 api 재시도 로직이 스레드를 과도하게 점유하는 문제를 즉시 응답 + 스케쥴러 + 결과 조회 api로 해결
  - 외부 api 호출을 트랜잭션에서 분리하는 과정에서 발생할 수 있는 정합성 문제를 History + 보상 로직으로 해결
    
👉 [lesson-platform-backend Repository 링크](https://github.com/hwan20202/lesson-platform-backend)


### 🔹 molly
> 의류 이커머스 플랫폼

- 기간: 2025.3 ~ 2025.4 (약 2달)
- 기술 스택: Spring Boot, JPA, MySQL
- 역할: 백엔드 개발
  - 상품 도메인 구현
   
- 핵심 구현
  - RDBMS에서 필터 및 정렬을 구현하는 과정에서 데이터 증가 시 성능저하 문제를 해결하기 위해서 노력

- 성과
  - 조회 api의 병목을 파악하는 과정에서 RDBMS의 동작과 한계에 대해서 이해할 수 있었습니다.
  - CQRS 패턴의 필요성을 이해하고, CQRS 패턴을 적용하기 위해서 데이터의 일관성을 보장하기 위한 로직이 중요함을 배울 수 있었습니다.
    
👉 [molly-api Repository 링크](https://github.com/hwan20202/molly-api)

---

## 📖 Study & Writing


---

## ✨ About Me

- 문제의 **원인을 끝까지 파고드는 개발자**
- "왜?"를 설명할 수 있는 코드를 지향합니다.
- 협업에서의 **커뮤니케이션과 문서화**를 중요하게 생각합니다.
<!--
**hwan20202/hwan20202** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
