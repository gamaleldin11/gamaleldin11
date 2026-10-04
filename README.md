<div align="center">

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/banner-mobile-dark.svg">
  <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="assets/banner-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Gamaleldin Salem — Full-Stack .NET Engineer. I build AI-integrated financial systems: ASP.NET Core and Angular on the outside, forecasting engines and LLM orchestration underneath. Cairo, Egypt. BSc ×2 Computer Systems Engineering. Open to opportunities. Capabilities: backend, frontend, data, AI and ML." src="assets/banner-dark.svg" width="100%">
</picture>

<br><br>

<a href="https://www.linkedin.com/in/gamaleldin-salem-2046b1220/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a0e17?style=for-the-badge&logo=linkedin&logoColor=5eead4&labelColor=0a0e17">
</a>
<a href="mailto:ge.hazem@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-0a0e17?style=for-the-badge&logo=gmail&logoColor=5eead4&labelColor=0a0e17">
</a>
<a href="https://github.com/gamaleldin11?tab=repositories">
  <img alt="Repositories" src="https://img.shields.io/badge/Repositories-0a0e17?style=for-the-badge&logo=github&logoColor=5eead4&labelColor=0a0e17">
</a>

<!-- Once the portfolio is live on Vercel, uncomment this and put the real URL
     in the href. A badge pointing at a dead link is worse than one badge fewer,
     which is why it ships commented out rather than pointing at a guess.
<a href="https://YOUR-SITE-URL/">
  <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-0a0e17?style=for-the-badge&logo=vercel&logoColor=5eead4&labelColor=0a0e17">
</a>
-->

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=1200&color=5EEAD4&background=0A0E17&center=true&vCenter=true&width=700&height=50&lines=Full-Stack+.NET+Engineer;Building+FinSight,+an+AI+CFO+for+small+businesses;ASP.NET+Core+%2B+Angular+%2B+LLM+orchestration;Author+of+an+8-track+interview+handbook;Open+to+opportunities">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=1200&color=0D9488&background=F7F9FC&center=true&vCenter=true&width=700&height=50&lines=Full-Stack+.NET+Engineer;Building+FinSight,+an+AI+CFO+for+small+businesses;ASP.NET+Core+%2B+Angular+%2B+LLM+orchestration;Author+of+an+8-track+interview+handbook;Open+to+opportunities">
  <img alt="Full-Stack .NET Engineer — Building FinSight, an AI CFO for small businesses — ASP.NET Core + Angular + LLM orchestration — Author of an 8-track interview handbook — Open to opportunities" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=1200&color=5EEAD4&background=0A0E17&center=true&vCenter=true&width=700&height=50&lines=Full-Stack+.NET+Engineer;Building+FinSight,+an+AI+CFO+for+small+businesses;ASP.NET+Core+%2B+Angular+%2B+LLM+orchestration;Author+of+an+8-track+interview+handbook;Open+to+opportunities">
</picture>

</div>

---

## <img src="assets/icons/terminal.svg" width="20" height="20" align="absmiddle" alt=""> Hello

I'm a software engineer working across the full **.NET** stack — C#, ASP.NET Core,
Entity Framework Core and SQL Server on the back end, Angular and TypeScript on
the front.

