<div align="center">

<!-- 🖼️ LOGO PLACEHOLDER: replace with your logo, e.g. ./docs/assets/logo.png -->
<img src="./logo.svg" alt="logo-yourguide.png" width="240" />

# LankaGuide

**Discover Sri Lanka with verified local guides, on your own terms.**

A web and mobile platform connecting local and foreign tourists with SLTD-verified tour guides and travel agencies, featuring customisable tours, AI-powered recommendations, live location sharing and a social "For You" feed.

[![Status](https://img.shields.io/badge/status-in%20development-orange?style=for-the-badge)](#-roadmap)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red?style=for-the-badge)](#-license)
[![Repo](https://img.shields.io/badge/repository-private-lightgrey?style=for-the-badge)](#)
[![PRs](https://img.shields.io/badge/PRs-team%20only-blue?style=for-the-badge)](#-contributing--git-workflow)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

<!-- 🔧 Once CI is set up, add: [![CI](https://github.com/<ORG_OR_USER>/<REPO>/actions/workflows/ci.yml/badge.svg)](https://github.com/<ORG_OR_USER>/<REPO>/actions) -->

[About](#-about) •
[Features](#-features) •
[Screenshots](#-screenshots--prototype) •
[Tech Stack](#-tech-stack) •
[Getting Started](#-getting-started) •
[Roadmap](#-roadmap) •
[Contributing](#-contributing--git-workflow) •
[Team](#-team)

</div>

---

## 📖 About

Tourism is one of Sri Lanka's most important industries, yet travellers still struggle to find trustworthy guides, understand fair prices and plan routes that suit them. Guides and agencies, in turn, lack a single place to build credibility and reach visitors.

**LankaGuide** brings **tourists, tour guides and travel agencies** together in one platform:

- **Tourists** (local and foreign) hire guides directly, shape their own tour routes, discover historical sites and stays on a map, and share their live location with trusted contacts while travelling.
- **Guides and agencies** earn trust through an **SLTD-licence verified badge** (the blue tick), publish transparent fares and promote their services.
- **Everyone** shares journeys, photos and promotions through a social **For You** feed.
- **AI** helps with destination and guide recommendations, a travel chatbot and a profile assistant.


## ✨ Features

### 🧳 For Tourists

| Feature | Description |
|---|---|
| **Hire guides directly** | Browse verified guides, compare fares and send a booking request without a middleman. |
| **Customisable tours** | Choose destinations, set the date and time, and pick your own pick-up and drop-off points. |
| **Stays on a map** | View hotels, cabanas and rooms on an interactive map alongside historical sites. |
| **Live location sharing** | Share real-time location with a chosen contact while travelling, and stop at any time. |
| **For You feed** | Follow journeys and photos from other travellers, guides and agencies; like and comment. |
| **Report an issue** | Report a guide, agency, post or safety problem directly in the app. |

### 🧭 For Guides and Agencies

| Feature | Description |
|---|---|
| **SLTD verified badge** | Submit an SLTD licence for verification and receive a blue tick on your profile. |
| **Profile and fares** | Showcase languages, specialities, areas covered and transparent pricing. |
| **Promotions** | Agencies can publish offers and packages to the For You feed. |
| **Booking management** | Accept, decline or adjust tour requests from tourists. |

### 🤖 AI Features

| Feature | Description |
|---|---|
| **Destination recommendations** | Personalised suggestions based on interests, trip length and past activity. |
| **Guide recommendations** | Matches tourists to guides by language, location, speciality, price and rating. |
| **AI chatbot** | Answers travel questions about destinations, transport, culture and using the app. |
| **Profile assistant** | Helps guides, agencies and tourists write and improve their profiles. |

### 🌐 Platform

- **Multilingual:** Sinhala, Tamil and English at launch, with more languages planned.
- **Roles:** Tourist, Guide, Agency and Admin, with role-based access control.
- **Platforms:** Responsive web app and a mobile app (iOS and Android).

---

## 🖼️ Screenshots / Prototype

> 📌 **Placeholders.** Replace these with real screenshots or Figma exports as screens are built. Suggested folder: `docs/screenshots/`.

| Home / Discover | Guide Profile (Verified ✔) | Tour Customiser |
|:---:|:---:|:---:|
| ![Home](./docs/screenshots/home.png) | ![Guide profile](./docs/screenshots/guide-profile.png) | ![Tour customiser](./docs/screenshots/tour-customiser.png) |

| Stays Map | For You Feed | Live Location Sharing |
|:---:|:---:|:---:|
| ![Map](./docs/screenshots/map.png) | ![Feed](./docs/screenshots/feed.png) | ![Live location](./docs/screenshots/live-location.png) |

| AI Chatbot | Profile Assistant | Report an Issue |
|:---:|:---:|:---:|
| ![Chatbot](./docs/screenshots/chatbot.png) | ![Profile assistant](./docs/screenshots/profile-assistant.png) | ![Report](./docs/screenshots/report.png) |

**🎨 Design prototype:** `[Figma link: PLACEHOLDER]`
**🚀 Live demo:** `[Demo link: PLACEHOLDER]`

---

## 🛠️ Tech Stack


| Layer | Technology | Why |
|---|---|---|
| **Web** | React + Vite + Tailwind CSS | Fast development, large ecosystem |
| **Mobile** | React Native (Expo) | Shares logic and types with the web app |
| **Backend** | Node.js + NestJS (REST API) | Structured, modular, TypeScript-first |
| **Database** | PostgreSQL + PostGIS | Relational data (bookings, roles, verification) plus geospatial queries (nearby stays and guides) |
| **ORM** | Prisma | Type-safe queries and migrations |
| **Real-time** | Socket.IO | Live location sharing |
| **Maps** | Leaflet + OpenStreetMap (or Mapbox) | Free option available for development |
| **Auth** | JWT + role-based access control | Tourist, Guide, Agency, Admin |
| **AI** | LLM API (chatbot, profile assistant) + recommendation service | Provider to be decided |
| **Media storage** | Cloudinary or AWS S3 | Feed photos and licence documents |
| **i18n** | i18next | Sinhala, Tamil, English and future languages |
| **CI/CD** | GitHub Actions | Lint, test and build on every PR |
| **Hosting** | Vercel (web), Render or Railway (API) | Simple deployment |
| **Project management** | Jira | Backlog, sprints and issue tracking |
| **Coursework docs** | Google Docs | Project report and documentation |

### Architecture Overview

```text
 ┌──────────────┐   ┌──────────────────┐
 │  Web (React) │   │ Mobile (Expo RN) │
 └──────┬───────┘   └────────┬─────────┘
        │   REST + WebSocket │
        └──────────┬─────────┘
                   ▼
          ┌─────────────────┐        ┌───────────────────┐
          │  API (NestJS)   │───────▶│ AI services (LLM, │
          │ Auth • Bookings │        │ recommendations)  │
          │ Feed • Reports  │        └───────────────────┘
          └───┬─────────┬───┘
              ▼         ▼
   ┌────────────────┐  ┌──────────────────┐
   │ PostgreSQL +   │  │ Media storage    │
   │ PostGIS        │  │ (S3/Cloudinary)  │
   └────────────────┘  └──────────────────┘
```

---

## 🚀 Getting Started

> These instructions assume the proposed monorepo layout below. Update them once the stack and structure are finalised.

### Prerequisites

- [Node.js](https://nodejs.org/) `>= 20`
- [npm](https://www.npmjs.com/) `>= 10`
- [PostgreSQL](https://www.postgresql.org/) `>= 15` with the PostGIS extension (or [Docker](https://www.docker.com/))
- [Expo Go](https://expo.dev/go) app, or an Android/iOS emulator, for mobile
- [Git](https://git-scm.com/)

### 1. Clone the repository

The repository is private, so make sure you have been added as a collaborator.

```bash
git clone https://github.com/<ORG_OR_USER>/<REPO>.git
cd <REPO>
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Copy the example files and fill in your own values. **Never commit real secrets.**

```bash
cp apps/api/.env.example apps/api/.env
cp apps/web/.env.example apps/web/.env
cp apps/mobile/.env.example apps/mobile/.env
```

**`apps/api/.env`**

```env
# Server
PORT=4000
NODE_ENV=development

# Database
DATABASE_URL="postgresql://postgres:postgres@localhost:5432/lankaguide?schema=public"

# Auth
JWT_SECRET=change_me
JWT_EXPIRES_IN=7d

# AI
AI_PROVIDER_API_KEY=your_key_here

# Media storage
CLOUDINARY_URL=cloudinary://<key>:<secret>@<cloud_name>

# Maps (if using Mapbox)
MAPBOX_TOKEN=your_token_here
```

**`apps/web/.env`**

```env
VITE_API_URL=http://localhost:4000
VITE_MAPBOX_TOKEN=your_token_here
```

**`apps/mobile/.env`**

```env
EXPO_PUBLIC_API_URL=http://<YOUR_LOCAL_IP>:4000
```

### 4. Start the database (optional, via Docker)

```bash
docker run --name lankaguide-db -e POSTGRES_PASSWORD=postgres \
  -e POSTGRES_DB=lankaguide -p 5432:5432 -d postgis/postgis:15-3.4
```

### 5. Run migrations and seed data

```bash
npm run db:migrate --workspace=apps/api
npm run db:seed --workspace=apps/api
```

### 6. Run the apps

```bash
# API
npm run dev --workspace=apps/api

# Web
npm run dev --workspace=apps/web

# Mobile (scan the QR code with Expo Go)
npm run start --workspace=apps/mobile
```

| App | URL |
|---|---|
| Web | http://localhost:5173 |
| API | http://localhost:4000 |
| API docs (Swagger) | http://localhost:4000/api/docs |

### Useful scripts

| Command | Purpose |
|---|---|
| `npm run lint` | Lint all workspaces |
| `npm run test` | Run all tests |
| `npm run build` | Build all workspaces |
| `npm run format` | Format code with Prettier |

---

## 📂 Project Structure

```text
LankaGuide/
├── apps/
│   ├── web/            # React + Vite web app
│   ├── mobile/         # React Native (Expo) app
│   └── api/            # NestJS backend (REST + WebSocket)
│       ├── prisma/     # Schema, migrations, seed
│       └── src/
│           ├── auth/
│           ├── users/
│           ├── guides/
│           ├── agencies/
│           ├── bookings/
│           ├── tours/
│           ├── places/        # Historical sites and stays
│           ├── feed/          # Posts, likes, comments
│           ├── tracking/      # Live location sharing
│           ├── reports/
│           ├── reviews/
│           └── ai/            # Chatbot, recommendations, profile assistant
├── packages/
│   └── shared/         # Shared types, validation, i18n strings
├── docs/
│   ├── assets/         # Logo and images
│   ├── screenshots/    # App screenshots
│   └── architecture/   # Diagrams and design notes
├── .github/
│   ├── workflows/      # CI pipelines
│   └── pull_request_template.md
├── README.md
└── package.json
```

---

## 🗺️ Roadmap

> 📌 **Draft plan.** The delivery framework, sprint length and dates have **not been decided yet**. Fill in the blanks once Chapter 3 of the coursework document is agreed. Items are grouped by theme, not committed to specific sprints.

### 🏁 Delivery Framework

| Item | Value |
|---|---|
| **Framework** | `[Scrum / Kanban / Scrumban: TBD]` |
| **Sprint length** | `[TBD]` |
| **Number of sprints** | `[TBD]` |
| **Project start** | `[DD/MM/YYYY]` |
| **Final submission** | `[DD/MM/YYYY]` |
| **Board** | Jira: `[link: PLACEHOLDER]` |

### 🎯 Phase 1: Foundation (Sprint `[X]`)

- [ ] Finalise tech stack, repository setup and CI
- [ ] Design system and Figma prototype
- [ ] Database schema design
- [ ] Authentication and role-based access (Tourist, Guide, Agency, Admin)
- [ ] Multilingual setup (Sinhala, Tamil, English)

### 🎯 Phase 2: Core Marketplace (Sprint `[X]`)

- [ ] Guide and agency profiles
- [ ] SLTD licence submission and verified badge (admin review flow)
- [ ] Guide search, filters and fare display
- [ ] Hire a guide: booking request and acceptance flow

### 🎯 Phase 3: Tours and Maps (Sprint `[X]`)

- [ ] Customisable tour builder (destinations, dates, pick-up and drop-off)
- [ ] Interactive map of historical sites
- [ ] Hotels, cabanas and rooms on the map

### 🎯 Phase 4: Community (Sprint `[X]`)

- [ ] For You feed: posts with photos
- [ ] Likes and comments
- [ ] Agency promotions
- [ ] Report an issue (users, posts, safety)

### 🎯 Phase 5: Safety and AI (Sprint `[X]`)

- [ ] Live location sharing with a trusted contact
- [ ] Destination and guide recommendation engine
- [ ] AI chatbot
- [ ] AI profile assistant

### 🎯 Phase 6: Polish and Submission (Sprint `[X]`)

- [ ] Testing, bug fixing and performance
- [ ] Accessibility and usability review
- [ ] Documentation and final demo

### 🔮 Post-Submission / Market Launch Ideas

- [ ] Additional app languages beyond Sinhala, Tamil and English
- [ ] Reviews and ratings for guides and agencies
- [ ] Expanded user profile section (travel history, saved places, preferences)
- [ ] Online payments and booking deposits
- [ ] Offline maps
- [ ] Push notifications
- [ ] Admin analytics dashboard
- [ ] Partnerships with hotels and transport providers

---

## 🤝 Contributing / Git Workflow

This is a **private, team-only** repository. Please follow the conventions below so the history stays clean and every change is traceable to a Jira ticket.

### Branching Strategy

| Branch | Purpose |
|---|---|
| `main` | Stable, demo-ready code. Protected: changes only via pull request. |
| `develop` | Integration branch for completed features. |
| `feature/<JIRA-KEY>-short-description` | New features, e.g. `feature/LG-12-guide-search` |
| `bugfix/<JIRA-KEY>-short-description` | Bug fixes, e.g. `bugfix/LG-34-map-marker-crash` |
| `hotfix/<short-description>` | Urgent fixes to `main` |
| `docs/<short-description>` | Documentation only |

> `LG` is a suggested Jira project key. Replace it with your real key.

### Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<scope>): <short summary> [JIRA-KEY]
```

| Type | Use for |
|---|---|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation changes |
| `style` | Formatting, no logic change |
| `refactor` | Code change that is neither a fix nor a feature |
| `test` | Adding or updating tests |
| `chore` | Tooling, config, dependencies |

**Example:** `feat(bookings): add pick-up location picker [LG-21]`

### Workflow

1. Pick a ticket from the current sprint on Jira and move it to **In Progress**.
2. Create a branch from `develop`:
   ```bash
   git checkout develop && git pull
   git checkout -b feature/LG-21-pickup-picker
   ```
3. Commit small and often, using the convention above.
4. Push and open a **pull request into `develop`**, linking the Jira ticket.
5. Request a review from **at least one** teammate. Move the ticket to **In Review**.
6. Address feedback, then **squash and merge** once approved and CI passes.
7. Move the ticket to **Done** and delete the branch.

### Pull Request Checklist

- [ ] The PR title follows the commit convention and includes the Jira key
- [ ] The code builds and runs locally
- [ ] Lint and tests pass
- [ ] New logic has tests where reasonable
- [ ] No secrets or `.env` files are committed
- [ ] UI changes include a screenshot or short recording
- [ ] Documentation is updated if needed

### Code Style

- TypeScript with strict mode
- ESLint and Prettier (run `npm run lint` and `npm run format` before pushing)
- Meaningful names, small functions, comments where intent isn't obvious

### Definition of Done

A ticket is **done** when it is reviewed and merged, passes CI, meets its acceptance criteria and has been demoed or verified by the team.

---

## 👥 Team

Built by a team of five as part of the Agile Team Project (ATP) module.

| Member | Role | GitHub |
|---|---|---|
| `Nidarsha Liyanarachchi` | `[Role, e.g. Scrum Master / Product Owner]` | [@username](https://github.com/Nidarsha44) |
| `Chathuranga Kalhara` | `[Role, e.g. Frontend Lead]` | [@username](https://github.com/chathuranga-K) |
| `Jeewaka Maduwantha` | `[Role, e.g. Backend Lead]` | [@username](https://github.com/Jeewaka-M20) |
| `Mandil Lisara Liyanage` | `[Role, e.g. AI / Data]` | [@username](https://github.com/username) |
| `Dasun Kalsara Silva` | `[Role, e.g. QA / UI-UX]` | [@username](https://github.com/dasunglitch) |

<!-- Role ideas: Product Owner, Scrum Master (if using Scrum), Frontend, Mobile, Backend, AI/ML, UI/UX Design, QA/Testing, DevOps, Documentation -->

**Tools:** Jira (project management) • Git and GitHub (version control) • Google Docs (coursework documentation)

---

## 📄 License

**© 2026 LankaGuide. All Rights Reserved.**

This software and its source code are proprietary and confidential. No part of this repository may be copied, modified, distributed, sublicensed or used for any purpose without prior written permission from the copyright holders.

<!-- Update the copyright holder(s) and year once decided. Check any university IP policy that may apply to coursework. -->

---

## 🙏 Acknowledgements

- **Sri Lanka Tourism Development Authority (SLTD)** for the licensing framework that underpins our verification badge
- `[Banu Athuraliya / Vishmi Embuldeniya]`, `[University of Westminster, UK - Informatic Institute of Technology]`
- [OpenStreetMap](https://www.openstreetmap.org/) contributors
- Open-source libraries and tools used in this project

---

<div align="center">

Made with ❤️ for Sri Lankan tourism

</div>
