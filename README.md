<div align="center">

<img src="./logo.png" alt="Nexus Logo" width="120" height="auto" />

<h1>N E X U S</h1>

<p>
  <strong>A Fullstack Social WebApp, that mixes X & Discord.</strong>
</p>


[![wip](https://img.shields.io/badge/status-work%20in%20progress-lightgrey?style=flat-square)](#)
[![license](https://img.shields.io/badge/license-Custom%20Portfolio-blue?style=flat-square)](https://github.com/lucy-next/Nexus/blob/main/LICENSE)

---

</div>

## Project Purpose

Nexus is a **Proof-of-Concept (PoC)** designed to demonstrate my proficiency in TypeScript-driven fullstack development. The primary focus of this project is not just "another social clone," but an exercise in building a complex App without reliance on external APIs.

### Separation of Concerns

Unlike many modern Next.js projects that rely on Server Side Rendering, Nexus follows Server / Client Seperation:

* **Decoupled Backend:** A dedicated Nest.js API handles business logic, security, and database interactions.
* **Independent Frontend:** Next.js acts purely as a consumer of the API, ensuring that the backend remains easier to scale or secure later on.
* **Data Sovereignty:** All content moderation (Text & Image scanning) is handled locally on the server to avoid reliance on expensive 3rd-party APIs.

---

## Development Status

### Implemented
* Nothing, i just started.

### Planned (In Development)
* **User Accounts:** Secure registration logic and JWT-based authentication.
* **Database Foundation:** Scalable SQL schema using Prisma.
* **Profile Management:** Custom bios, avatars, and account settings.
* **Global Feed:** A Twitter-style timeline with Posts and Comments.
* **Chatrooms:** A Discord-style Group chats with Realtime Chatting via WebSockets.
* **Messaging:** 1:1 Realtime DMs via WebSockets.
* **Local AI Moderation:** Integrate a Filter for local image & text scanning and custom profanity filters.
* **Admin Tools:** Dedicated moderation page for banning users and updating filters.

---
<div align="center">
<br />
<sub>Built with Blahaj and TypeScript by Lucy</sub>
</div>
