# Maksym Ostrovskyi

**Backend Developer** · Python · FastAPI · PostgreSQL · Docker

I build async backend services with clean architecture and real production concerns in mind —
concurrency, caching, containerized deployments.

---

## Stack

**Backend**
`Python` `FastAPI` `Django` `Asyncio` `Pydantic` `SQLAlchemy 2.0` `Alembic`

**Data & Caching**
`PostgreSQL` `Redis` `SQL`

**Infrastructure**
`Docker` `Docker Compose` `JWT / bcrypt`

**Frontend**
`TypeScript` `JavaScript` `REST API` `React`

---

## Projects

### [booking_service](https://github.com/RiaLnN/booking_service) — Fullstack Booking App
> FastAPI · PostgreSQL · Redis · TypeScript · Docker Compose

Fullstack application for booking meeting rooms and desks.
Async REST API with layered architecture (Routers → Services → Models), JWT authentication, Redis caching, Alembic migrations.
Race conditions handled via pessimistic row-level locking (`SELECT ... FOR UPDATE`).
TypeScript SPA frontend with admin panel, slot management and booking flow.
Full environment in Docker Compose: frontend (Nginx) + backend + PostgreSQL + Redis.

---

### [telegramBot_whisper](https://github.com/RiaLnN/telegramBot_whisper) — Voice Transcription Telegram Bot
> Python · aiogram · Groq Whisper · LLaMA · Docker · Azure

Telegram bot that transcribes voice messages in seconds using Groq's Whisper API.
Reply to any transcription with a summary command — bot returns a concise summary via a second LLM call.
Works in any language. Deployed on Azure via Docker.

---

### [GravityC](https://github.com/RiaLnN/GravityC) — N-Body Gravity Simulation
> C11 · SDL3

2D gravitational simulation of N bodies written in pure C.
Inelastic collision physics (momentum conservation, dynamic radius recalculation).
Direct pixel-buffer rendering, O(N²) force calculation, manual memory management.

---

### [Remote-System-Monitor-Bot](https://github.com/RiaLnN/Remote-System-Monitor-Bot)
> Python · aiogram · Telegram API

Telegram bot for remote server monitoring. Real-time system metrics, alert notifications.

---

## Contact

[Telegram](https://t.me/rialnns) · [max07070799@gmail.com](mailto:max07070799@gmail.com) · Open to remote
