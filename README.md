# hey, i'm Khuzayma

<img align="right" width="406" height="408" alt="The Ultimate Programmer’s Den 💻 _ Late Night Coding Vibes" src="https://github.com/user-attachments/assets/e2d9fc88-cde5-4280-96c2-3ab5645c1e52" />


### cs + math @ umass amherst · i build agents and then try to break them

[![LinkedIn](https://img.shields.io/badge/LinkedIn-khuzayma--mushtaq-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khuzayma-mushtaq)
[![Email](https://img.shields.io/badge/Email-kmushtaq@umass.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kmushtaq@umass.edu)

Honors CS student, Math minor, class of '28. SWE intern at Eccountant ERP this past summer, ML fellow at AI4ALL Ignite, Calculus TA in between.

Anyone can chain five API calls behind a prompt. Making that chain fail safely is the part I actually find interesting.

<br clear="right" />

---

### things i've built

### 🤖 Sir Alibi

You confess something you did wrong and an agent drafts the apology email, sends a gift card scaled to how bad it was, schedules the follow-up, and builds a playlist.
I own the backend, the integrations, and Google OAuth. Every step is strict JSON to Zod, one retry, then a deterministic fallback, and a confidence gate that stops the agent before it sends an email it shouldn't. Built at YHack 2026 with a team of four, and the pause gate exists because the first version did not have one.

### 📊 Crewlytics

A manager dashboard that flags who on the team is heading for burnout before they say anything.
Next.js and Prisma on top of Postgres, with a class-balanced logistic regression served through FastAPI at 0.89 ROC-AUC. I tuned the threshold to 0.95 recall on purpose, because missing a burned-out engineer costs more than a false alarm does.

### 💸 PayPerPlay

A Chrome extension that charges you for the seconds of video you actually watch instead of the month you forgot to cancel.
Active-playback detection sends 5-second heartbeats, an Express and SQLite ledger accumulates the session, and settlement lands in USDC on Solana devnet at about $0.00025 a transaction. Won Best Use of Solana at HackDartmouth.

### 🧮 Tax Burden Equity Analyzer

A Random Forest over 61,231 Census filer units predicting effective tax rate, 0.900 R² on a frozen test split.
The number I'd actually defend in an interview is a different one: an imputation bug was quietly corrupting 40% of rows, and rebuilding whole-return income as a family residual moved correlation with AGI from 0.815 to 0.983. The model was never the hard part. AI4ALL Ignite, team of five.

---

### tech stack

**languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**backend & data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

**ml**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-14F195?style=for-the-badge&logo=solana&logoColor=black)

**the ones that write half of it**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

---

### elsewhere

1st place at HackDartmouth · Chancellor's Award · Paul Solli Scholarship · Dean's List 2x · Commonwealth Honors College

Looking for Summer 2027 SWE and ML internships, open to a Spring 2027 co-op. When I'm not coding it's Formula 1, cricket, and a fragrance habit I refuse to justify.
