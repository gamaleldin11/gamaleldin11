<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Gamaleldin Salem — Full-Stack .NET Engineer. I build AI-integrated financial systems: ASP.NET Core and Angular on the outside, forecasting engines and LLM orchestration underneath. Giza, Egypt. BSc ×2 Computer Systems Engineering. Open to opportunities." src="assets/banner-dark.svg" width="100%">
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

</div>

---

## Hello 

I'm a software engineer working across the full **.NET** stack — C#, ASP.NET Core,
Entity Framework Core and SQL Server on the back end, Angular and TypeScript on
the front.

What actually interests me is the seam where those systems meet machine learning:
forecasting engines, LLM orchestration, and models that have to survive contact
with real users rather than stay in a notebook.

I hold **two BSc degrees in Computer Systems Engineering** — University of
Greenwich and MSA University — and completed the **ITI intensive .NET Track**.

---

## What I'm building

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

<sub>`C#` · `ASP.NET Core` · `EF Core` · `SQL Server` · `Angular 17` · `SignalR` · `Hangfire` · `TimeGPT` · `LangFlow`</sub>

[**→ Source**](https://github.com/gamaleldin11/FinSight_G)

---

## Selected work

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

<sub>`Python` · `PyTorch` · `HuBERT` · `Hugging Face` · `SQLite`</sub>

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

<sub>`Angular` · `TypeScript` · `RxJS` · `Angular Material`</sub>

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

<sub>`C#` · `ASP.NET Core MVC` · `EF Core` · `ASP.NET Identity` · `Razor`</sub>

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

<sub>`React` · `TypeScript` · `Vite` · `TanStack Router` · `Framer Motion`</sub>

</details>

---

## Stack

**Backend**

![C#](https://img.shields.io/badge/C%23-0a0e17?style=flat-square&logo=csharp&logoColor=5eead4)
![.NET](https://img.shields.io/badge/.NET-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4)
![EF Core](https://img.shields.io/badge/EF_Core-0a0e17?style=flat-square&logo=nuget&logoColor=5eead4)
![SignalR](https://img.shields.io/badge/SignalR-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4)
![Hangfire](https://img.shields.io/badge/Hangfire-0a0e17?style=flat-square&logo=dotnet&logoColor=5eead4)

**Frontend**

![Angular](https://img.shields.io/badge/Angular-0a0e17?style=flat-square&logo=angular&logoColor=5eead4)
![TypeScript](https://img.shields.io/badge/TypeScript-0a0e17?style=flat-square&logo=typescript&logoColor=5eead4)
![RxJS](https://img.shields.io/badge/RxJS-0a0e17?style=flat-square&logo=reactivex&logoColor=5eead4)
![React](https://img.shields.io/badge/React-0a0e17?style=flat-square&logo=react&logoColor=5eead4)
![Chart.js](https://img.shields.io/badge/Chart.js-0a0e17?style=flat-square&logo=chartdotjs&logoColor=5eead4)

**Data**

![SQL Server](https://img.shields.io/badge/SQL_Server-0a0e17?style=flat-square&logo=microsoftsqlserver&logoColor=5eead4)
![T-SQL](https://img.shields.io/badge/T--SQL-0a0e17?style=flat-square&logo=microsoftsqlserver&logoColor=5eead4)
![SQLite](https://img.shields.io/badge/SQLite-0a0e17?style=flat-square&logo=sqlite&logoColor=5eead4)

**AI / ML**

![Python](https://img.shields.io/badge/Python-0a0e17?style=flat-square&logo=python&logoColor=5eead4)
![PyTorch](https://img.shields.io/badge/PyTorch-0a0e17?style=flat-square&logo=pytorch&logoColor=5eead4)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-0a0e17?style=flat-square&logo=huggingface&logoColor=5eead4)
![HuBERT](https://img.shields.io/badge/HuBERT-0a0e17?style=flat-square&logo=pytorch&logoColor=5eead4)
![Claude API](https://img.shields.io/badge/Claude_API-0a0e17?style=flat-square&logo=anthropic&logoColor=5eead4)

**Systems & tooling**

![C++](https://img.shields.io/badge/C%2B%2B-0a0e17?style=flat-square&logo=cplusplus&logoColor=5eead4)
![CUDA](https://img.shields.io/badge/CUDA-0a0e17?style=flat-square&logo=nvidia&logoColor=5eead4)
![Linux](https://img.shields.io/badge/Linux-0a0e17?style=flat-square&logo=linux&logoColor=5eead4)
![Git](https://img.shields.io/badge/Git-0a0e17?style=flat-square&logo=git&logoColor=5eead4)
![Docker](https://img.shields.io/badge/Docker-0a0e17?style=flat-square&logo=docker&logoColor=5eead4)
![Postman](https://img.shields.io/badge/Postman-0a0e17?style=flat-square&logo=postman&logoColor=5eead4)
![Jira](https://img.shields.io/badge/Jira-0a0e17?style=flat-square&logo=jira&logoColor=5eead4)

---

## Background

| | |
|:--|:--|
| **BSc (Hons) Computer Systems Engineering** | University of Greenwich — Second Class Honours, First Division |
| **BSc Computer Systems Engineering** | MSA University — GPA 3.11, graduation project graded 4.0 |
| **Intensive .NET Track** | Information Technology Institute (ITI) |
| **Implementation Engineer** | Bishara — Kuwait |
| **Networking & Cybersecurity** | SYSTEL Telecom × Digital Hub — 72 credit hours |
| **HCIA-AI** | Huawei × ICT Talent Bank |

Outside the CV: six years volunteering with **Resala Charity Organization**,
teaching English and running IT-literacy classes for people who had never touched
a computer. Arabic native, English fluent.

---

<div align="center">

### Let's build something

The fastest way to reach me is email.

<a href="mailto:ge.hazem@gmail.com">
  <img alt="ge.hazem@gmail.com" src="https://img.shields.io/badge/ge.hazem@gmail.com-0a0e17?style=for-the-badge&logo=gmail&logoColor=5eead4&labelColor=0a0e17">
</a>
<a href="https://www.linkedin.com/in/gamaleldin-salem-2046b1220/">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a0e17?style=for-the-badge&logo=linkedin&logoColor=5eead4&labelColor=0a0e17">
</a>

<sub>Giza, Egypt &nbsp;·&nbsp; open to full-stack and .NET engineering roles</sub>

</div>
