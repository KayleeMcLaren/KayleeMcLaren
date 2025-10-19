![header](https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&text=Kaylee%20McLaren%20|%20Fintech%20Cloud%20Engineer&fontSize=35&strokeWidth=0&descAlign=0&descAlignY=0&reversal=false&fontAlign=50&fontAlignY=40)

# 👋 Hi, I'm Kaylee

For me, software development is a creative act, whether I'm building a compelling proof-of-concept for an investor or a simple, intuitive feature for a user. I love learning new technologies and thrive on the challenge of building something impactful from the ground up.

This philosophy is at the heart of my work as a Software Developer for a South African fintech startup, where we're on a mission to bring vital digital services to underserved rural communities in Africa.

This [**Serverless Fintech Ecosystem**](https://github.com/KayleeMcLaren/Serverless-Fintech-Ecosystem) is my core portfolio project. It's my playground for exploring these ideas and building a complete, event-driven system from scratch using AWS, Python, and Terraform.

---

### 🚀 My Core Project: A Serverless Fintech Ecosystem

This is a multi-service project designed to showcase a practical understanding of event-driven fintech architecture and Infrastructure as Code. Each component is an independent microservice that communicates via events.

* **Phase 1: Core Services**
    * ✅ **Digital Wallet API**: The foundational ledger system.
    * ✅ **Micro-Loan Management System**: An event-driven business workflow.
* **Phase 2: Event-Driven Sagas**
    * ✅ **Payment Processing Simulator**: A complex, asynchronous choreography pattern.
* **Phase 3: Personal & Advanced**
    * [ ] **Savings Goal Visualiser**: Customer-facing application logic.
    * [ ] **Debt Repayment Optimizer**: Algorithmic problem-solving.

---

## 🧠 Tech Stack
My primary focus for this ecosystem includes:
-   **Languages:** Python, JavaScript (React)
-   **Core AWS Services:** **Lambda, API Gateway, DynamoDB (GSI), SNS, S3, CloudFront**
-   **Infrastructure as Code:** **Terraform** (managing all resources across multiple modules)
-   **Architecture:** **Event-Driven Microservices,** Asynchronous Sagas, Decoupled Services
-   **Frontend:** React, TailwindCSS

---

## 💼 Featured Fintech Projects
| Project | Description | Tech Highlights |
| :--- | :--- | :--- |
| 💳 **Digital Wallet API** | Serverless wallet for creating accounts, checking balances, and processing atomic credit/debit transactions. | **AWS Lambda, API Gateway, DynamoDB** |
| 💰 **Micro-Loan System** | Event-driven system to apply for, approve, and reject micro-loans. An approval publishes an event to SNS. | **Lambda, DynamoDB (GSI), SNS**. The `digital_wallet` service subscribes to "approval" events to fund the wallet, decoupling the services. |
| 💵 **Payment Simulator** | Simulates an asynchronous payment saga between a user and a merchant using event choreography. | **Lambda, SNS, DynamoDB**. A `POST` to `/payment` publishes an event. SNS filter policies route events to different Lambdas for processing ("debit wallet" vs. "update status"). |
| 📊 **Savings Goal Visualiser** | Visual budgeting and savings tracker. | (In Progress) **React, S3/CloudFront, Lambda, API Gateway** |
| 📉 **Debt Repayment Optimizer** | Suggests optimal repayment strategies (e.g., "Snowball" vs. "Avalanche") based on user's loan data. | (Future) **Python, Lambda, API Gateway, React** |

---

## 🚀 What I'm Working On
Building a **Fintech Cloud Portfolio** showcasing AWS serverless architectures and scalable, event-driven backend systems.

Currently developing: **Savings Goal Visualiser** 📊

---

## 📫 Let's Connect
**Kaylee McLaren**
Software Developer | Fintech | AWS & Python Enthusiast
-   💼 [LinkedIn](https://www.linkedin.com/in/software-dev-kaylee-mclaren/)
-   🐍 [GitHub Projects](https://github.com/KayleeMcLaren?tab=repositories)
-   ✉️ Email: mclaren.kaylee@gmail.com

Passionate about building reliable, scalable, and impactful cloud-native fintech applications.
Currently focused on backend systems, AWS serverless solutions, and data-driven decision tools.
