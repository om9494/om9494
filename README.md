# 👋 Hey, I'm Om Panchal

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&center=true&vCenter=true&width=700&lines=Backend+Engineer+in+the+Making+%F0%9F%9A%80;Java+%7C+Spring+Boot+%7C+AWS+%7C+Docker;I+Design+Systems%2C+Not+Just+APIs;Competitive+Programmer+%7C+Builder+%7C+Problem+Solver" />
</p>

<p align="center">
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"/>
  </a>
  <a href="YOUR_PORTFOLIO_URL">
    <img src="https://img.shields.io/badge/Portfolio-Visit-black?style=for-the-badge&logo=vercel"/>
  </a>
  <a href="mailto:om4499panchal@gmail.com">
    <img src="https://img.shields.io/badge/Email-Let's%20Talk-red?style=for-the-badge&logo=gmail"/>
  </a>
</p>

---

## 🧠 A Little About Me

I'm a **Computer Engineering student at MIT Academy of Engineering, Pune**, who enjoys going beyond "making it work" and figuring out **how to make it scale, survive concurrency, and behave correctly under failure**.

My sweet spot is **backend engineering + cloud infrastructure + system design**.

```text
┌──────────────────────────────────────────────────────────┐
│                    WHAT I LIKE BUILDING                  │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  ⚙️  Scalable Backend Systems                            │
│  🔄  Concurrent & Distributed Workflows                  │
│  ☁️  Cloud-Native Applications                           │
│  🐳  Containerized Infrastructure                        │
│  🧩  REST APIs & Microservices                           │
│  🗄️  Database-Driven Systems                             │
│  🤖  RAG / LLM Applications                              │
│  🧠  DSA & Problem Solving                               │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

Currently, I'm particularly interested in **Java/Spring Boot, AWS, distributed systems, concurrency, and system design**.

---

# ⚡ Quick Snapshot

<p align="center">

| 🏆                  | 📊                    | ☁️             | 💻                      |
| ------------------- | --------------------- | -------------- | ----------------------- |
| **SIH 2024 Winner** | **400+ DSA Problems** | **AWS**        | **Backend Engineering** |
| National Level      | LeetCode + Codeforces | Cloud & DevOps | Java / Spring Boot      |

</p>

🎓 **B.Tech Computer Engineering** — MITAOE Pune
💼 **Software Development Intern** — Parma IT Solutions
🏆 **Smart India Hackathon 2024 — National Winner**
🏆 **Datathon 2025 — Winner**
🏆 **Industry Institute Future Summit 2026 — Winner**

---

# 🔥 What I've Been Building

## 🎬 ShowTime

### `A movie booking system where concurrency actually matters.`

Most booking systems look simple until **multiple users try to book the same seat at exactly the same time**.

That's where things get interesting.

I built ShowTime with a focus on:

```text
User
  │
  ▼
Seat Selection
  │
  ├──────────────► Concurrent Requests
  │                       │
  ▼                       ▼
Booking Service ───► Conflict Handling
  │
  ▼
Payment
  │
  ▼
Razorpay
  │
  ▼
Confirmed Booking
```

### Engineering Focus

* ⚡ Concurrent multi-user seat selection
* 🔒 Booking conflict handling
* 💳 Razorpay payment integration
* ☕ Java + Spring Boot backend
* 🗄️ PostgreSQL query optimization
* ☁️ AWS infrastructure
* 🔄 CI/CD using AWS CodePipeline
* 📊 CloudWatch monitoring
* 🐳 Dockerized deployment

**Stack**

`Java` `Spring Boot` `PostgreSQL` `Razorpay` `AWS` `Docker` `CI/CD`

---

## 💰 Real-Time Crypto Trading & Wallet System

### `Because trading is basically a concurrency problem disguised as finance.`

Built an event-driven backend capable of processing **concurrent trading operations** while maintaining data consistency.

```text
                  ┌──────────────┐
Buy Order ───────►│              │
                  │ Order Engine │──────► PostgreSQL
Sell Order ──────►│              │
                  │              │
Wallet ──────────►│              │
                  └──────┬───────┘
                         │
                    Synchronization
                         │
                  Race Condition
                     Prevention
```

### What I worked on

* 🧵 Multi-threaded asynchronous order handling
* 🔐 Thread-safe synchronization
* ⚡ Event-driven backend architecture
* 💹 CoinGecko API integration
* 💳 Razorpay integration
* 🐳 Docker containerization
* ☸️ Kubernetes deployment
* ☁️ AWS deployment

**Stack**

`Java` `Spring Boot` `PostgreSQL` `Docker` `Kubernetes` `AWS`

---

# 🤖 AI × RAG × Real Problems

## Admission Chat Engine

### 🏆 Smart India Hackathon 2024 — National Winner

What started as a problem statement became a **national-level winning project**.

We built an AI-powered admission platform capable of retrieving relevant information from institutional datasets and generating context-aware responses using **RAG + LLMs**.

### Architecture

```text
                  User
                   │
                   ▼
             React Frontend
                   │
                   ▼
             REST API Layer
                   │
                   ▼
            Retrieval Layer
                   │
          ┌────────┴────────┐
          ▼                 ▼
     Vector Search      Institutional
                         Dataset
          │
          ▼
          LLM
          │
          ▼
   Context-Aware Answer
