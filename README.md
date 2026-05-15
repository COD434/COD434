# Hey, I'm Karabo 

Self-taught backend engineer focused on authentication systems, API security, and developer tooling. I don't just use Auth,I build the infrastructure behind it and i have fun doing it. I also play PUBG when I feel like relaxing😏 

Currently I am:

- Deepening my  cryptography knowledge to strengthen the security foundations of Authenik8

- Deepening my understanding of system design and DSAs to build more scalable, production-grade systems 

- Extending the Authenik8 ecosystem  next milestone: integrating the standalone API into the CLI as an optional preset

---

## 🛠️ Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

---

##  The Authenik8 Ecosystem

Most developers bolt auth on at the end. I built an entire ecosystem around doing it right from the start.

### [`authenik8-core`](https://www.npmjs.com/package/authenik8-core) The Identity Engine
![npm](https://img.shields.io/npm/v/authenik8-core?style=flat-square&color=CB3837&logo=npm)

The core library powering the entire ecosystem. An Identity Engine that resolves credentials, OAuth profiles, and future auth strategies into a unified system identity  preventing duplicate identities and handling login vs. account-linking flows consistently.

---

### [`create-authenik8-app`](https://github.com/COD434/create-authenik8-app) The CLI Generator
![Maintained](https://img.shields.io/badge/maintained-yes-success?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-ready-blue?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)

```bash
npx create-authenik8-app my-app
```

Scaffolds a production-ready auth backend in seconds. What you get instantly:
- JWT access + refresh token rotation
- Redis-based token storage
- Role-Based Access Control (RBAC)
- Google & GitHub OAuth via the Identity Engine
- Clean, scalable folder structure
- `.env` auto-generated

Roadmap: WebAuthn · MFA · Advanced RBAC · Production presets

---

### [`Authenik8`](https://github.com/COD434/Authenik8)  The production API
![CI](https://github.com/COD434/Authenik8/actions/workflows/CI.yml/badge.svg?branch=main&event=push)
![Documents Passing](https://img.shields.io/badge/documents-passing-brightgreen)
![SQLi Passing](https://img.shields.io/badge/SecurityTests-passing-brightgreen)

A standalone, attach-to-any-frontend auth API built for real production workloads.

**Features:**
- JWT authentication with token bucket rate limiting
- IP whitelisting + dynamic IP expiration
- Redis-backed rate limiting and token management
- Email verification and OTP support
- Role-based access control + admin seeding
- Anonymous guest-mode auth
- Grafana + Prometheus observability out of the box
- Load tested with Artillery
- Fully containerised with Docker Compose

```bash
git clone https://github.com/COD434/Authenik8
docker-compose up --build
```

---

## Currently Building

The Authenik8 ecosystem

---

## Currently Studying

![Cryptography](https://img.shields.io/badge/Cryptography-deepening-blueviolet?style=flat-square)
![System Design](https://img.shields.io/badge/System%20Design-deepening-blue?style=flat-square)
![DSA](https://img.shields.io/badge/DSA-active-orange?style=flat-square)

---

## 📬 Get In Touch

[![Gmail](https://img.shields.io/badge/Email-seeisakarabo2%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:seeisakarabo2@gmail.com)
[![npm](https://img.shields.io/badge/npm-authenik8--core-CB3837?style=flat-square&logo=npm)](https://www.npmjs.com/package/authenik8-core)
[![GitHub](https://img.shields.io/badge/GitHub-COD434-181717?style=flat-square&logo=github)](https://github.com/COD434)

---

*Authentication is an identity resolution problem. I build systems that treat it that way.*
