<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="profile-light.svg">
  <img alt="Valerie Rwamba Munyi — cybersecurity, software, DevSecOps, AI and entrepreneurship. Full-frame ASCII portrait." src="profile-dark.svg" width="1080">
</picture>

# Valerie Rwamba Munyi

**Building useful technology. Making security part of the process. Turning ideas into evidence.**

I'm Valerie, a technology builder and entrepreneur based in Nairobi, Kenya, working across **software development, cybersecurity, and release engineering**. My wider interests include **DevSecOps, AI applications, data privacy, and technology ventures**.

I created **CanaryGuard AI**, connecting release evidence, policy decisions, and deployment observations. I also lead **NextEdge Analytics**, a privacy-first web analytics venture. My portfolio shows application work, security decisions, academic projects, and the reasoning behind them.

I'm open to **roles and internships in software, cybersecurity, and DevSecOps**, alongside **AI and privacy-focused collaborations, open-source contributions, and relevant partnerships**. I bring practical project experience, an entrepreneurial perspective, and a commitment to learning through useful work.

[Portfolio & project walkthroughs](https://valerie-rwamba-munyi.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/valerie-munyi-48587b2b6/) · [Email me](mailto:valerierwamba1@gmail.com)

## Selected work

### 01 / CanaryGuard AI
**Release review, policy decisions and rollout history in one traceable workflow.**

- **Problem:** Test results, security scans and deployment observations arrive through separate systems. A release needs a decision tied to the exact commit and workflow attempt, followed by a record of whether the rollout continued, promoted or rolled back.
- **My work:** Built TypeScript/Node.js APIs that validate release evidence, verify signed GitHub webhooks and correlate reviews, Check Runs and deployment events under an immutable release identity. Added PostgreSQL persistence for lifecycle history, duplicate-delivery protection and repository-scoped reporting. Deterministic policy blocks failed tests and critical security findings; AI advice cannot override it.
- **Tools:** TypeScript · Node.js · PostgreSQL · Zod · OpenAI SDK · Docker · NGINX · GitHub Actions · Trivy · axe-core · Render.
- **Results & evidence:** At the 9 October 2026 release, 531 tests passed. CI verified the built container, weighted routing, autonomous promotion, rollback and continuation; Render's deployed commit and health response were verified. The MVP supports an optional OpenAI provider and defaults to mock intelligence.

[Source, API contracts & setup](https://github.com/RWAMBA/the-autonomous-canary) · [Verified release checks](https://github.com/RWAMBA/the-autonomous-canary/actions/runs/37977195749)

### 02 / Engineering portfolio
**Accessible project presentation with tested contact delivery.**

- **Problem:** The inherited site needed clearer project contributions, a hero that did not collide with the fixed header, reliable keyboard/mobile navigation and a working contact form.
- **My work:** Customized the Next.js source, reorganized project cards around contribution and implementation evidence, and added focus handling, reduced-motion support and deterministic sitemap generation. Built a server-side Formspree integration with origin checks, bounded fields, a honeypot and an upstream timeout; failed submissions retain the visitor's message.
- **Tools:** Next.js · React · TypeScript · Tailwind CSS · Framer Motion · Playwright · Node.js test runner · Formspree · GitHub Actions · Vercel.
- **Results & evidence:** At the contact release, all 13 automated tests and 19 browser tests passed. Layout checks covered 320–1440px widths; post-merge CI passed, and the owner verified that a live production submission reached Gmail.

[Live portfolio](https://valerie-rwamba-munyi.vercel.app/)

### 03 / Innovation Club Management System
**Member, event and reporting workflows for an academic club system.**

- **Problem:** Club administration requires linked records for members, event registration, attendance, projects and reports, with different views for administrators, patrons and members.
- **My work:** Developed and presented the Elite Academy Innovation Club Management System using PHP and MySQL. Implemented administrator, patron and member views, with local execution through XAMPP and supporting system documentation.
- **Tools:** PHP · MySQL · HTML · CSS · JavaScript · Bootstrap · Apache · XAMPP · phpMyAdmin.
- **Results & evidence:** The March 2026 KNEC Course Specialization Project received **Distinction (Grade 1)**. The portfolio includes login, event-creation and reporting screens from the submitted documentation.

[System screenshots & walkthrough](https://valerie-rwamba-munyi.vercel.app/#works)

### 04 / LearnFlow Platform
**Role-based education workflows with explicit data-access boundaries.**

- **Problem:** Students, guardians, teachers, tutors and administrators need access to different education records. Authentication, account recovery and database permissions must support those role and organization boundaries.
- **My work:** Worked on a Lovable-scaffolded React/TypeScript application with authentication, account recovery, role permissions, curriculum and assessment workflows. The repository includes Supabase migrations, access-policy tests and storage-authorization checks, with architecture and security handoff documents explaining their scope.
- **Tools:** React · TypeScript · TanStack Start/Router/Query · Vite · Tailwind CSS · Supabase · PostgreSQL · Vitest · Playwright · Bun.
- **Results & evidence:** PR checks passed for type checking, lint, tests, build and disposable Supabase migration, row-level security and storage-principal verification. Source and security documents make the access boundaries reviewable; the repository currently lists no public demo. The original brief is retained separately from the implemented application.

[Source, setup & security documentation](https://github.com/RWAMBA/learnflow-platform)

## Tools & technical foundation

[![TypeScript, JavaScript, HTML, CSS, PHP, Bootstrap, React, Next.js, Tailwind CSS, Vite, Node.js, PostgreSQL, Supabase, MySQL, Docker, NGINX, Git, GitHub, GitHub Actions, Vercel, Bun, npm and Linux](https://skillicons.dev/icons?i=ts,js,html,css,php,bootstrap,react,nextjs,tailwind,vite,nodejs,postgres,supabase,mysql,docker,nginx,git,github,githubactions,vercel,bun,npm,linux&perline=8)](https://github.com/RWAMBA?tab=repositories)

| Area | Tools used across my projects |
| --- | --- |
| Languages & interfaces | TypeScript · JavaScript · PHP · HTML · CSS · React · Next.js · Tailwind CSS · Bootstrap · Framer Motion · Radix UI |
| Application & data | Node.js · REST APIs · TanStack Start, Router & Query · Vite · PostgreSQL · Supabase Auth/Storage · MySQL · Zod · OpenAI SDK |
| Delivery & environments | Git · **GitHub** · GitHub Actions · Docker · NGINX · Vercel · Render · Linux · npm · Bun · Apache · XAMPP · phpMyAdmin · Formspree |
| Testing & code quality | Playwright · Vitest · Node.js test runner · Testing Library · axe-core · ESLint · Prettier |
| Security practices | Trivy dependency/container/secret scans · signed-webhook verification · role-based access · Supabase row-level security · input validation · privacy-conscious logging |

## GitHub statistics

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=RWAMBA&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=RWAMBA&theme=github">
  <img alt="RWAMBA's public GitHub statistics: stars, commits, pull requests, issues and contributions" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=RWAMBA&theme=github_dark" width="340">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=RWAMBA&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=RWAMBA&theme=github">
  <img alt="Languages represented in RWAMBA's public repositories" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=RWAMBA&theme=github_dark" width="340">
</picture>

<sub>Cards use public GitHub data and refresh through the card provider's cache. Repository language statistics describe the visible code mix, not proficiency. Private project work is not represented by these cards; GitHub's contribution calendar appears below.</sub>

## How I work

- Define the user workflow, access boundaries and acceptance criteria before implementation.
- Deliver through a verified baseline, isolated branch, reviewed changes, CI and post-deployment checks.
- Test failure paths, authorization and keyboard interactions alongside the expected flow.
- Keep secrets and private client information outside public repositories; document implementation decisions and limits.

## Collaboration & opportunities

I'm open to **software, cybersecurity and DevSecOps roles and internships**, **AI and privacy-focused collaborations**, and **technology partnerships**. My project work spans application delivery, security controls, release automation and product development through CanaryGuard AI and NextEdge Analytics.

**[Contact me](https://valerie-rwamba-munyi.vercel.app/#contact)** · **[LinkedIn](https://www.linkedin.com/in/valerie-munyi-48587b2b6/)**
