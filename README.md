# Phạm Hồ Đăng Huy (Zohanubis)

<div align="center">

![Typing SVG](<https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Fullstack+Software+Engineer;Cloud+Solutions+Architect+(AWS);Building+Scalable+Systems;From+Concept+to+Production>)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20Me-Anything-1abc9c.svg)](mailto:zohanubis.work@gmail.com)
[![Open to Work](https://img.shields.io/badge/Open%20To-Work-green.svg)](https://www.linkedin.com/in/zohanubis)

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%" alt="separator" />
</div>

## 👨‍💻 About Me

> **"I don't just write code; I engineer solutions."**

I am a **Fullstack Software Engineer** with over **1 year of professional experience** in designing, developing, and deploying high-performance web applications. My expertise spans the entire software development lifecycle—from crafting responsive Frontend interfaces to architecting robust Backend microservices and managing cloud infrastructure on **AWS**.

I have successfully delivered multiple outsourcing projects, transforming complex client requirements into production-ready systems. I specialize in building **Microservices**, implementing **DevOps** pipelines, and optimizing cloud resources for cost and performance.

### 🚀 Core Competencies

- **Fullstack Development:** Seamless integration of modern Frontends (Next.js, React) with powerful Backends (NestJS, Spring Boot).
- **Cloud & DevOps:** Extensive experience deploying and managing applications on **AWS** (EC2, S3, RDS, Lambda) using **Docker** and **Kubernetes**.
- **System Architecture:** Proven ability to design scalable, event-driven, and microservices-based architectures.

---

## 💼 Work Experience

| Role                            | Organization / Type         | Period         | Key Responsibilities                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| :------------------------------ | :-------------------------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Fullstack Software Engineer** | **Freelance / Outsourcing** | 2024 - Present | • Delivered **end-to-end web solutions** for diverse clients, handling everything from UI/UX implementation to Backend logic and Database design.<br>• Deployed and maintained production environments on **AWS**, ensuring 99.9% uptime.<br>• Optimized application performance, reducing API latency by **40%** through caching (Redis) and database indexing.<br>• Integrated 3rd-party services (Payment Gateways, OAuth, Google Maps) to enrich application functionality. |
| **Software Engineer**           | **Graduation Project**      | 2025           | • Graduated with an **Engineer's Degree** in Software Engineering.<br>• Lead Developer for capstone projects focusing on Enterprise Resource Planning (ERP) and Smart Education systems.                                                                                                                                                                                                                                                                                        |

---

## 🛠️ Technical Arsenal

### 🌐 Frontend & UI

![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)

### ⚙️ Backend & API

![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=grpc&logoColor=white)

### ☁️ Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

### 🗄️ Databases & Caching

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)

---

## 🏆 Featured Projects

<details open>
<summary><h3>✨ HUIT-EDU – EdTech Microservices Ecosystem (2024)</h3></summary>

> _A comprehensive education management platform built with microservices architecture to handle high-concurrency requests._

**Role:** Solution Architect & Fullstack Developer

#### 🏗️ System Architecture

```mermaid
graph TB
    Client[Web / Mobile Client] -->|HTTPS| API[API Gateway]

    subgraph "Microservices Cluster"
        API -->|gRPC| Auth[Auth Service]
        API -->|gRPC| Student[Student Service]
        API -->|gRPC| Course[Course Service]
        API -->|Event| Notif[Notification Service]
    end

    subgraph "Data Persistence"
        Student --> Mongo[(MongoDB)]
        Course --> Postgres[(PostgreSQL)]
        Auth --> Redis[(Redis Cache)]
    end

    subgraph "External Integration"
        Notif --> FCM[Firebase Cloud Messaging]
        Auth --> OAuth[Google/Facebook Auth]
    end
```

**Key Highlights:**

- **Scalability:** Designed independent services communicating via **gRPC** for low-latency internal networking.
- **Event-Driven:** Implemented **Apache Kafka** to handle asynchronous tasks like grade processing and mass notifications.
- **Deployment:** Containerized with **Docker** and orchestrated using **Kubernetes**, deployed on **AWS EKS**.

</details>

<details>
<summary><h3>✨ Smart Attendance – AI Face Recognition System (2024)</h3></summary>

> _An automated attendance system leveraging AI to streamline classroom management._

**Role:** Backend Lead & Infra Engineer

#### 🔄 User Flow

```mermaid
sequenceDiagram
    participant U as User
    participant F as Frontend
    participant B as NestJS Backend
    participant AI as AWS Rekognition

    U->>F: Scans Face / Uploads Image
    F->>B: Sends Image Stream
    B->>AI: Request Face Matching
    AI-->>B: Returns Match Confidence > 95%
    B->>B: Mark Attendance in DB
    B-->>F: Success Response
    B->>U: Push Notification (Firebase)
```

**Key Highlights:**

- **AI Integration:** Seamless integration with **AWS Rekognition** for <1s face verification.
- **Real-time:** Used **Socket.io** to update attendance dashboards instantly for teachers.
- **Security:** Implemented secure signed URLs for S3 bucket access to protect student data.

</details>

---

## 🏅 Honors & Awards

| Year     | Award                    | Description                                                                                    |
| :------- | :----------------------- | :--------------------------------------------------------------------------------------------- |
| **2025** | 🥈 **2nd Prize**         | **Digital Transform Challenge** - Recognized for innovative use of Microservices in Education. |
| **2025** | 🏆 **National Finalist** | **S.M.A.C Challenge** - Top 10 teams nationwide.                                               |
| **2024** | 🥇 **Excellent Degree**  | Graduated with honors in Software Engineering.                                                 |

---

## 📊 Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Zohanubis&show_icons=true&theme=ocean_blue&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zohanubis&layout=compact&theme=ocean_blue&hide_border=true&langs_count=8" width="48%" />
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Zohanubis&theme=flat&no-frame=true&margin-w=4" />
</div>

---

<div align="center">
  
  ### 📬 Let's Collaborate!
  
  *I am currently open to new opportunities. If you need a scalable solution or a reliable engineer, hit me up!*
  
  [![Email](https://img.shields.io/badge/Email-Zohanubis.work%40gmail.com-c0392b?style=for-the-badge&logo=gmail)](mailto:zohanubis.work@gmail.com)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/zohanubis)
  [![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Site-10ac84?style=for-the-badge&logo=firefox)](https://zohanubis.github.io)
  
  <br>

  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" alt="separator" />
  
  <p>© 2025 Designed by Zohanubis</p>

</div>
