# Hi, I'm Bui Hoang Vuong 

**Fresher Java Backend / Fullstack Developer** — Ho Chi Minh City, Vietnam

I build production-grade REST APIs with Java/Spring Boot and design normalized PostgreSQL schemas from scratch. Currently exploring the intersection of backend engineering and AI — from Agentic AI systems to Generative UI — and how these trends reshape the way users interact with modern applications.

---

## Featured Projects

### ONE CLICK JOBS — Microservice-based Job Platform
> Spring Boot · ReactJS · PostgreSQL · Docker · DeepSeek API

A full-stack recruitment platform built with microservice architecture.

- **Microservice design**: Decomposed into Auth Service, Recruitment Service, and Gateway Service — each independently deployable via Docker
- **Database design**: 2 independent PostgreSQL schemas — Auth DB (10 tables, 5 security domains) and Recruitment DB (21 tables, 7 business domains) — with full PK/FK constraints, optimized indexes, and Flyway migrations
- **AI feature**: CV matching powered by DeepSeek API, parsing job descriptions and ranking candidate fit automatically
- **Performance**: Identified 12 redundant parallel API calls per page load via Chrome DevTools & wrk profiling — applied skipFetch optimization, improving throughput from 12.58 → 791 req/s and p99 latency from 1,970ms → 26ms (63x improvement)
- **Frontend**: JWT token refresh, protected routes, role-based UI rendering for Candidate and Employer flows

| Service | Repository |
|---|---|
| Auth Service | [OneClick-authService-be](https://github.com/Shinx99/OneClick-authService-be) |
| Recruitment Service | [OneClick-recruitmentService-be](https://github.com/Shinx99/OneClick-recruitmentService-be) |
| Gateway Service | [OneClick-gatewayService](https://github.com/Shinx99/OneClick-gatewayService) |
| Front-End | [OneClick-authService-fe](https://github.com/Shinx99/OneClick-authService-fe) |

**Demo accounts:**
```
Admin:     admin@example.com / Admin@123
Recruiter (Owner): fpt@example.com / Recruiter@123
Recruiter: recruiter0@example.com / docker
Candidate: candidate0@example.com / Candidate@123
```

---

### MILK TEA SHOP — E-commerce Website
> Spring Boot · VueJS · PostgreSQL · Docker

A full-stack e-commerce platform built as a 5-member team project with Git-based collaboration.

- **Database**: Led end-to-end design — from business requirements analysis and ERD modeling to a normalized PostgreSQL schema (17 tables) with PK/FK constraints and Flyway migrations
- **Backend**: 15 CRUD REST endpoints (Customer, Product, Address, Order) with input validation and unified response format
- **Frontend**: Refactored 8 Vue.js components using composables and service layer pattern

| | Repository |
|---|---|
| Back-end | [milk-tea-ecommerce-springmvc](https://github.com/Shinx99/milk-tea-ecommerce-springmvc) |
| Front-end | [milk-tea-ecommerce-fe](https://github.com/Shinx99/milk-tea-ecommerce-fe) |

**Demo accounts:**
```
Admin:    admin@milktea.local / Admin#123
Customer: customer1@milktea.local / Customer#1
```

---

## Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring-security&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat&logo=vue.js&logoColor=4FC08D)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**DevOps & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Stats

![Profile Views](https://komarev.com/ghpvc/?username=buihoangvuong777&color=blueviolet)
[![GitHub Followers](https://img.shields.io/github/followers/buihoangvuong777?label=Followers&style=social)](https://github.com/buihoangvuong777)

---

## Contact

[![Email](https://img.shields.io/badge/Email-buihoangvuong777@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:buihoangvuong777@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hoangvuongbui--backend-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hoangvuongbui-backend/)

---

> *"Everything seems impossible — until it's done."*
