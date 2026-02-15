# 👋 Hi, I'm Kaylee McLaren

**Backend Software Engineer** | Python, AWS & Event-Driven Systems | Cape Town, South Africa

I build scalable backend systems for fintech applications, specializing in event-driven microservices, serverless architectures, and infrastructure as code.

📧 [mclaren.kaylee@gmail.com](mailto:mclaren.kaylee@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/software-dev-kaylee-mclaren/)  
🌍 Cape Town, South Africa | Open to remote opportunities

---

## 🚀 What I Do

I design and deploy backend systems with a focus on reliability, scalability, and maintainability. My experience spans production fintech systems, cloud infrastructure management, and building proof-of-concept architectures to explore distributed systems patterns.

**Recent Work:**
- Built production systems serving 30+ savings groups (500+ members) in Uganda as part of 4-person engineering team
- Independently managed AWS infrastructure with Terraform (30+ resources across staging/production)
- Created automated dashboard reducing operational overhead by 85%
- Developed onboarding automation reducing setup time from 2 hours to 5 minutes

**Current Focus:** 
- Exploring distributed systems patterns (event choreography, saga patterns)
- Expanding into JVM ecosystem (Kotlin/Spring Boot)
- Building portfolio projects that demonstrate production-grade architecture

---

## 🏆 Featured Project: Serverless Fintech Ecosystem

**[🔗 Live Demo](https://d18l23eogq3lrf.cloudfront.net/)** | **[📂 Repository](https://github.com/KayleeMcLaren/Serverless-Fintech-Ecosystem)**

A complete event-driven microservices platform built to understand production patterns for scalable fintech systems.

### What It Demonstrates

✅ **Event-Driven Architecture** - 6 microservices communicating via AWS SNS (Saga pattern)  
✅ **Infrastructure as Code** - Multi-environment Terraform with workspace isolation  
✅ **Security** - JWT authentication with AWS Cognito on 20+ endpoints  
✅ **Workflow Orchestration** - KYC process using AWS Step Functions  
✅ **Financial Correctness** - Atomic transactions via DynamoDB TransactWriteItems  
✅ **Testing & CI/CD** - Pytest suite with Moto + GitHub Actions automation

### Architecture Highlight

This project uses event choreography where services publish events to SNS topics and subscribers react independently. For example, when a loan is approved, the loan service publishes an event—the wallet service subscribes and funds the account automatically. This decouples services and enables independent scaling.

**Why I built it this way:** At my day job, I worked on Lambda-based systems but didn't architect the overall event-driven patterns. This project let me design the complete system architecture from scratch to understand trade-offs between choreography vs. orchestration, eventual consistency challenges, and idempotency requirements.

**Tech Stack:** Python 3.12, AWS (Lambda, API Gateway, SNS, Step Functions, DynamoDB, Cognito), Terraform, React, CloudFront

---

## 💳 Also Check Out: Payment Service (Kotlin)

**[📂 Repository](https://github.com/KayleeMcLaren/Payment-Service)**

RESTful payment microservice built with Kotlin + Spring Boot to demonstrate proficiency with JVM-based enterprise patterns.

**Why Kotlin?** My production experience is Python/AWS serverless. I built this to understand JVM-based microservices architecture commonly used in enterprise fintech—dependency injection with Spring, ORM patterns with JPA/Hibernate, and Kotlin's type safety compared to Python's dynamic typing.

**Highlights:**
- Spring Data JPA with H2 database
- Payment lifecycle state management
- Comprehensive testing (JUnit 5 + MockK)
- Service-repository pattern

**Tech Stack:** Kotlin, Spring Boot, Spring Data JPA, H2, Gradle, JUnit, MockK

---

## 🛠️ Tech Stack

**Languages:** Python (Expert) • Kotlin (Proficient) • JavaScript/TypeScript • SQL

**Backend & Cloud:** AWS (Lambda, DynamoDB, Step Functions, SNS/SQS, API Gateway, Cognito) • Spring Boot • FastAPI • Flask

**DevOps & IaC:** Terraform • Docker • Git • GitHub Actions • CI/CD

**Practices:** Event-Driven Architecture • Microservices • Infrastructure as Code • TDD • Agile

---

## 📊 Current Projects & Learning

🔭 **Currently:** Exploring Kafka for event streaming (understanding alternatives to SNS/SQS at scale)  
🌱 **Learning:** FastAPI for high-performance Python APIs, Kubernetes for container orchestration  
💡 **Interested in:** Platform engineering, financial infrastructure, distributed systems at scale

---

## 💼 Work Experience

**Junior Software Engineer @ AIMLScore** (Oct 2023 - Dec 2025)  
Part of 4-person team building microfinance platform for rural Uganda.

**Individual ownership:**
- Built production React dashboard (sole developer)
- Managed all Terraform infrastructure (30+ AWS resources)
- Created automated onboarding system (96% time reduction)

**Team contributions:**
- Implemented Lambda functions for loan lifecycle under senior developer guidance
- Participated in DynamoDB schema design for multi-tenant patterns
- Collaborated on production observability and monitoring

---

## 📫 Let's Connect

I'm interested in backend engineering roles where I can work on scalable systems, contribute to meaningful products, and continue growing my distributed systems expertise.

**Email:** mclaren.kaylee@gmail.com  
**LinkedIn:** [linkedin.com/in/software-dev-kaylee-mclaren](https://www.linkedin.com/in/software-dev-kaylee-mclaren/)  
**Location:** Cape Town, South Africa (Open to remote)  
**Status:** Currently seeking new opportunities

---