What actually interests me is the seam where those systems meet machine learning:
forecasting engines, LLM orchestration, and models that have to survive contact
with real users rather than stay in a notebook. (Degrees and certifications are
under [Background](#-background) below.)

Right now I'm a **Tech Specialist intern at Beeviro**, building web applications
for the agency's clients, after finishing the ITI intensive .NET track.

---

## <img src="assets/icons/rocket.svg" width="20" height="20" align="absmiddle" alt=""> What I'm building

> ### FinSight — an AI virtual CFO for small businesses
>
> Most small companies have no financial analyst, so the software has to do the
> analyst's job: notice the problem, quantify it, and say what to do about it.
> FinSight ingests a company's transactions, forecasts 90 days of cash flow,
> detects risk before it becomes a crisis, and explains what it found in plain
> language.

| Source files | Commits | Engineers | DB tables |
|:---:|:---:|:---:|:---:|
| **464** | **115** | **6** | **30** |

**What that involved**

- 17 controllers with command/query-separated DTOs, a generic repository over
  Unit of Work, and multi-tenancy through a scoped tenant service
- JWT bearer auth with an HTTP-only cookie fallback, full issuer/audience/lifetime
  validation, and role-based authorisation over ASP.NET Identity
- **Nixtla TimeGPT** for time-series cash-flow forecasting and **LangFlow**
  for the recommendation and chat layer, orchestrated through LangFlow
- Real-time alerting on **SignalR**, with **Hangfire** running scheduled forecast
  jobs behind an admin-only dashboard
- A 30-table SQL Server schema with code-first migrations and a daily aggregation
  layer for the hot query path
- Health-check endpoints, a global exception handler, environment-aware config,
  and both unit and integration test projects

![C#](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=csharp&logoColor=5eead4 "C#")
![ASP.NET Core](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4 "ASP.NET Core")
![EF Core](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nuget&logoColor=5eead4 "EF Core")
![SQL Server](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=microsoftsqlserver&logoColor=5eead4 "SQL Server")
![Angular 17](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=angular&logoColor=5eead4 "Angular 17")
![SignalR](https://img.shields.io/badge/SignalR-0a0e17?style=flat-square&logoColor=5eead4)
![Hangfire](https://img.shields.io/badge/Hangfire-0a0e17?style=flat-square&logoColor=5eead4)
![TimeGPT](https://img.shields.io/badge/TimeGPT-0a0e17?style=flat-square&logoColor=5eead4)
![LangFlow](https://img.shields.io/badge/LangFlow-0a0e17?style=flat-square&logoColor=5eead4)

[**→ Source**](https://github.com/gamaleldin11/FinSight_G)

<br>

> ### Career Tracks Handbook — eight interview courses in one site
>
> A written course for every role I interview for: frontend, backend, full-stack,
> data analyst, data scientist, data engineer, AI engineer and network &
> connectivity engineer. Every track ends in a system-design stage and a self-test
> whose wrong answers link back to the section to reread.

| Modules | Tracks | Sections | Self-test questions |
|:---:|:---:|:---:|:---:|
| **116** | **8** | **1,491** | **444** |

**What that involved**

- A Node build that turns Markdown modules into one searchable page with a
  per-track sidebar, an Entry / Mid / Senior level filter, a site-wide glossary,
  progress tracking and dark and light themes
- Importers that pull two existing courses (an Obsidian handbook and a hand-written
  HTML bootcamp) into the same site without rewriting them, with maths rendered at
  build time through KaTeX
- A shared system-design series, from the request path and scaling a product
  step by step to reliability patterns and design questions for each role
- Fast-moving facts checked against primary sources, with sources at the end of
  every module
- A strict build that fails on any broken cross-reference, checked in GitHub
  Actions on every push and deployed on Vercel

![Node.js](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nodedotjs&logoColor=5eead4 "Node.js")
![JavaScript](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=javascript&logoColor=5eead4 "JavaScript")
![Markdown](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=markdown&logoColor=5eead4 "Markdown")
![KaTeX](https://img.shields.io/badge/KaTeX-0a0e17?style=flat-square&logoColor=5eead4)
![GitHub Actions](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=githubactions&logoColor=5eead4 "GitHub Actions")
![Vercel](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=vercel&logoColor=5eead4 "Vercel")

[**→ Live site**](https://career-tracks-amber.vercel.app/) &nbsp;·&nbsp; [**→ Source**](https://github.com/gamaleldin11/career-tracks)

---

## <img src="assets/icons/layers.svg" width="20" height="20" align="absmiddle" alt=""> Selected work

<details>
<summary><b>Speech Emotion Recognition</b> — transformer-based emotion classification from raw audio &nbsp;·&nbsp; <code>93% accuracy</code></summary>

<br>

My **graduation project**, graded **4.0 / Excellent**. It classifies emotion from
the acoustic properties of speech rather than from what is said, so it never needs
a transcript.

- Fine-tuned a pretrained **HuBERT** encoder from Hugging Face — linear projection
  to 256 dimensions, dropout regularisation, classification head over the pooled
  temporal representation
- Made the encoder swappable: moving to Wav2Vec2 is a single config change, since
  models load through the `AutoModel` abstraction
- Trained on the **ShEMO** corpus (~3,000 semi-natural utterances, 3h25m of speech)
  with augmentation to counter significant class imbalance
- Shipped as a working desktop application — login, patient records, live
  microphone capture, SQLite persistence — not a notebook
- **93% accuracy**, validated with a confusion matrix across the emotion classes

![Python](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=python&logoColor=5eead4 "Python")
![PyTorch](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=pytorch&logoColor=5eead4 "PyTorch")
![HuBERT](https://img.shields.io/badge/HuBERT-0a0e17?style=flat-square&logoColor=5eead4)
![Hugging Face](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=huggingface&logoColor=5eead4 "Hugging Face")
![SQLite](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=sqlite&logoColor=5eead4 "SQLite")

</details>

<details>
<summary><b>Online Course Store</b> — a teacher's own course shop with Egyptian payment methods</summary>

<br>

An online shop where an independent teacher sells their own courses, so they keep
what they earn instead of paying a marketplace a share of every sale.

- Customers browse, buy and start a course on any device
- **Stripe, Paymob and Fawry** behind one payment interface, so Egyptian customers
  can pay by card or in cash at a kiosk
- Verified payment callbacks, so a course unlocks only once the money has
  actually arrived

![Next.js](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nextdotjs&logoColor=5eead4 "Next.js")
![React](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=react&logoColor=5eead4 "React")
![TypeScript](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=typescript&logoColor=5eead4 "TypeScript")
![PostgreSQL](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=postgresql&logoColor=5eead4 "PostgreSQL")
![Tailwind CSS](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=tailwindcss&logoColor=5eead4 "Tailwind CSS")
![Stripe](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=stripe&logoColor=5eead4 "Stripe")

</details>

<details>
<summary><b>Fractional Investment Platform</b> — Angular SPA for fractional ownership of high-value assets</summary>

<br>

Breaks property, gold and equities into affordable fractional shares, so a user
can build a diversified position without the capital a whole unit would need.
Covers the full journey from landing page to funded, tracked holdings. Built with
a team of five.

- 17 components and 11 routed pages — dashboard, listings, asset detail, checkout,
  deposit funds, authentication
- Route guards for admin access and user-existence checks, plus six injectable
  services covering auth, API access, payments, notifications and projects
- PayPal checkout flow and a built-in chatbot assistant with typing indicators
  and message threading

![Angular](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=angular&logoColor=5eead4)
![TypeScript](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=typescript&logoColor=5eead4)
![RxJS](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=reactivex&logoColor=5eead4)
![Angular Material](https://img.shields.io/badge/Angular_Material-0a0e17?style=flat-square&logoColor=5eead4)

</details>

<details>
<summary><b>Enterprise MVC & Identity Suite</b> — ASP.NET Core MVC with full authentication workflows</summary>

<br>

A pair of applications built to work through the parts of enterprise .NET that
matter in production.

- Full CRUD over a student/department domain via a repository abstraction with
  interfaces, rather than `DbContext` straight from controllers
- Schema evolution through EF Core code-first migrations, including an auth
  migration layered onto an existing schema
- Registration and login on ASP.NET Identity with view models and server-side
  validation, plus a second application demonstrating external OAuth login

![C#](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=csharp&logoColor=5eead4)
![ASP.NET Core MVC](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4)
![EF Core](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nuget&logoColor=5eead4)
![ASP.NET Identity](https://img.shields.io/badge/ASP.NET_Identity-0a0e17?style=flat-square&logoColor=5eead4)
![Razor](https://img.shields.io/badge/Razor-0a0e17?style=flat-square&logoColor=5eead4)

</details>

<details>
<summary><b>FinSight Presentation Engine</b> — an animated slide deck as a web application</summary>

<br>

Rather than exporting slides, I built the presentation as an application:
full-screen animated transitions, keyboard-driven navigation, and a live editor
so content can be corrected mid-presentation without leaving the deck.

Arrows and space to navigate, `E` to edit in place, `R` to replay animations,
`F` for fullscreen. Slide definitions are separated from editable content, so
copy changes never touch layout code.

![React](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=react&logoColor=5eead4)
![TypeScript](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=typescript&logoColor=5eead4)
![Vite](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=vite&logoColor=5eead4)
![TanStack Router](https://img.shields.io/badge/TanStack_Router-0a0e17?style=flat-square&logoColor=5eead4)
![Framer Motion](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=framer&logoColor=5eead4)

</details>

---

## <img src="assets/icons/cpu.svg" width="20" height="20" align="absmiddle" alt=""> Stack

<sub>Hover an icon for its name.</sub>

**Backend**
&nbsp;
![C#](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=csharp&logoColor=5eead4 "C#")
![.NET](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4 ".NET")
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-0a0e17?style=flat-square&logoColor=5eead4)
![EF Core](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nuget&logoColor=5eead4 "EF Core")
![SignalR](https://img.shields.io/badge/SignalR-0a0e17?style=flat-square&logoColor=5eead4)
![Hangfire](https://img.shields.io/badge/Hangfire-0a0e17?style=flat-square&logoColor=5eead4)

**Frontend**
&nbsp;
![Angular](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=angular&logoColor=5eead4 "Angular")
![TypeScript](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=typescript&logoColor=5eead4 "TypeScript")
![RxJS](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=reactivex&logoColor=5eead4 "RxJS")
![React](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=react&logoColor=5eead4 "React")
![Next.js](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nextdotjs&logoColor=5eead4 "Next.js")
![Tailwind CSS](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=tailwindcss&logoColor=5eead4 "Tailwind CSS")
![Chart.js](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=chartdotjs&logoColor=5eead4 "Chart.js")

**Data**
&nbsp;
![SQL Server](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=microsoftsqlserver&logoColor=5eead4 "SQL Server")
![PostgreSQL](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=postgresql&logoColor=5eead4 "PostgreSQL")
![T-SQL](https://img.shields.io/badge/T--SQL-0a0e17?style=flat-square&logoColor=5eead4)
![SQLite](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=sqlite&logoColor=5eead4 "SQLite")

**AI / ML**
&nbsp;
![Python](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=python&logoColor=5eead4 "Python")
![PyTorch](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=pytorch&logoColor=5eead4 "PyTorch")
![Hugging Face](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=huggingface&logoColor=5eead4 "Hugging Face")
![HuBERT](https://img.shields.io/badge/HuBERT-0a0e17?style=flat-square&logoColor=5eead4)
![Claude API](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=anthropic&logoColor=5eead4 "Claude API")

**Systems & tooling**
&nbsp;
![C++](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=cplusplus&logoColor=5eead4 "C++")
![CUDA](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=nvidia&logoColor=5eead4 "CUDA")
![Linux](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=linux&logoColor=5eead4 "Linux")
![Git](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=git&logoColor=5eead4 "Git")
![Docker](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=docker&logoColor=5eead4 "Docker")
![Microsoft Azure](https://img.shields.io/badge/Azure-0a0e17?style=flat-square&logoColor=5eead4)
![GitHub Actions](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=githubactions&logoColor=5eead4 "GitHub Actions")
![Postman](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=postman&logoColor=5eead4 "Postman")
![Jira](https://img.shields.io/badge/-0a0e17?style=flat-square&logo=jira&logoColor=5eead4 "Jira")

---

## <img src="assets/icons/cap.svg" width="20" height="20" align="absmiddle" alt=""> Background

| | | |
|:--:|:--|:--|
| <img src="assets/icons/briefcase.svg" width="18" height="18" alt="Experience"> | **Tech Specialist Intern** | Beeviro, Egypt — Aug 2026 to now |
| <img src="assets/icons/briefcase.svg" width="18" height="18" alt="Experience"> | **Software Development Trainee** | ITI intensive .NET track — Jan to Jul 2026 |
| <img src="assets/icons/briefcase.svg" width="18" height="18" alt="Experience"> | **Implementation Engineer** | Bishara, Kuwait — supporting Farwaniya Hospital's system, 2025 |
| <img src="assets/icons/cap.svg" width="18" height="18" alt="Education"> | **BSc (Hons) Computer Systems Engineering** | University of Greenwich — Second Class Honours, First Division |
| <img src="assets/icons/cap.svg" width="18" height="18" alt="Education"> | **BSc Computer Systems Engineering** | MSA University — GPA 3.11, graduation project graded 4.0 |
| <img src="assets/icons/badge-check.svg" width="18" height="18" alt="Certification"> | **Data Science and Machine Learning** | CLS Learning Solutions — Nov 2025 to Jan 2026 |
| <img src="assets/icons/badge-check.svg" width="18" height="18" alt="Certification"> | **Digitera Technical Track** | ICareer — Sep 2026 |
| <img src="assets/icons/badge-check.svg" width="18" height="18" alt="Certification"> | **Networking & Cybersecurity** | SYSTEL Telecom × Digital Hub — 72 credit hours |
| <img src="assets/icons/badge-check.svg" width="18" height="18" alt="Certification"> | **HCIA-AI** | Huawei × ICT Talent Bank |

Outside the CV: six years volunteering with **Resala Charity Organization**,
teaching English and running IT-literacy classes for people who had never touched
a computer. Arabic native, English fluent.

---

## <img src="assets/icons/pulse.svg" width="20" height="20" align="absmiddle" alt=""> Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=gamaleldin11&show_icons=true&hide_border=true&bg_color=0A0E17&title_color=5EEAD4&icon_color=5EEAD4&text_color=9DB0CF&border_color=22304A">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=gamaleldin11&show_icons=true&hide_border=true&bg_color=F7F9FC&title_color=0D9488&icon_color=0D9488&text_color=4A5B73&border_color=D7E0EC">
  <img alt="gamaleldin11's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=gamaleldin11&show_icons=true&hide_border=true&bg_color=0A0E17&title_color=5EEAD4&icon_color=5EEAD4&text_color=9DB0CF&border_color=22304A" width="49%">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=gamaleldin11&layout=compact&hide_border=true&bg_color=0A0E17&title_color=5EEAD4&text_color=9DB0CF&border_color=22304A">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=gamaleldin11&layout=compact&hide_border=true&bg_color=F7F9FC&title_color=0D9488&text_color=4A5B73&border_color=D7E0EC">
  <img alt="gamaleldin11's most-used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gamaleldin11&layout=compact&hide_border=true&bg_color=0A0E17&title_color=5EEAD4&text_color=9DB0CF&border_color=22304A" width="49%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=gamaleldin11&hide_border=true&background=0A0E17&stroke=22304A&ring=5EEAD4&fire=5EEAD4&currStreakNum=E8EEFB&sideNums=E8EEFB&currStreakLabel=5EEAD4&sideLabels=9DB0CF&dates=5C6B82">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=gamaleldin11&hide_border=true&background=F7F9FC&stroke=D7E0EC&ring=0D9488&fire=0D9488&currStreakNum=101828&sideNums=101828&currStreakLabel=0D9488&sideLabels=4A5B73&dates=77879E">
  <img alt="gamaleldin11's contribution streak" src="https://streak-stats.demolab.com/?user=gamaleldin11&hide_border=true&background=0A0E17&stroke=22304A&ring=5EEAD4&fire=5EEAD4&currStreakNum=E8EEFB&sideNums=E8EEFB&currStreakLabel=5EEAD4&sideLabels=9DB0CF&dates=5C6B82" width="70%">
</picture>

<!-- Regenerated daily by .github/workflows/snake.yml onto the `output`
     branch — see that workflow for how the snake and its theming are
     produced. The two images below 404 until that workflow has run once. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gamaleldin11/gamaleldin11/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gamaleldin11/gamaleldin11/output/snake.svg">
  <img alt="A snake animation eating the squares of gamaleldin11's GitHub contribution graph" src="https://raw.githubusercontent.com/gamaleldin11/gamaleldin11/output/snake-dark.svg" width="100%">
</picture>

</div>

---

<div align="center">

### <img src="assets/icons/mail.svg" width="20" height="20" align="absmiddle" alt=""> Let's build something

The fastest way to reach me is email.

<a href="mailto:ge.hazem@gmail.com">
  <img alt="ge.hazem@gmail.com" src="https://img.shields.io/badge/ge.hazem@gmail.com-0a0e17?style=for-the-badge&logo=gmail&logoColor=5eead4&labelColor=0a0e17">
</a>
<a href="https://www.linkedin.com/in/gamaleldin-salem-2046b1220/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a0e17?style=for-the-badge&logo=linkedin&logoColor=5eead4&labelColor=0a0e17">
</a>

<sub>Cairo, Egypt &nbsp;·&nbsp; open to full-stack and .NET engineering roles</sub>

</div>
