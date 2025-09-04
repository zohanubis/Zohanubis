# Phạm Hồ Đăng Huy (Zohanubis)

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Welcome+to+my+profile!;Pham+Ho+Dang+Huy+-+Zohanubis;Software+Engineer+%7C+Microservices+%7C+Cloud+DevOps)

![Wave Banner](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

</div>

## 🚀 Quick Navigation

<div align="center">

[![Contact](https://img.shields.io/badge/📬-Contact-blue?style=for-the-badge&logo=gmail)](mailto:zohanubis.work@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼-LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/zohanubis)
[![GitHub](https://img.shields.io/badge/💻-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/zohanubis)
[![Portfolio](https://img.shields.io/badge/🎯-Portfolio-FF6B6B?style=for-the-badge&logo=firefox)](https://zohanubis.github.io)

</div>

---

## 📋 Table of Contents

| Section | Quick Links |
|---------|-------------|
| 🎓 **Education** | [Jump to Education](#-education) |
| 🚀 **Tech Stack** | [Jump to Tech Stack](#-tech-stack) |
| 🏆 **Projects** | [Jump to Projects](#-projects) |
| 🏅 **Achievements** | [Jump to Achievements](#-achievements) |
| 📊 **Stats** | [Jump to Stats](#-stats) |
| 📬 **Contact** | [Jump to Contact](#-contact) |

> **💡 Tip:** Press <kbd>Ctrl</kbd> + <kbd>F</kbd> to search quickly!

---

## 👨‍💻 About Me

> **Hi! I'm Pham Ho Dang Huy, a fourth-year Software Engineering student with a strong passion for back-end development, microservices, and cloud-native solutions. I love building scalable, maintainable systems and always strive for clean code and best practices. Currently, I'm seeking an internship to further hone my skills and gain real-world experience in software development.**

### 🌱 Specializations

- **Back-end Development** | **Microservices Architecture** | **Cloud & DevOps**

---

## 🎓 Education

| Institution | Program | Duration | Status |
|-------------|---------|----------|---------|
| **Ho Chi Minh City University of Industry and Trade** | Software Engineering | 2021 - Present | 🎓 **4th Year Student** |

---

## 🚀 Tech Stack

### 🌐 Web & Backend

<div align="center">

![NextJS](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Express](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)

  </div>

### ☁️ DevOps & Cloud

<div align="center">

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat-square&logo=firebase&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)

  </div>

### 🗄️ Databases

<div align="center">

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=prisma&logoColor=white)

</div>

---

## 🏆 Projects

### 🎯 Featured Projects

<details>
<summary><b>✨ HUIT-EDU (2024)</b> - Microservices Education Management System</summary>

#### 🏗️ Architecture Overview

```mermaid
graph TB
    A[Frontend - Next.js] --> B[API Gateway]
    B --> C[Student Service]
    B --> D[Course Service]
    B --> E[Attendance Service]
    B --> F[Notification Service]
    
    C --> G[(MongoDB)]
    D --> H[(PostgreSQL)]
    E --> I[(Redis)]
    F --> J[Firebase FCM]
    
    K[gRPC] --> C
    K --> D
    K --> E
    
    L[Kafka] --> M[Event Bus]
    M --> N[Analytics Service]
```

#### 🛠️ Tech Stack (HUIT-EDU)

- **Frontend:** Next.js 15+, React 19, TypeScript, Tailwind CSS
- **Backend:** NestJS 11+, Microservices, gRPC, KafkaJS
- **Infrastructure:** Docker, Nx Monorepo, AWS

#### 🚀 Key Features (HUIT-EDU)

- ✅ Microservices architecture with gRPC communication
- ✅ Real-time notifications with Firebase FCM
- ✅ Event-driven architecture with Kafka
- ✅ Comprehensive student and course management

*Architecture diagram rendered with Mermaid[^3]*

  </details>

  <details>
<summary><b>✨ Edu Attendance (2024)</b> - Smart Attendance System</summary>

#### 🏗️ System Flow

```mermaid
sequenceDiagram
    participant S as Student
    participant A as Attendance App
    participant B as Backend API
    participant R as AWS Rekognition
    participant N as Notification Service
    
    S->>A: Scan QR Code
    A->>B: Submit Attendance
    B->>R: Face Recognition
    R-->>B: Verification Result
    B->>N: Send Notification
    N-->>S: Attendance Confirmed
```

#### 🛠️ Tech Stack (Edu Attendance)

- **Backend:** NestJS 10+, RabbitMQ, MongoDB, Redis
- **Frontend:** Next.js 15+, Shadcn/UI, TypeScript
- **AI/ML:** AWS Rekognition for face recognition
- **Infrastructure:** Docker Compose, AWS S3

#### 🚀 Key Features (Edu Attendance)

- ✅ Face recognition attendance system
- ✅ Real-time notifications
- ✅ Role-based access control
- ✅ Comprehensive analytics dashboard

*Sequence diagram rendered with Mermaid[^3]*

  </details>

---

## 🏅 Achievements

| Achievement | Year | Description | Certificate |
|-------------|------|-------------|-------------|
| 🥈 **2nd Prize** | 2025 | Academic Competition | [View Certificate](https://res.cloudinary.com/zohanubis/image/upload/fl_preserve_transparency/v1749702002/GiaiNhi-DigtalTransformChallenge._r2csef.jpg?_s=public-apps) |
| 🏆 **Finalist** | 2025 | Academic Competition | [View Certificate](https://res.cloudinary.com/zohanubis/image/upload/fl_preserve_transparency/v1749701985/ChungKet-DigtalTransformChallenge_mr5aw8.jpg?_s=public-apps) |
| 📚 **Participation** | 2025 | Student Scientific Research (Round 1) | [View Certificate](https://res.cloudinary.com/zohanubis/image/upload/fl_preserve_transparency/v1749701986/NCKH-Vong1_kjvskm.jpg?_s=public-apps) |

---

## 📊 GitHub Statistics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Zohanubis&theme=one_dark_pro&hide_border=false&include_all_commits=true&count_private=false&show_icons=true&line_height=20)[^2]
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Zohanubis&theme=one_dark_pro&hide_border=false&include_all_commits=true&count_private=false&layout=compact&langs_count=8)[^2]
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Zohanubis&theme=one_dark_pro&hide_border=false)[^2]

</div>

### 🏆 GitHub Trophies

<div align="center">

![trophy](https://github-profile-trophy.vercel.app/?username=Zohanubis&theme=onedark&no-frame=false&no-bg=false&margin-w=4&row=1&column=7)

</div>

---

*Timeline chart rendered with Mermaid[^3]*

---

## 📬 Contact & Connect

<div align="center">

### 📧 Get in Touch

[![Email](https://img.shields.io/badge/📧-zohanubis.work@gmail.com-red?style=for-the-badge&logo=gmail)](mailto:zohanubis.work@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼-LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/zohanubis)
[![GitHub](https://img.shields.io/badge/💻-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/zohanubis)

### 📍 Location

**Ho Chi Minh City, Vietnam**

### 🎯 Looking For

- 🎓 **Internship opportunities** in Software Engineering
- 🤝 **Collaboration** on open-source projects
- 💼 **Full-time positions** starting 2025

</div>

---

## 💡 Quick Actions

<div align="center">

[![Hire Me](https://img.shields.io/badge/💼-Hire%20Me-00C851?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/zohanubis)
[![View Resume](https://img.shields.io/badge/📄-View%20Resume-FF6B6B?style=for-the-badge&logo=firefox)](https://zohanubis.github.io/resume)
[![Contact Now](https://img.shields.io/badge/📬-Contact%20Now-2196F3?style=for-the-badge&logo=gmail)](mailto:zohanubis.work@gmail.com)

</div>

---

<div align="center">

### 📬 Ready to collaborate? Let's build something amazing together

![Footer](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

*Proudly created with ❤️ by [Zohanubis](https://github.com/zohanubis)*

</div>

---

