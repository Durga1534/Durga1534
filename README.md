# 👋 Hey, I'm Durga Prasad

<p align="center">
  <a href="https://durga-prasad-portfolio1.vercel.app/"><img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Now-FF5722?style=for-the-badge"/></a>
  <a href="https://www.linkedin.com/in/durgaprasad23"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:kondurudurgaprasad.2@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Durga1534"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

**Full-Stack Developer** passionate about building modern web applications with **React.js**, **Next.js**, **Node.js**, and **TypeScript**. I enjoy turning ideas into functional products with clean code and intuitive user experiences.

🔍 **Open to remote full-stack/backend roles** | 📍 Based in India

---

## 🚀 Tech Stack

### 💻 Frontend
![React](https://img.shields.io/badge/-React.js-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-black?style=flat-square&logo=next.js)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/-Zustand-000000?style=flat-square&logo=Zustand&logoColor=white)
![Shadcn/UI](https://img.shields.io/badge/-Shadcn/UI-000000?style=flat-square&logo=shadcnui&logoColor=white)

### 🛠 Backend
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/-Express.js-000000?style=flat-square&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20API-ff6f00?style=flat-square&logo=api&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-black?style=flat-square&logo=json-web-tokens)

### 🧠 Languages
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)

### 🗄 Databases
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Appwrite](https://img.shields.io/badge/-Appwrite-F02E65?style=flat-square&logo=appwrite&logoColor=white)

### 🧰 Tools & Platforms
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel)
![Render](https://img.shields.io/badge/-Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Sentry](https://img.shields.io/badge/-Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

---

## Featured Projects

### [JobSense AI](https://github.com/Durga1534/JobSense-AI)
**Autonomous AI Job-Hunting Agent**

AI agent that automates job hunting — searches boards, scores each listing against your resume using Groq AI, and sends the best matches to WhatsApp. Built to solve my own job-search fatigue.

**Tech Stack:** Node.js · TypeScript · QStash · Redis · Groq AI · Twilio · Arcjet · Neon PostgreSQL · Koyeb

**Key Features:**
- QStash drives the background polling queue with guaranteed at-least-once delivery
- Groq AI scores each job listing against resume fit in under 200ms per listing
- Arcjet handles rate limiting and bot protection at the API edge
- Resolved real production issues during build — Groq JSON parsing failures, WhatsApp character limits, and credential rotation after a GitHub push protection incident
- Full production stack deployed at zero infrastructure cost

> No live demo — backend service. See GitHub for architecture and setup.

---

### [Syncro Flow](https://github.com/Durga1534/collab-dashboard) | [Live Demo →](https://syncro-flow-ten.vercel.app)
**Real-Time Collaborative Workspace**

Real-time collaborative workspace where teams manage tasks and see live updates across every connected browser in under 100ms.

**Tech Stack:** Next.js 16 · TypeScript · PostgreSQL · Drizzle ORM · Pusher · Clerk · Zod · Vercel

**Key Features:**
- Every mutation follows a strict pipeline — Zod validation, RBAC membership check, PostgreSQL write, Pusher broadcast, activity log — in a single server action
- Multi-tenant workspaces with three roles (owner, admin, member) enforced server-side on every mutation
- Pusher client and server split into separate modules to prevent SSR bundling crashes at runtime
- Automatic polling fallback every 5 seconds when WebSocket channel drops, with live/polling status badge in the UI
- Clerk webhook syncs users into PostgreSQL automatically on sign-up

---

### [Rate Limiter API Gateway](https://github.com/Durga1534/rate-limiter-api-gateway)
**Distributed Backend Infrastructure**

Production-grade API gateway with Redis-based distributed rate limiting, built to handle sustained traffic with zero downtime.

**Tech Stack:** Node.js · Express.js · TypeScript · Redis · PostgreSQL · Docker Compose · JWT · Pino · Prometheus

**Key Features:**
- Sliding window rate limiting via Redis primitives protects the database from traffic spikes
- Full Docker Compose orchestration — Node.js, PostgreSQL, and Redis in isolated services with environment parity across local and production
- Centralized JWT authentication middleware with structured error handling
- Pino structured logging and Prometheus metrics endpoint configured from day one
- Layered middleware architecture makes the system straightforward to extend and debug

> No live demo — run locally with docker compose up. Full setup in README.

---

### [Converso](https://github.com/Durga1534/my_converso) | [Live Demo →](https://my-converso.vercel.app)
**AI Voice Companion SaaS Platform**

AI voice companion SaaS with real-time audio streaming, multi-tenant data isolation, and subscription-based access control.

**Tech Stack:** Next.js · TypeScript · Vapi AI · Supabase · PostgreSQL · Clerk · Row Level Security · Vercel

**Key Features:**
- PostgreSQL schema designed with Row Level Security so each user can only ever access their own data — enforced at the database level, not the application layer
- Clerk handles the full auth and billing lifecycle from sign-up through subscription management
- Vapi AI powers real-time voice streaming with low-latency audio responses
- Supabase analytics and custom event tracking to understand how users interact with the platform
- Role-based access control gates features by subscription tier

---

> 📌 **[View all repositories →](https://github.com/Durga1534?tab=repositories)**

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Durga1534&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Durga1534&layout=compact&theme=radical&hide_border=true" alt="Top Languages" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Durga1534&theme=radical&hide_border=true" alt="GitHub Streak"/>
</p>

---

## 🧠 Currently Learning & Exploring

- Advanced Next.js patterns (Server Actions, Streaming SSR, Partial Prerendering)
- Docker containerization and orchestration with Kubernetes
- WebSockets and real-time communication (Socket.io)
- CI/CD pipelines with GitHub Actions
- Testing with Jest, React Testing Library, and Playwright
- Cloud deployment strategies (AWS, GCP, Azure)

---

## 📫 How to Reach Me

- 🌐 **Portfolio:** [durga-prasad-portfolio1.vercel.app](https://durga-prasad-portfolio1.vercel.app/)  
- ✉️ **Email:** kondurudurgaprasad.2@gmail.com  
- 💼 **LinkedIn:** [linkedin.com/in/durgaprasad23](https://www.linkedin.com/in/durgaprasad23)  
- 💻 **GitHub:** [github.com/Durga1534](https://github.com/Durga1534)

📍 **Open to remote full-stack/frontend development roles**

---

## 💡 What I Bring to the Table

- ✅ **3+ Full-stack SaaS applications** built from scratch
- ✅ Strong focus on **clean code architecture** and **scalable design patterns**
- ✅ Experience with **modern DevOps practices** (CI/CD, monitoring, error tracking)
- ✅ Passionate about **user experience** and building intuitive interfaces
- ✅ Quick learner with ability to **adapt to new technologies** rapidly

---

## 😄 Fun Facts About Me

- 🍜 **Foodie** who loves exploring new cuisines
- 🎌 **Anime enthusiast** (currently watching: [Dragon ball series])
- 📺 Love binge-watching tech documentaries and series
- ☕ Powered by coffee and curiosity
- 🎮 Casual gamer in my free time

---

<p align="center">
  <i>Thanks for stopping by! Let's build something amazing together.</i> ✨
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Durga1534&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---
