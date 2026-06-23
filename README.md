<div align="center">

# Burhan Cabiroglu

### Backend Software Engineer | AI-augmented systems | Java, Spring Boot, .NET, Microservices

I build production backend systems where reliability matters: distributed services, financial application flows, message-driven architectures, CI/CD automation, and observability-heavy production support. I am especially interested in the AI era of backend engineering: reliable APIs, event pipelines, agentic workflows, and systems that make intelligent products dependable in production.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-burhancabiroglu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/burhancabiroglu)
[![Email](https://img.shields.io/badge/Email-burhancabiroglu97%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:burhancabiroglu97@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-burhancabiroglu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/burhancabiroglu)

</div>

---

## What I Focus On

- Backend services with Java, Spring Boot, C#, .NET, Node.js, REST APIs, GraphQL, CQRS, and MediatR
- Distributed systems with RabbitMQ, event-driven flows, offline synchronization, and recovery mechanisms
- Databases with PostgreSQL, MySQL, schema design, query optimization, and transaction-oriented workflows
- Production delivery with Docker, Jenkins, CI/CD, Git workflows, structured logging, Serilog, and ELK
- AI developer work: LLM-ready APIs, async AI jobs, retrieval workflows, automation, observability, and backend foundations for intelligent products

## Current Work

I am currently building production backend services with C#, .NET, PostgreSQL, MySQL, RabbitMQ, Jenkins, and React. My recent work includes asynchronous communication flows, offline sync and recovery mechanisms, CI/CD automation, and structured logging for production troubleshooting.

Previously, I worked on financial applications across banking, factoring, international banking, marketplace, and enterprise platforms.

## Featured Systems

| Project | What it shows | Stack |
| --- | --- | --- |
| [Ticket Microservice](https://github.com/burhancabiroglu/TicketMicroservice) | Java microservices, service discovery, async messaging, mail flows, and containerized infrastructure | Java, Spring Boot, Eureka, Spring Security, RabbitMQ, Docker, PostgreSQL |
| [Cabir CRM](https://github.com/burhancabiroglu/cabir-crm) | Full-stack CRM with clean backend structure, auth, CQRS, and production-style deployment thinking | Next.js, TypeScript, .NET 8, PostgreSQL, MediatR, CQRS, JWT |
| [Transportation Server System](https://github.com/burhancabiroglu/transport-reservation-server) | Reservation backend with authentication and operational data flows | TypeScript, NestJS, PostgreSQL, JWT, React, Docker |

## Flagship Direction

The next public project I am shaping is a larger, real microservice application: an AI-assisted commerce and operations platform with identity, catalog, order, payment, notification, recommendation, and observability services.

The goal is to demonstrate production-grade backend thinking: service boundaries, RabbitMQ events, PostgreSQL ownership per service, Docker Compose local infrastructure, gateway routing, structured logs, and AI workflows that run asynchronously instead of blocking user-facing APIs.

## Architecture Snapshot

```mermaid
flowchart LR
    Web["Web / Mobile Client"] --> Gateway["API Gateway"]
    Gateway --> Identity["Identity Service"]
    Gateway --> Catalog["Catalog Service"]
    Gateway --> Order["Order Service"]
    Order --> Payment["Payment Service"]
    Order --> MQ["RabbitMQ Event Bus"]
    MQ --> Notification["Notification Service"]
    MQ --> AI["AI Recommendation / Assistant Jobs"]
    Catalog --> CatalogDb[("Catalog DB")]
    Order --> OrderDb[("Order DB")]
    Payment --> PaymentDb[("Payment DB")]
    AI --> Vector[("Vector Store")]
    Notification --> Observability["Logs / Metrics / Traces"]
```

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,dotnet,cs,ts,js,nodejs,nestjs,react,nextjs,postgres,mysql,rabbitmq,docker,git,githubactions,jenkins,aws" alt="Tech stack icons" />
</p>

## AI Backend Mini-Game

I am experimenting with a browser mini-game that turns microservice operations into a playable system: route traffic, scale services, handle incidents, and use AI-assisted automation before latency burns the platform down.

Play it here after GitHub Pages is enabled:

**https://burhancabiroglu.github.io/burhancabiroglu/game/**

## GitHub Activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=burhancabiroglu&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="Burhan Cabiroglu GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=burhancabiroglu&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Most used languages" />
</p>

## Open To

- Backend Software Engineer roles
- Java / Spring Boot backend roles
- Distributed systems, financial systems, and production platform teams
- International relocation opportunities