```

### My Role

👨‍💼 **Team Lead — 6 Members**

I coordinated the team throughout the development lifecycle, from **design → implementation → integration → delivery**.

**Stack**

`React.js` `Node.js` `Express.js` `MongoDB` `RAG` `LLMs` `Vector Retrieval`

---

# 🏗️ How I Think About Engineering

I don't just ask:

> **"Does the API work?"**

I like asking:

```text
What happens when 10,000 users call it?

What happens when two requests modify the same resource?

What happens when the database is slow?

What happens when payment succeeds but booking fails?

What happens when a service crashes?

Can we observe the failure?

Can we recover safely?

Can we scale it horizontally?
```

That's why I'm spending a lot of time learning:

**System Design → Distributed Systems → Concurrency → Cloud Architecture → DevOps**

---

# 🛠️ My Engineering Toolbox

### Backend

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="55"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="55"/>
</p>

`Java` `Spring Boot` `Node.js` `Express.js` `REST APIs` `Microservices`

### Databases

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="50"/>
</p>

`PostgreSQL` `MySQL` `MongoDB`

### Cloud & DevOps

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="65"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="55"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" width="50"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" width="50"/>
</p>

`AWS` `Docker` `Kubernetes` `Jenkins` `CI/CD`

### Frontend

`React.js` `JavaScript` `HTML5` `CSS3`

### Fundamentals

`DSA` `OOP` `DBMS` `Operating Systems` `Computer Networks` `System Design`

---

# ☁️ AWS Playground

I've worked with:

```text
EC2          S3             RDS
VPC          SQS            Lambda
CloudFront   Elastic Beanstalk
CloudFormation
CodePipeline CodeBuild      CodeDeploy
CloudWatch   SNS            IAM
```

I'm particularly interested in understanding **why a particular AWS service belongs in an architecture**, rather than simply learning service names.

---

# 🧩 Problem Solving

### Competitive Programming

```text
┌──────────────────────────────┐
│       PROBLEM SOLVING        │
├──────────────────────────────┤
│                              │
│   400+ Problems Solved      │
│                              │
│   ⭐ CodeChef — 3 Star       │
│   ⭐ Codeforces — 1200       │
│                              │
│   DSA • Algorithms • CP      │
│                              │
└──────────────────────────────┘
```

I enjoy problems where the obvious solution works for 10 inputs but completely falls apart at **10⁵**.

---

# 🏆 Beyond Code

| Achievement                                  | What it means                  |
| -------------------------------------------- | ------------------------------ |
| 🥇 **Smart India Hackathon 2024**            | National Winner                |
| 🥇 **Datathon 2025**                         | Winner                         |
| 🥇 **Industry Institute Future Summit 2026** | Winner                         |
| 🏅 **GDG Hackathon**                         | Industry Project Award         |
| 🎓 **Reliance Scholar**                      | 4-Year Engineering Scholarship |
| 🎓 **Super 30 Scholar**                      | MITAOE                         |

---

# 💼 Experience

### Software Development Intern

**Parma IT Solutions · June 2026 – August 2026**

Worked on the backend of a production-facing **Pharmacy ERP system**.

`Node.js` `Express.js` `MongoDB` `REST APIs` `Postman` `Git`

---

# 📚 Currently Learning

```text
                    ┌───────────────────┐
                    │   SYSTEM DESIGN   │
                    └─────────┬─────────┘
                              │
               ┌──────────────┼──────────────┐
               ▼              ▼              ▼
          Distributed     Concurrency      Scalability
            Systems
               │              │              │
               └──────────────┼──────────────┘
                              ▼
                         CLOUD / AWS
                              │
                              ▼
                       PRODUCTION SYSTEMS
```

---

# 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

# 🤝 Let's Build Something

I'm always interested in conversations around:

**Backend Engineering · System Design · Cloud · DevOps · Distributed Systems · AI · Open Source**

If you're building something interesting, let's connect.

<p align="center">

<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="YOUR_PORTFOLIO_URL">
<img src="https://img.shields.io/badge/Portfolio-Explore-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="mailto:om4499panchal@gmail.com">
<img src="https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

<p align="center">

### `Build → Break → Understand → Scale → Repeat.`

⭐ **Thanks for visiting my profile!**

</p>
