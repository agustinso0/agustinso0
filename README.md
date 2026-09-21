<div align="center">

# Agustin Loos

### Full Stack Developer | Backend & IoT

Building web applications, REST APIs, industrial IoT integrations, and modular backend systems with a strong focus on clean architecture, code quality, and real business needs.

[Portfolio](https://agustinloos.dev) | [LinkedIn](https://www.linkedin.com/in/agustinloos/) | [GitHub](https://github.com/agustinso0) | [Email](mailto:loosagustin@gmail.com)

</div>

---

## About Me

I'm a Full Stack Developer with a backend focus, working across web applications, REST APIs, industrial IoT integrations, and modular systems.

I drive an AI-augmented engineering workflow using Claude Code, OpenCode, and Engram: from architecture design and codebase analysis to guided refactoring, test generation, and persistent decision tracking across sessions. Combined with SDD and TDD, this approach lets me structure requirements, detect edge cases early, and validate changes with comprehensive tests before scaling complexity.

---

## Technical Skills

### Languages

```txt
JavaScript | TypeScript | Go | SQL | HTML5 | CSS3
```

### Frontend

```txt
React | Next.js | Redux | State Management | API Integration
Reusable Components | Forms | Responsive Design | HTML | CSS
```

### Backend

```txt
Node.js | NestJS | Express.js | RESTful APIs | JWT | WebSockets
Modular Architecture | Service Design | Authentication | Authorization
```

### Databases

```txt
PostgreSQL | MongoDB | Redis | Prisma ORM
Data Modeling | Schema Design | Query Optimization
```

### Testing, Quality & DevOps

```txt
TDD | Jest | Unit Tests | Integration Tests | E2E Tests
ESLint | Prettier | Docker | Linux | Git | GitHub Actions | CI/CD
GitLab self-managed | Nginx (reverse proxy, SSL/TLS, rate limiting)
```

### IoT & Embedded

```txt
MQTT | mTLS | Modbus RTU | Protobuf | AWS IoT Core
Eclipse hawkBit (OTA) | Embedded C | Zephyr firmware
```

### Desktop

```txt
Go (Wails, Fyne)
```

### AI-Augmented Development

```txt
Claude Code | OpenCode | Engram | Gentle AI | SDD | TDD
Architecture design | Guided refactoring | Test generation
Cross-session context persistence | Incremental planning
```

---

## Experience

### Full Stack Developer Jr → Platform Specialist | Pump Control S.R.L.

**June 2026 – present**

Industrial IoT — fuel measurement and control equipment for the oil & gas industry.

- Built and maintained the internal technical documentation platform (Docusaurus + multi-repo federation pipeline), integrating corporate SSO (Microsoft Entra ID) and a Go backend service for tiered authorization and access auditing of private manuals.
- Designed and implemented, through full SDD/TDD cycles, the deployment of an OTA update server (Eclipse hawkBit) across testing and production, including Zephyr firmware and a device simulator to validate the full flow against real hardware.
- Built a Go-based CI/CD tool for secure firmware secret distribution via GitLab Package Registry, adopted by the Firmware team; diagnosed and fixed real production bugs involving TLS and Git identity.
- Diagnosed a critical embedded C firmware bug causing field reboots of an industrial controller: identified the root cause (a TLS/TCP handling overflow) and built a reproduction tool that let the Firmware team validate and implement the fix.
- Contributed to a desktop application (Go + Wails) for device firmware recovery via the MCUboot/SMP protocol: ports/adapters architecture, CLI, and UI/UX improvements.
- Developed end-of-line (EOL) production testing tools: migrated a Python test bench for an IoT device to Go (MQTT/mTLS, AWS IoT Core, Protobuf), and built a Go-based EOL test program using Modbus RTU for another product line.
- Resolved internal infrastructure incidents and maintained the Nginx-based reverse proxy layer (SSL/TLS termination with Let's Encrypt/Certbot, virtual hosts, rate limiting, security headers, Docker integration); handled TLS certificate rotation, testing environments, self-managed GitLab, and contributed to an embedded controller's React/TypeScript frontend.

### Full Stack Developer (Freelance) | Aloise Sur

**Mar 2025 – Oct 2025**

- Developed features for a financial dashboard (Next.js, TypeScript), improving consultation and visualization of operational data.
- Contributed to the implementation of an ERP system focused on reducing manual tasks and streamlining internal processes.
- Standardized development environments with Docker and optimized database queries to improve response times in frequent operations.
- Built administrative interfaces and management views focused on usability and clear information display.

### Trainee Apprentice | Smurfit Westrock

**Jan 2024 – May 2024**

- Provided technical support to internal users, resolving incidents related to systems, connectivity, and equipment.
- Performed preventive and corrective maintenance on systems and networks; documented incidents and procedures for recurring issue tracking.

---

## Featured Project

### Passenger Transportation Management System | Backend API

Backend project focused on managing passenger transportation operations: bookings, trips, companies, users, vehicles, drivers, payments, invoicing, notifications, and operational analytics.

**Technical stack:** Node.js 20, NestJS 11, TypeScript strict, PostgreSQL, Prisma ORM, Redis, BullMQ, JWT/Passport, Swagger/OpenAPI, Jest, Docker, GitHub Actions, ESLint, Prettier.

**Highlights:**

- Modular monolith architecture with clear domain boundaries and explicit inter-module contracts.
- 14 domain modules: Auth, Companies, Users, Drivers, Vehicles, Routes, Trips, Bookings, Payments, Invoices, Notifications, Analytics, Audit Log, and Health.
- Multi-tenant context resolution per request, ports/adapters pattern for decoupling use cases and persistence, and support for asynchronous flows.
- Redis (cache, locks, rate limiting), BullMQ (background jobs), domain events, and outbox pattern for traceability and internal consistency.
- Full test coverage with Jest (unit, integration, e2e), architecture guardrails, and AI-assisted test generation via SDD/TDD.
- SDD workflow to split complex changes into proposal, design, specification, tasks, and verification before implementation.

---

## Education

- **Technical Degree in Programming** | Universidad Tecnológica Nacional FRBB | 2024 – 2025 | GPA: 8.78
- **Information Systems Engineering** | Universidad Nacional del Sur | 2022 – 2023
- **Professional and Personal IT Technician** | Escuela de Educación Secundaria Técnica N.º 1, Coronel Suárez | 2015 – 2021

---

## Languages

| Language | Proficiency |
| --- | --- |
| Spanish | Native |
| English | Intermediate |

---

## Contact

I'm interested in backend architecture, industrial IoT, full stack product development, technical quality, and AI-augmented engineering workflows.

<div align="center">

**[Portfolio](https://agustinloos.dev)** | **[LinkedIn](https://www.linkedin.com/in/agustinloos/)** | **[GitHub](https://github.com/agustinso0)** | **[Email](mailto:loosagustin@gmail.com)**

</div>

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=agustinso0&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=agustinso0&layout=compact&theme=dark&hide_border=true&bg_color=0d1117" alt="Top Languages" height="165" />
</div>

---

<div align="center">
  <sub>Last updated: Sept 2026 | Full Stack Developer | Backend & IoT | AI-augmented development</sub>
</div>
