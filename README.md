![header](https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&text=Kaylee%20McLaren%20|%20Fintech%20Cloud%20Engineer&fontSize=35&strokeWidth=0&descAlign=0&descAlignY=0&reversal=false&fontAlign=50&fontAlignY=40)

# 👋 Hi, I'm Kaylee

For me, software development is a creative act, whether I'm building a compelling proof-of-concept for an investor or a simple, intuitive feature for a user. I love learning new technologies and thrive on the challenge of building something impactful from the ground up.

This philosophy is at the heart of my work as a Software Developer for a South African fintech startup, where we're on a mission to bring vital digital services to underserved rural communities in Africa.

This [**Serverless Fintech Ecosystem**](https://github.com/KayleeMcLaren/Serverless-Fintech-Ecosystem) is my core portfolio project. It's my playground for exploring these ideas and building a complete, event-driven system from scratch using AWS, Python, and Terraform.

---

### 🚀 My Core Project: A Serverless Fintech Ecosystem

**[Live Demo Link](https://d18l23eogq3lrf.cloudfront.net/)**

This is a multi-service project designed to showcase a practical understanding of event-driven fintech architecture and Infrastructure as Code. Each component is an independent microservice that communicates via events.

## ✅ Project Status: Complete

| Service | Status | Description |
| :--- | :---: | :--- |
| **Frontend UI (React)** | ✅ | A React SPA with a full UI for all backend services. |
| **Digital Wallet API** | ✅ | Core ledger service. Manages user balances and all transactions. |
| **Micro-Loan System** | ✅ | Manages loan applications, approvals, rejections, and repayments. |
| **Payment Simulator** | ✅ | Asynchronous, event-driven payment processing saga. |
| **Savings Goal Manager** | ✅ | Manages CRUD for savings goals and handles atomic fund transfers. |
| **Debt Repayment Optimiser** | ✅ | Algorithmic calculator for "Avalanche" vs. "Snowball" payoff plans. |

---

## 🛠️ Tech Stack
My primary focus for this ecosystem includes:

### Backend & DevOps
* **Infrastructure as Code:** **Terraform** (with `stg` & `prd` Workspaces)
* **Serverless Compute:** **AWS Lambda** (Python 3.12)
* **API:** **AWS API Gateway** (REST API)
* **Database:** **AWS DynamoDB** (including Global Secondary Indexes - GSIs)
* **Event-Driven Messaging:** **AWS SNS** (with Subscription Filter Policies)
* **CI/CD:** **GitHub Actions** (for `pytest` and `terraform validate`)

### Frontend
* **Framework:** **React** (with React Hooks & Context API)
* **Hosting:** **AWS S3** (Static Website Hosting)
* **CDN & Delivery:** **AWS CloudFront** (with OAC)
* **UI/Styling:** **Tailwind CSS**
* **Data Visualization:** **Recharts**
* **Notifications:** **React Hot Toast**

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

## 🔮 Future Enhancements
With the core ecosystem complete, the next major feature in development will be:

1. **KYC & Onboarding Orchestrator:** Architecting a new microservice using AWS Step Functions to manage a multi-step, stateful user onboarding and KYC (Know Your Customer) workflow. This will act as a gatekeeper before a wallet can be created.

2. **User Authentication:** Implementing AWS Cognito to manage user sign-up, sign-in, and secure all API Gateway endpoints with a JWT authorizer.

---

## 📫 Let's Connect
**Kaylee McLaren**
Software Developer | Fintech | AWS & Python Enthusiast
-   💼 [LinkedIn](https://www.linkedin.com/in/software-dev-kaylee-mclaren/)
-   🐍 [GitHub Projects](https://github.com/KayleeMcLaren?tab=repositories)
-   ✉️ Email: mclaren.kaylee@gmail.com

I love the challenge of building reliable and impactful fintech apps on AWS. I'm currently focused on coding event-driven backends, mastering AWS serverless, and using data to build smarter tools.
