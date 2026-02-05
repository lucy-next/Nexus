<div align="center">

<img src="./logo.png" alt="Nexus Logo" width="120" height="auto" />

<h1>N E X U S</h1>

<p>
  <strong>A Fullstack Social Website, that mixes X & Discord.</strong>
</p>

<p>
  <a href="#architecture">Architecture</a> •
  <a href="#status">Status</a> •
  <a href="#tech-stack">Tech Stack</a>
</p>

[![wip](https://img.shields.io/badge/status-work%20in%20progress-lightgrey?style=flat-square)](#)
[![license](https://img.shields.io/badge/license-Custom%20Portfolio-blue?style=flat-square)](https://github.com/lucy-next/Nexus/blob/main/LICENSE)

---

</div>

## Project Purpose

Nexus is a technical **Proof-of-Concept (PoC)** designed to demonstrate proficiency in TypeScript-driven fullstack development. The primary focus of this project is not just "another social clone," but an exercise in building a **robust, scalable architecture** from scratch.

### Separation of Concerns

Unlike many modern Next.js projects that rely solely on Server Actions, Nexus follows the principle of **Security through Server/Client Separation**:

* **Decoupled Backend:** A dedicated **Nest.js API** handles business logic, security, and database interactions.
* **Independent Frontend:** **Next.js** acts purely as a consumer of the API, ensuring that the backend remains platform-agnostic and easier to scale or secure independently.
* **Data Sovereignty:** All content moderation (Text & Image scanning) is handled locally on the server to avoid reliance on external 3rd-party APIs.

---

## Development Status

### Implemented
* Nothing, i just started.

### 🛠️ Planned (In Development)
* **User Accounts:** Secure registration logic and JWT-based authentication.
* **Database Foundation:** Scalable SQL schema using Prisma.
* **Profile Management:** Custom bios, avatars, and account settings.
* **Global Feed:** A Twitter-style timeline with Posts and Comments.
* **Chatrooms:** A Discord-style Group chats with Realtime Chatting via WebSockets.
* **Messaging:** 1:1 Realtime DMs via WebSockets.
* **Local AI Moderation:** Integrate a Filter for local image & text scanning and custom profanity filters.
* **Admin Tools:** Dedicated moderation page for banning users and updating filters.

---

## 🛠️ Tech Stack

**Backend:** <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=flat-square&logo=nestjs&logoColor=white" /> 
<img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white" /> 
<img src="https://img.shields.io/badge/Prisma-%230C344B.svg?style=flat-square&logo=prisma&logoColor=white" />

**Frontend:** <img src="https://img.shields.io/badge/next.js-%23000000.svg?style=flat-square&logo=next.js&logoColor=white" /> 
<img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white" /> 
<img src="https://img.shields.io/badge/shadcn%2Fui-%23000000.svg?style=flat-square&logo=shadcnui&logoColor=white" />

<div align="center">
<br />
<sub>Built with ☕ and TypeScript by Lucy</sub>
</div>
