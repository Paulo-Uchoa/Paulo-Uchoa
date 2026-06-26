<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,100:1f6feb&height=200&section=header&text=Paulo%20Uchoa&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%C2%B7%20Java%20%7C%20Spring%20Boot%20%7C%20Angular&descAlignY=60&descSize=18" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Full-Stack+Developer+%F0%9F%92%BB;Java+%7C+Spring+Boot+%7C+REST+APIs;Angular+%7C+TypeScript+%7C+Frontend;Event-Driven+Systems+with+RabbitMQ;Always+learning%2C+always+shipping+%F0%9F%9A%80)](https://git.io/typing-svg)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=paulo-uchoa&color=58a6ff&style=flat-square&label=profile+views)
[![GitHub followers](https://img.shields.io/github/followers/paulo-uchoa?style=flat-square&color=58a6ff&label=followers)](https://github.com/Paulo-Uchoa)

</div>

---

## `$ whoami`

```java
public class PauloUchoa extends Developer {

    String role        = "Full-Stack Developer (Java + Angular)";
    String location    = "São Paulo, SP 🇧🇷";
    String[] focus     = { "RESTful APIs", "Full-Stack Web Apps", "Event-Driven / Messaging" };
    String[] learning  = { "Cloud (AWS/GCP)", "Docker & Kubernetes", "DevOps" };
    String funFact     = "I debug production issues faster with coffee ☕";

    @Override
    public String toString() {
        return "Passionate about clean code and solving real problems.";
    }
}
```

---

## 🛠️ Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

### Frontend
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Messaging & Database
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Testing & DevOps
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🚀 Featured Projects

<div align="center">
  <a href="https://github.com/Paulo-Uchoa/fintrack">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Paulo-Uchoa&repo=fintrack&theme=github_dark&hide_border=true&bg_color=0d1117" alt="FinTrack"/>
  </a>
  <a href="https://github.com/Paulo-Uchoa/notiflow">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Paulo-Uchoa&repo=notiflow&theme=github_dark&hide_border=true&bg_color=0d1117" alt="Notiflow"/>
  </a>
</div>

### 💰 FinTrack — Personal Finance Tracker

A **full-stack** app to organize personal finances: accounts, categories, transactions, monthly budgets and visual reports.

- **What it does:** JWT authentication (register/login), CRUD for accounts and categories, income/expense entries with filters and pagination, per-category budgets tracking *spent vs. limit*, and income × expense reports with a per-category chart.
- **Backend:** Java 17 · Spring Boot 3 · Spring Security (JWT) · JPA/Hibernate · PostgreSQL · Flyway · OpenAPI/Swagger
- **Frontend:** Angular · TypeScript · RxJS + Signals
- **Engineering:** automated tests (JUnit 5, Mockito, Testcontainers), Docker Compose (database + API + web) and GitHub Actions CI

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

🔗 **[View repository »](https://github.com/Paulo-Uchoa/fintrack)**

### 🔔 Notiflow — Event-Driven Notification Service

An **asynchronous** notification service built around **RabbitMQ**. A REST API accepts requests and delivers them in the background through per-channel workers (email, SMS, push).

- **What it does:** per-channel routing, retries with exponential backoff, a **dead-letter queue** for exhausted messages, **idempotent consumers**, and full delivery-status tracking (`PENDING → SENT / FAILED / DEAD`).
- **Stack:** Java 17 · Spring Boot 3 · RabbitMQ / Spring AMQP · PostgreSQL · Flyway · OpenAPI/Swagger
- **Engineering:** integration tests with Testcontainers (real RabbitMQ + Postgres), Docker Compose and GitHub Actions CI

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

🔗 **[View repository »](https://github.com/Paulo-Uchoa/notiflow)**

### 🚗 Mobi Auto — Car Dealership Management API

A REST API for managing car dealerships, with **role-based access** (admin, owner, manager, assistant) and **automatic assignment** of sales opportunities based on assistant workload.

- **Stack:** Java 17 · Spring Boot 3 · Spring Security (JWT) · JPA/Hibernate · Swagger · Docker
- **Highlights:** layered permission checks (`@PreAuthorize` + business rules) and a fair lead-distribution algorithm

🔗 **[View repository »](https://github.com/Paulo-Uchoa/mobi-auto-backend)**

---

## 📊 GitHub Stats

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=paulo-uchoa&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=paulo-uchoa&layout=compact&langs_count=7&theme=github_dark&hide_border=true&bg_color=0d1117"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=paulo-uchoa&theme=github-dark-blue&hide_border=true&background=0d1117" alt="GitHub Streak"/>
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=paulo-uchoa&theme=algolia&no-frame=true&no-bg=true&row=1&column=6" alt="GitHub Trophies"/>
</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=paulo-uchoa&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff" alt="Contribution Graph"/>
</div>

---

## 🎯 Currently Working On

```
🔨  Building full-stack apps with Spring Boot & Angular
📨  Exploring event-driven systems with RabbitMQ
🧪  Writing well-tested code (JUnit, Mockito, Testcontainers)
🌱  Studying cloud & containerization (Docker, AWS)
```

---

## 📫 Let's Connect

<div align="center">
  <a href="https://www.linkedin.com/in/paulo-jose-vieira-uchoa/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:paulojosevieira2011@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Paulo-Uchoa" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:58a6ff&height=60&section=footer" width="100%"/>
</div>
