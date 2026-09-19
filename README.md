# Giuseppe Pio Ruocco — Fullstack Software Engineer

> Fullstack Software Engineer based in Naples, Italy. I build production systems end-to-end — from Spring Boot REST APIs and microservices to Angular and React frontends — across enterprise consulting engagements and independent products.

Currently an **Analyst Software Engineer at Accenture**, working on an enterprise insurance platform for Generali (EU) and on a web platform for Italy's electricity balancing market (Terna). Previously at **Sistemi Informativi (IBM Company)**. 3+ years of experience in real production environments across insurance, energy, public administration, and healthcare.

[![Portfolio](https://img.shields.io/badge/Portfolio-18181B?style=flat&logo=githubpages&logoColor=white)](https://josephpshine63.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giuseppe-pio-ruocco-7b4367267/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:dev.pioruocco@gmail.com)
![Open to work](https://img.shields.io/badge/Status-Open%20to%20opportunities-6ee7b7?style=flat)

---

## 🚀 Featured Projects

### [WacChat — Real-Time Chat Platform](https://github.com/JosephPshine63/connecting) · [🌐 wacchat.win](https://wacchat.win)
A WhatsApp Web-inspired messaging platform built as Spring Boot 3 microservices: an API gateway (Spring Cloud Gateway), a file service, a notification service, and a call service with WebRTC signaling. Identity is handled by a custom-themed Keycloak realm with Google login, messaging runs over STOMP/WebSocket relayed through RabbitMQ, media is stored on Cloudflare R2, and the whole stack ships with observability (Prometheus, Grafana, Loki, Tempo). Includes "Arno", a Gemini-powered chatbot, and an Angular 19 client generated from the OpenAPI spec. Fully dockerized, with a GitHub Actions CI pipeline and a scripted production deploy.

`Spring Boot 3` `Angular 19` `Keycloak` `RabbitMQ` `WebSocket/STOMP` `WebRTC` `PostgreSQL` `Docker` `Prometheus` `Grafana` `Loki` `Tempo`

---

### [GprFlow — Crypto Trading Platform](https://github.com/JosephPshine63/GprFlow) · [🌐 gprflow.trade](https://gprflow.trade)
A fullstack crypto trading platform: live market data and price charts (CoinGecko), buy/sell against a wallet balance, portfolio with per-asset profit/loss, watchlist, and a Gemini AI chatbot for market Q&A. Authentication uses stateless JWT in an HttpOnly cookie, optional email OTP 2FA, and Cloudflare Turnstile. The backend is being split from a monolith into independent Spring Boot services behind a gateway that handles JWT validation, rate limiting, and request size caps. Payments run through Stripe (test mode on the public demo), and deploys go out via GitHub Actions to a self-hosted server behind a Cloudflare Tunnel.

`Spring Boot` `Spring Cloud Gateway` `React` `Redux` `PostgreSQL` `Stripe` `Gemini AI` `JWT` `2FA` `Docker` `GitHub Actions`

---

### [PioCart — E-Commerce Backend](https://github.com/JosephPshine63/PioCart)
A complete REST API for an e-commerce platform: product and category management, dynamic cart logic, order processing, and user management. JPA domain model with proper relationships (OneToMany, ManyToMany), input validation, and a fully dockerized dev environment.

`Java 17` `Spring Boot 3` `PostgreSQL` `Docker Compose` `ModelMapper` `Lombok`

---

### [BookTribe — Social Reading Platform](https://github.com/JosephPshine63/BookTribe)
A Spring Cloud microservices setup — config server, discovery server, gateway, feedback and notification services — paired with an Angular frontend and a self-managed Keycloak realm, built to explore microservices architecture end-to-end.

`Spring Cloud` `Angular` `Keycloak` `Microservices`

---

## 💼 Experience

**Accenture** — Analyst Software Engineer · Naples *(Nov 2025 – Present)*
- **IIAB** (Generali, EU insurance platform, 200+ people cross-company team): Angular 16+ components (services, modules, pipes) for complex insurance workflows, plus Spring Boot REST endpoints for business logic; GitFlow, PRs, and systematic code reviews across ~8 bi-weekly sprints
- **MSD Terna S.p.A.** (Italy's national electricity balancing market): React + TypeScript frontend and Java / Node.js microservices, Oracle and MongoDB, asynchronous batch processing, real-time WebSocket notifications, Kubernetes deployment and GitLab CI/CD

**Sistemi Informativi (IBM Company)** — Software Engineer · Rome *(May 2024 – Sep 2025)*
- **GDSI** (Armed Forces health data): Spring Boot services, new Keycloak role, Spring Security configuration, Angular 14 optimization, Elasticsearch integration
- **Lucilla** (Municipality of Rome): Angular frontend restructuring and technical/functional documentation
- **CDC/WSO2** (Digital Citizen Hub): application logs and platform monitoring on WSO2
- Oracle DB schema migrations with Liquibase in a multi-team environment

**IndSoftware** — HMI Developer · Angri (SA) *(Nov 2023 – Dec 2023)*
- SCADA/HMI applications for PLC control with Siemens TIA Portal, business logic in VBScript and SQL on Oracle

---

## 🛠 Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java%2017+-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Spring Cloud Gateway](https://img.shields.io/badge/Spring%20Cloud%20Gateway-6DB33F?style=flat&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=flat)

**Frontend**
![Angular](https://img.shields.io/badge/Angular%2014--19-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat&logo=reactivex&logoColor=white)
![React](https://img.shields.io/badge/React%2018-61DAFB?style=flat&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Oracle DB](https://img.shields.io/badge/Oracle%20DB-F80000?style=flat&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=flat)

**DevOps & Observability**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/Git%20%2F%20GitFlow-F05032?style=flat&logo=git&logoColor=white)

**Integrations**
`Stripe` · `Razorpay` · `Gemini AI` · `CoinGecko API` · `Resend` · `Cloudflare R2` · `Cloudflare Turnstile` · `WSO2`

**Self-hosting (homelab, personal)**
`Ubuntu Server` · `UFW` · `Nginx Proxy Manager` · `Cockpit` · `Portainer` · `Nextcloud` · `Pi-hole`

---

## 🧠 AI-Assisted Engineering

I use **Claude Code** as part of my day-to-day workflow. Completed Anthropic Academy courses: *Claude Code 101*, *Introduction to Model Context Protocol*, *Introduction to Agent Skills*, *Introduction to Subagents*, *AI Fluency: Framework & Foundations*, and *Claude 101*.

---

## 💡 About

I care about shipping software that actually runs in production. Over the past three years I've contributed to platforms used across the EU — insurance systems, energy-market tools, public administration and healthcare services — and I build my own projects to explore what genuinely interests me: real-time systems, auth flows, payments, observability, and AI integrations.

I'm most effective when I can own a feature from API design to UI delivery, in teams that move fast and review code seriously.

Open to fullstack or backend roles at product, SaaS, or consulting companies. Outside of work: gym and kickboxing. 🥊

---

## 📬 Contact

- **Email:** [dev.pioruocco@gmail.com](mailto:dev.pioruocco@gmail.com)
- **Portfolio:** [josephpshine63.github.io/portfolio](https://josephpshine63.github.io/portfolio/)
- **LinkedIn:** [giuseppe-pio-ruocco](https://www.linkedin.com/in/giuseppe-pio-ruocco-7b4367267/)
- **Location:** Naples, Italy

---

<p align="center">
  <sub>Built end-to-end, like everything else.</sub>
</p>
