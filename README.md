<div align="center">

<img src="logo-yourguide.png" alt="YourGuide.lk logo" width="240" />

**Travel Sri Lanka with a guide you can trust.**

A web and mobile platform where local and foreign tourists find, customise and book SLTDA-verified tour guides and agencies, with transparent fares, live location sharing and AI trip suggestions.

[![Status](https://img.shields.io/badge/status-in%20development-orange?style=for-the-badge)](#-roadmap)
[![Landing page](https://img.shields.io/badge/landing%20page-live-brightgreen?style=for-the-badge)](https://yourguidelk.vercel.app/)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red?style=for-the-badge)](#-license)
[![PRs](https://img.shields.io/badge/PRs-team%20only-blue?style=for-the-badge)](#-contributing--git-workflow)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

[About](#-about) •
[Features](#-features) •
[Landing Page](#-landing-page) •
[Tech Stack](#-tech-stack) •
[Getting Started](#-getting-started) •
[Structure](#-project-structure) •
[Roadmap](#-roadmap) •
[Contributing](#-contributing--git-workflow) •
[Team](#-team)

</div>

---

## 📖 About

Sri Lanka has many skilled guides, but tourists cannot easily tell who is licensed, what a fair price is, or how to plan a route that suits them. Guides and agencies, in turn, have no single place to prove their credentials and reach visitors directly.

**YourGuide.lk** brings **tourists, tour guides, agencies and admins** together in one platform:

- **Tourists** (local and foreign) hire guides directly or through an agency, customise destinations and pick-up and drop-off points, see the fare upfront, and share their live location with trusted contacts.
- **Guides and agencies** earn a **blue tick** by submitting an SLTDA licence that an admin verifies, then take bookings and promote their services.
- **Everyone** shares journeys and promotions through a social **For You** feed.
- **AI** supports destination and guide recommendations, a chatbot and a profile assistant.

### Problem and aim

> **Problem:** Tourists in Sri Lanka lack a single platform to hire an SLTDA-verified guide at a fair price for a fully customised tour.
>
> **Aim:** *To build a trusted platform where tourists can hire verified guides and customise their own journey in Sri Lanka.*

### Client and context

| Item | Detail |
|---|---|
| **Client** | Simulated client based on the **Sri Lanka Tourism Development Authority (SLTDA)**, the regulator of tourism and guide licensing in Sri Lanka. Requirements come from official published material, competitor and document analysis, and weekly supervision sessions. |
| **Module** | Agile Team Project, 5COSC021C.Y University of Westminster, Informatics Institute of Technology (IIT) |
| **Competitors reviewed** | Withlocals, GoWithGuide, Tripadvisor, GetYourGuide, GoAroundSriLanka and SriLankaTravel |

---

## ✨ Features

### In scope (final product)

| Area | What it does |
|---|---|
| **Registration and login** | Separate access for tourists, guides, agencies and admins. |
| **SLTDA licence verification** | Licence number, expiry date and card photo are reviewed by an admin. |
| **Verified blue tick** | Shown on guide and agency profiles with a valid SLTDA licence. Unlicensed guides can still be listed, without the badge. |
| **Search** | Find guides and agencies by location, availability, ratings, reviews and budget. |
| **Tour customisation** | Choose destinations, date and duration, and set pick-up and drop-off points on a map. |
| **Transparent fares** | The fare breakdown is shown to tourists and guides before booking. |
| **Online payments** | Pay through a digital wallet. Receipts are sent by SMS and email. |
| **Rate and review** | Tourists review guides and agencies. |
| **For You feed** | Post photos and videos, like and comment. Agencies and guides can post promotions. |
| **AI recommendations** | Suggests destinations, tour packages and guides based on tourist interests. |
| **AI chatbot** | Answers questions in text and voice mode. |
| **AI profile assistant** | Helps tourists, guides, agencies and vehicle hires manage their profiles. |
| **Live location sharing** | Tourists share their live location with a contact by SMS or email while travelling. |
| **Vehicle and transport hire** | Hire a vehicle and transport service for a tour. |
| **Report an issue** | Report problems in the platform with images and videos. |
| **Platforms** | Mobile app for tourists. Web app for guides, agencies and the admin panel. |
| **Landing page** | Marketing website for YourGuide.lk |

### Out of scope (future development)

- Expanding the mobile app to guides, agencies and vehicle hire services
- Expanding the web app for tourists
- Automatic SLTDA verification through the SLTDA system
- Hotels, cabanas and rooms on a map, and booking accommodation
- Improved location sharing (last known location alert to an emergency contact)
- Online e-pass for essentials
- Travel insurance

---

## 🌐 Landing Page

The marketing landing page promotes the product to its target users and collects early-access sign-ups. It is **not** the product itself.

**🚀 Live site:** https://yourguidelk.vercel.app/

### Sections

| Section | Purpose |
|---|---|
| **Hero** | Value proposition, call to action and the licence-verified and live-location highlights |
| **Why YourGuide.lk** | The three core problems: unverified guides, no single place to book, hard planning |
| **Features** | Nine key features, shown with a screenshot of the app home screen |
| **How it works** | Discover, customise, book and pay, travel safely |
| **Safety** | Opt-in, time-limited live trip link and in-app reporting |
| **For guides and agencies** | Benefits and join buttons |
| **FAQ** | Blue tick, local tourists, location sharing, payments, launch date |
| **Early access** | Email sign-up and App Store and Google Play badges (coming soon) |

### Landing page requirements checklist

Based on the Coursework 1 specification. Ticks reflect what is visible on the live site.

- [x] Product name, logo and clear value proposition
- [x] The problem and how the product solves it
- [x] Key features with a screenshot from the prototype
- [x] Working call to action (early-access email form)
- [x] Contact email and copyright footer
- [x] Hosted over HTTPS
- [x] Page title and meta description
- [x] Responsive styles for tablet and mobile
- [ ] Team section (names and roles)
- [ ] Social links and privacy notice (the email form collects personal data)
- [ ] Hosted on the team's own `.com` or `.lk` domain (currently on `vercel.app`)
- [ ] Favicon and social media preview image
- [ ] Accessibility check (alt text, colour contrast, keyboard navigation)
- [ ] Analytics for visitor and sign-up numbers (encouraged)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Landing page** | HTML, CSS, JavaScript, hosted on Vercel |
| **Web app** | React |
| **Mobile app** | React Native (Expo), chosen to stay close to the React web stack |
| **Backend** | Java Spring Boot (REST API) |
| **Real-time** | WebSockets (live location sharing) |
| **Database** | PostgreSQL |
| **Maps** | Google Maps |
| **Payments** | Visa, Google Pay, Apple Pay |
| **AI** | LLM-based chatbot and recommendation service (provider to be decided) |
| **Design** | Figma |
| **Testing** | Postman |
| **Project management** | Jira |
| **Version control** | Git and GitHub |
| **Documentation** | Google Docs, draw.io |

### Architecture overview

```text
 ┌────────────────────┐  ┌───────────────────────┐
 │ Web app (React)    │  │ Mobile app (React     │
 │ guides • agencies  │  │ Native) • tourists    │
 │ • admin            │  │                       │
 └─────────┬──────────┘  └───────────┬───────────┘
           │      REST + WebSocket   │
           └────────────┬────────────┘
                        ▼
              ┌───────────────────┐        ┌───────────────────┐
              │ API (Spring Boot) │───────▶│ AI services       │
              │ Auth • Bookings   │        │ (chatbot,         │
              │ Feed • Reports    │        │ recommendations)  │
              └─────────┬─────────┘        └───────────────────┘
                        ▼
              ┌───────────────────┐
              │    PostgreSQL     │
              └───────────────────┘
```

> The web app, mobile app and API are planned. This repository currently contains the marketing landing page.

---

## 🚀 Getting Started

The landing page is plain HTML, CSS and JavaScript, so there is **no build step and no dependencies to install**.

### Prerequisites

- [Git](https://git-scm.com/)
- A modern web browser
- Optional: a local web server, for example the VS Code **Live Server** extension

### Run the landing page locally

The repository is private, so make sure you have been added as a collaborator.

```bash
git clone https://github.com/<ORG_OR_USER>/<REPO>.git
cd <REPO>/marketing-landing-page
```

Then either open `index.html` directly in your browser, or serve the folder with Live Server.

### Deployment

The landing page is deployed on **Vercel** at https://yourguidelk.vercel.app/.

> Vercel project settings (root directory, production branch) are `[TBD]`.

---

## 📂 Project Structure

Current repository layout:

```text
.
├── marketing-landing-page/
│   ├── index.html              # Page content and menu script
│   ├── style.css               # Styles, including tablet and mobile breakpoints
│   ├── phone-screen.png        # App home screen screenshot
│   ├── app-store-badge.png     # App Store badge (coming soon)
│   └── google-play-badge.png   # Google Play badge (coming soon)
├── logo-yourguide.png          # Project logo
├── .gitignore
└── README.md
```

Folders for the web app, mobile app and API will be added as those parts are built.

---

## 🗺️ Roadmap

> 📌 **Draft plan.** The delivery framework, sprint dates and board link are not final. Replace the `TBD` values once Chapter 3 of the coursework document is agreed.

### Delivery framework

| Item | Value |
|---|---|
| **Google Doc (coursework)** | `https://docs.google.com/document/d/1pi_fOmgh55fEjvhewt7WQdMKd3yZMoGveOcmOFy3mhk/edit?tab=t.0` |
| **Figma prototype** | `https://www.figma.com/design/CKJO0sRbHZUSGZljRyYgJf/YourGuide.lk-UI?node-id=2-2&t=DCVRu5M17gh5iX5a-1` |

### Progress so far

- [x] Project idea, problem statement and aim defined
- [x] Competitor analysis started (Withlocals, GoWithGuide, Tripadvisor, GetYourGuide, GoAroundSriLanka, SriLankaTravel)
- [x] Chapter 1 (Introduction) and Chapter 2 (Existing Work) drafted in the Google Doc
- [x] Repository set up
- [x] Marketing landing page built and deployed on Vercel
- [ ] High-fidelity Figma prototype
- [ ] Landing page: team section, privacy notice, custom domain

### Planned delivery

| Phase | Focus |
|---|---|
| **1. Foundation** | Tech stack, database schema, authentication and roles (tourist, guide, agency, admin) |
| **2. Core marketplace** | Guide and agency profiles, SLTDA licence submission and blue tick, search and fares, booking flow |
| **3. Tours and payments** | Tour customisation with pick-up and drop-off, online payments, reviews and ratings, vehicle hire |
| **4. Community and safety** | For You feed, promotions, live location sharing, report an issue |
| **5. AI** | Recommendations, chatbot, profile assistant |
| **6. Polish and submission** | Testing, accessibility review, documentation, final demo |

Items are grouped by theme and are not yet committed to specific sprints.

---

## 🤝 Contributing / Git Workflow

This is a **private, team-only** repository. Every change should be traceable to a Jira ticket.

### Branches

| Branch | Purpose |
|---|---|
| `main` | Stable, demo-ready code (and what Vercel deploys). Changes go through pull requests. |
| `feature/<JIRA-KEY>-short-description` | New features, e.g. `feature/<JIRA-KEY>-team-section` |
| `bugfix/<JIRA-KEY>-short-description` | Bug fixes |
| `docs/<short-description>` | Documentation only |

> The Jira project key is `[TBD]`. A separate `develop` branch can be added once the app and API repositories grow.

### Commit messages

Short, imperative summaries that follow [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<scope>): <short summary> [JIRA-KEY]
```

Common types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

**Example:** `feat(landing): add team section [JIRA-KEY]`

### Workflow

1. Pick a ticket from the current sprint and move it to **In Progress**.
2. Create a branch from `main`:
   ```bash
   git checkout main && git pull
   git checkout -b feature/<JIRA-KEY>-short-description
   ```
3. Commit small and often.
4. Push and open a **pull request**, linking the Jira ticket.
5. Get a review from **at least one** teammate and move the ticket to **In Review**.
6. Merge once approved, move the ticket to **Done** and delete the branch.

### Pull request checklist

- [ ] Title includes the Jira key
- [ ] The change runs locally
- [ ] UI changes include a screenshot
- [ ] No secrets or personal data are committed
- [ ] Documentation is updated if needed

### Definition of Done

A ticket is **done** when it is reviewed and merged, meets its acceptance criteria and has been demoed or checked by the team.

---

## 👥 Team

Built by a team of five as part of the Agile Team Project (ATP) module.

| Member | Role | GitHub |
|---|---|---|
| Nidarsha Liyanarachchi | `Team Leader` | [@Nidarsha44](https://github.com/Nidarsha44) |
| Chathuranga Kalhara | `Scrum master` | [@chathuranga-K](https://github.com/chathuranga-K) |
| Jeewaka Maduwantha | `UI Design` | [@Jeewaka-M20](https://github.com/Jeewaka-M20) |
| Mandil Lisara Liyanage | `Codes` | [@username](https://github.com/username) |
| Dasun Kalsara Silva | `Tests & Documentation` | [@dasunglitch](https://github.com/dasunglitch) |

**Tools:** Jira (project management) • Git and GitHub (version control) • Google Docs (coursework documentation) • Figma (design)

---

## 📄 License

**© 2026 YourGuide.lk. All Rights Reserved.**

This is a university project. The software and source code are proprietary and confidential. No part of this repository may be copied, modified, distributed or used without prior written permission from the copyright holders.

---

## 🙏 Acknowledgements

- **Sri Lanka Tourism Development Authority (SLTDA)** for the licensing framework behind our verification badge
- **Mrs. Vishmi Ambuldeniya**, module supervisor, and **Banuka Athuraliya**, module leader
- Informatics Institute of Technology (IIT) and the University of Westminster, UK
- Open-source libraries and tools used in this project

---

<div align="center">

Made with ❤️ for Sri Lankan tourism

</div>
