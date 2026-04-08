<h1 align="center">Avinash Pathak</h1>

<p align="center">
  <strong>Java Backend Developer | Spring Boot | Secure Multi-Tenant Systems</strong><br/>
  Designing scalable, secure backend architectures with production mindset
</p>

<p align="center">
  <a href="https://github.com/avinashee0012">
    <img src="https://img.shields.io/badge/GitHub-brown?style=flat-square&logo=github">
  </a>
  <a href="https://www.linkedin.com/in/avinashee0012/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin">
  </a>
  <a href="mailto:avinashee0012@gmail.com">
    <img src="https://img.shields.io/badge/Email-purple?style=flat-square&logo=gmail">
  </a>
</p>

---

## About Me

Java Backend Developer specializing in building **scalable, event-driven REST APIs** using Spring Boot.

I design backend systems with:

* Clean layered architecture and separation of concerns
* Event-driven and asynchronous processing patterns
* Secure API design with authentication and authorization
* Transactional consistency and reliable data handling
* Production-style practices including logging, error handling, and resilience patterns

Previously spent **6+ years at Amazon** handling SLA-critical escalations and performing structured root cause analysis. This experience shaped a strong engineering focus on **system reliability, clear debugging workflows, and predictable backend behavior**.

## Backend Toolkit

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-informational?style=flat-square&logo=openjdk">
  <img src="https://img.shields.io/badge/Spring_Boot-Framework-brightgreen?style=flat-square&logo=springboot">
  <img src="https://img.shields.io/badge/Spring_Security-JWT-success?style=flat-square&logo=springsecurity">
  <img src="https://img.shields.io/badge/Microservices-Architecture-blue?style=flat-square">
  <img src="https://img.shields.io/badge/REST_APIs-Design-blue?style=flat-square">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JPA-Hibernate-orange?style=flat-square">
  <img src="https://img.shields.io/badge/MySQL-Database-blue?style=flat-square&logo=mysql">
  <img src="https://img.shields.io/badge/MongoDB-NoSQL-darkgreen?style=flat-square&logo=mongodb">
  <img src="https://img.shields.io/badge/Redis-Caching-red?style=flat-square&logo=redis">
  <img src="https://img.shields.io/badge/Maven-Build-red?style=flat-square&logo=apachemaven">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JUnit-Testing-green?style=flat-square">
  <img src="https://img.shields.io/badge/Docker-Containers-blue?style=flat-square&logo=docker">
  <img src="https://img.shields.io/badge/Git-Version_Control-cyan?style=flat-square&logo=git">
  <img src="https://img.shields.io/badge/Linux-Environment-yellow?style=flat-square&logo=linux">
</p>

## Projects

### 🔹 [NotifyHub](https://github.com/avinashee0012/notifyhub) – Event-Driven Notification Platform *(Active Development)*

A scalable backend system that processes application events and delivers notifications asynchronously through messaging pipelines and real-time channels.

**Key Highlights:**

* Event-driven architecture with asynchronous processing using RabbitMQ
* REST APIs for event ingestion, notification retrieval, unread filtering, and read status updates
* Background worker service converting domain events into user notifications
* Real-time notification delivery using WebSocket push messaging
* Reliability features including retry handling, dead-letter queues, and idempotent processing
* Containerized infrastructure with Docker and docker-compose

**Tech:** Java 17 · Spring Boot · RabbitMQ · Spring Data JPA · WebSocket · MySQL · Docker · OpenAPI

### 🔹 [Zorvyn](https://github.com/avinashee0012/zorvyn) – Finance Management Backend System

A production-style backend system for managing financial records with secure authentication, role-based access control, and analytical dashboard insights.

**Key Highlights:**

* Clean layered architecture (Controller–Service–Repository) ensuring maintainable and scalable design 
* 25+ REST APIs covering authentication, user management, financial records, and dashboard analytics
* JWT-based stateless authentication with Spring Security and method-level RBAC using `@PreAuthorize`
* Financial records module with CRUD, pagination, sorting, keyword search, and multi-criteria filtering
* Dashboard APIs delivering income, expense, balance, category summaries, and recent transactions via aggregation queries
* Production-grade features including soft delete, DTO validation, and centralized exception handling
* Unit and repository testing using JUnit, Mockito, and H2 in-memory database

**Tech:** Java 17 · Spring Boot · Spring Security · JWT · Spring Data JPA · MySQL · H2 · Maven · OpenAPI

### 🔹 [HireFlow](https://github.com/avinashee0012/hireflow) – Multi-Tenant Recruitment Backend *(1st stable release made | Active Development)*

A production-style recruitment platform backend supporting organisation-level governance and role-based workflows.

**Key Highlights:**
- Multi-tenant architecture with strict tenant isolation
- 20+ REST APIs covering job creation, candidate applications, shortlisting, and organisation controls
- JWT-based stateless authentication with fine-grained RBAC (SUPPORT / ORGADMIN / RECRUITER / CANDIDATE)
- Explicit domain lifecycle enforcement preventing illegal state transitions
- Defense-in-depth authorization (controller + service layer validation)
- Transactional consistency across aggregates

**Tech:** Java 17 · Spring Boot · Spring Security · JWT · JPA · Hibernate · MySQL

### 🔹 [Online Video Rental](https://github.com/avinashee0012/online-video-rental) – Secure Backend System

A domain-driven rental system backend with enforced business invariants.

**Key Highlights:**
- 15+ REST APIs using layered architecture
- JWT-based authentication with ADMIN / CUSTOMER authorization
- Rental lifecycle enforcement (e.g., max active rentals per user)
- Centralized exception handling with consistent HTTP responses
- JPA/Hibernate entity modeling with relational mapping

**Tech:** Java 17 · Spring Boot · Spring Security · JWT · JPA · MySQL

---

<p align="center">
  <em>Secure APIs. Explicit domain rules. Production-oriented design.</em>
</p>
