<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-4F0599?style=for-the-badge&logo=About.me&logoColor=white)](https://trafost.github.io/personal-profile)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rahwisdilfiqrak)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahmannrdn/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahmannurudin29@gmail.com)
</div>

## About Me

Fullstack developer focused on building end-to-end systems.
Recently shifted deeper into backend work: chat infrastructure, background workers, AI pipelines, caching, and event-driven architecture.

---

## Featured Projects

### **Marmalade – Voice-First Emotional Companion (AI Partner Catalyst: Accelerate Innovation)**
Developed the complete **real-time AI infrastructure** for an emotional support agent that leverages multi-modal inputs to detect risk, evaluate mood, and deliver personalized counseling.
- Designed the **end-to-end architecture**, orchestrating real-time voice streaming (ElevenLabs) alongside dual-model inference (Gemini Flash for rapid scoring, Gemini Pro for counseling).
- Engineered the **backend system** on Cloud Run, implementing secure session state management, authentication, and persistent storage with PostgreSQL and Drizzle.
- Implemented a **multi-stage AI pipeline** that performs real-time emotional analysis and risk detection to ensure safety guardrails before generating adaptive voice responses.
- Built the **contextual memory engine**, utilizing vector embeddings and session summarization to maintain conversation continuity and personalized user history across interactions.

**Stack:** Node.js, Google Cloud Run, PostgreSQL, Drizzle ORM, Vertex AI (Gemini Flash/Pro, Embeddings), ElevenLabs Realtime, Cloud Storage

### **Orchestor – Agentic Social Media Scheduler (IBM watsonx Orchestrate Hackathon 2025)**
Built the full **backend and AI orchestration layer** for an agentic system that converts raw Asana social-media tasks into validated schedules and repost recommendations.
- Designed the **end-to-end architecture**, mapping how CSV/XLSX data moves from frontend parsing into backend normalization and finally into the Orchestrate agent.  
- Implemented the **backend** with Hono.  
- Integrated **IBM watsonx Orchestrate** using a custom JSON contract that drives multi-step agent reasoning for captions, validation, post-type classification, and scheduling.  
- Built the agent’s **knowledge base**, combining brand guidelines, product features, rule logic, historical posting data, and a formal prompt spec for deterministic output.  
- Delivered the entire **reasoning pipeline**, ensuring stable, machine-readable JSON for the frontend preview experience.

**Stack:** Hono, Cloudflare Workers, TypeScript, IBM watsonx Orchestrate

### **LoLo – AI League Coach (Rift Rewind Hackathon 2025)**
Led the full development of **LoLo**, a League of Legends companion that uses AWS Bedrock to analyze player performance and deliver reflective insights.  
- Designed the **overall architecture**, defining how data flows between Riot API, AI analysis, and the frontend.  
- Built the **backend** with Hono, AWS Lambda, SST, and S3.  
- Worked on **AI reasoning pipelines** powered by Bedrock for player insights and pro comparisons.  
- Contributed to **frontend integration**, ensuring smooth data handling and consistency across the app.  
**Stack:** Hono, AWS Lambda, S3, Bedrock, React, Vite, Tailwind  

---

### **BIMTranslator – AI Sign Language Translator (PAN AI Singapore Hackathon 2025)**  
Worked on the **frontend** for an AI-powered translator that converts Malay Sign Language into text in real time.  
- Built a responsive **gesture recognition interface** using TensorFlow.js and MediaPipe.  
- Integrated **PAN AI LLMs** for contextual text generation and improved translation accuracy.  
- Deployed via **GCP Cloud Run** for seamless browser-based interaction.  
**Stack:** React, TensorFlow.js, MediaPipe, GCP, PAN AI LLMs  

---

### **Ruang Diri – Mental Health Counseling Platform (Professional Work)**  
Core engineer for a counseling platform connecting clients with psychologists.  
- Built the backend with **NestJS** and **PostgreSQL (Drizzle ORM)**.  
- Added **real-time chat** with presence, file sharing, and unread tracking using Ably.  
- Integrated **Zoom automation**, notifications, and background jobs with Bull + Redis.  
- Containerized and deployed the app on **GCP Cloud Run** using Docker.
- Added **retry logic** and monitoring to background tasks.  
**Stack:** NestJS, PostgreSQL (Drizzle), Redis, BullMQ, Ably, React

---


## Skills & Technologies

<div align="center">

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend

![Nest.js](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-000000?style=for-the-badge&logo=hono&logoColor=orange)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Databases

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### State Management & APIs

![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

### Styling & UI

![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MaterialUI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

### Cloud & Infrastructure

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Testing & Optimization

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Lighthouse](https://img.shields.io/badge/Lighthouse-F44B21?style=for-the-badge&logo=lighthouse&logoColor=white)

</div>

## GitHub Activity

<div align="center" style={"display": "flex", "align-items": "center", "justify-content": "center"}>
  <img src="https://github-readme-stats.vercel.app/api?username=trafost&show_icons=true&theme=radical" alt="Rahman's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=trafost&theme=radical" alt="Rahman's GitHub Streak" />
</div>
<div align="center">
<img src="https://komarev.com/ghpvc/?username=trafost&style=flat-square&color=blueviolet" alt="Profile views" />
</div>

---
