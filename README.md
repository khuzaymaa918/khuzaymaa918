# Hi, I'm Khuzayma 👋

**CS + Math @ UMass Amherst (Honors, '28) · I build agents, backends, and the data pipelines underneath them**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-khuzayma--mushtaq-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khuzayma-mushtaq)
[![Email](https://img.shields.io/badge/Email-kmushtaq@umass.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kmushtaq@umass.edu)
[![Location](https://img.shields.io/badge/Amherst,_MA-171515?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

---

## About me

I'm a junior at UMass Amherst studying Computer Science with a Math minor. Most of what I build sits in the same place: an interface someone actually uses, an API and a database behind it, and something smarter than a CRUD endpoint making decisions in the middle.

This past summer I was a Software Engineer Intern at **Eccountant ERP** in Lahore, shipping full-stack features and Python REST APIs across inventory, sales, procurement, and finance modules of a cloud ERP used by small and mid-size businesses. The summer before that I was at **The Game Storm Studios**, writing C# event-driven logging and telemetry pipelines for a Unity mobile title on iOS and Android.

Right now I'm a **Machine Learning Fellow at AI4ALL Ignite**, where my team built a tax equity model on 61k Census filer units, and a **Calculus TA** at UMass, where I redesign partial-credit rubrics and run exam review workshops.

What I keep coming back to is agent reliability. Anyone can chain five API calls behind a prompt. Making that chain fail safely, validate its own output, and know when to stop and ask a human is the part I find genuinely hard and genuinely interesting.

Off the keyboard: Formula 1, cricket, and an ongoing fragrance habit I refuse to justify.

---

## What I'm building

**🤖 [Sir Alibi](https://github.com/khuzaymaa918/sir-alibi)** · TypeScript, Node.js, OpenAI API, Google OAuth 2.0
An autonomous relationship-repair agent built at YHack 2026 with a team of four. You confess an incident and it drafts a Gmail apology, sends a gift card scaled to severity, schedules a follow-up, and builds a playlist. I owned the backend, the integrations, and Google OAuth. The pipeline runs Confess → Perceive → Research → Pause Gate → Reason → Write → Execute, with strict JSON to Zod validation, one automatic retry, and a deterministic fallback at every step. The Pause Gate is the piece I care about most: it stops the agent on low confidence instead of letting it send an email it shouldn't.

**📊 [Crewlytics](https://github.com/khuzaymaa918/Crewlytics)** · Next.js, TypeScript, FastAPI, scikit-learn, PostgreSQL
A manager-facing capacity dashboard that flags teammates heading toward burnout and suggests reassignments. Team project. 13 REST routes, NextAuth, a Prisma-backed Postgres schema, a custom TypeScript matching algorithm tested with Vitest, and a class-balanced logistic regression served through a FastAPI endpoint at 0.89 ROC-AUC. Tuned the threshold to 0.95 recall on purpose: missing a burned-out engineer costs more than a false alarm.

**💸 [PayPerPlay](https://github.com/khuzaymaa918/PayPerPlay)** · TypeScript, Express, SQLite, Solana Web3.js, Chrome MV3
Pay for the seconds of video you actually watch, not the subscription. A Chrome extension detects active playback and sends 5-second payment heartbeats; an Express and SQLite ledger accumulates the session and settles it in USDC on Solana devnet, with every transfer verified by signature at roughly $0.00025 per transaction.

**🧮 [Tax Burden Equity Analyzer](https://tax-burden-equity-analyzer.fly.dev)** · Python, scikit-learn, SHAP
AI4ALL Ignite research project, team of five. A 500-tree Random Forest over 61,231 IPUMS CPS filer units predicting effective tax rate, 0.900 R² and 1.28pp MAE on a frozen 12,247-row test split. The part I'd actually talk about in an interview is the bug: an income imputation defect was corrupting 40% of rows, and reconstructing whole-return income as a family residual pulled correlation with AGI from 0.815 to 0.983. TreeSHAP counterfactuals then isolated a 2.35-point gap between wage and investment income at the same earnings.

---

## Experience

| | | |
|---|---|---|
| **Eccountant ERP** | Software Engineer Intern | Jun 2026 – Aug 2026 · Lahore |
| **AI4ALL Ignite** | Machine Learning Fellow | May 2026 – Present · Remote |
| **UMass Amherst** | Undergraduate Teaching Assistant, Calculus I & II | Sep 2025 – Present · Amherst, MA |
| **The Game Storm Studios** | Software Engineer Intern | Jun 2025 – Aug 2025 · Lahore |

---

## Tech I work with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend & frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)

**Data & ML**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-14F195?style=for-the-badge&logo=solana&logoColor=black)

---

## Honors

🥇 **1st Place, HackDartmouth** — Best Use of Solana
🎓 **Chancellor's Award Scholarship** — renewable, four years
🎓 **Paul Solli Scholarship** — renewable, four years
📘 **Dean's List** — 2x
🏛 **Commonwealth Honors College**, Multidisciplinary Honors

---

## What's next

I'm looking for **Summer 2027 software engineering and ML internships**, and I'm open to a Spring 2027 co-op. I'm most drawn to teams working on developer tools, agent infrastructure, and anything where reliability of a model in production is the actual problem.

Currently going deeper on deep learning frameworks and on evaluation for LLM systems, because API orchestration only takes you so far.

If you're building something in that space, or you just want to argue about whether an agent should ever be allowed to send an email unsupervised, [say hi](mailto:kmushtaq@umass.edu).
