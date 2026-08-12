# Morris Sambo

**Software Developer — South Africa**

I build production web applications and run the infrastructure they sit on. Currently a
developer at **Route Monitoring (RF) (Pty) Ltd**, and in my final year of a Diploma in
Information Technology at the Vaal University of Technology.

Most of my recent work is full-stack TypeScript — Next.js and React on the front,
PostgreSQL and Supabase behind it, deployed on infrastructure I set up and maintain myself.

---

## Selected work

### RM Training System · Route Monitoring *(private)*

A training registration and attendance platform used to manage operator certification
records. Next.js 15 and React 19 on TypeScript, with QR-code attendance capture and Excel
export for compliance reporting.

What I built and what it taught me:

- **PostgreSQL schema design with row-level security.** A nine-table schema with RLS
  policies on every table, versioned through SQL migrations rather than hand-applied
  changes.
- **Self-hosted infrastructure.** Moved the stack off hosted Supabase onto a self-managed
  Ubuntu server running the full Supabase stack under Docker Compose — Postgres, Kong API
  gateway, auth and storage — including generating and rotating the JWT signing secrets
  the service keys derive from.
- **A test suite that covers more than the happy path.** Vitest for unit tests, Playwright
  for end-to-end flows, and axe-core for automated accessibility auditing. The
  accessibility suite found real violations, which I fixed.
- **Security checks wired into the build.** ESLint security rules, a custom secret-scanning
  script, environment-variable validation and dependency auditing, combined into one
  release gate that has to pass before anything ships.
- **Performance work grounded in measurement** — including reducing over-fetching so pages
  request only the rows they actually render.

### Portfolio site

Next.js and TypeScript with Prisma over a relational database.
→ [`portfolio`](https://github.com/morrissambo18-oss/portfolio)

### Shalem Holdings

Business website for a digital solutions and event technology company. Built with Vite.
→ [`shalem-holdings`](https://github.com/morrissambo18-oss/shalem-holdings)

---

## Technical skills

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

Schema design, row-level security policies, SQL migrations, authentication and
session handling.

**Testing & quality**
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)

Unit and end-to-end testing, automated accessibility auditing with axe-core, static
security analysis, secret scanning.

**Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

Docker Compose, Ubuntu server administration, SSH key authentication, CI pipelines.

**Networking**
![Cisco CCNA](https://img.shields.io/badge/Cisco_CCNA-1BA0D7?style=flat-square&logo=cisco&logoColor=white)

---

## Currently

- Completing my Diploma in Information Technology
- Working on an AI solution for municipal water-loss detection — time series analysis,
  anomaly detection and multilingual speech processing in Python

---

## Contact

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:morris.sambo18@gmail.com)
