<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0b1220,100:111827&height=110&section=header&text=Kristian%20L%C3%B6vey&fontSize=42&fontColor=E5E7EB&desc=Azure%20%26%20Agentic%20AI%20%E2%80%A2%20Junior%20Technical%20Consultant%20%40%20Nephos%20%E2%80%A2%20M.Sc.%20@%20FER&descAlignY=75&descSize=15" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kristianlovey/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ki@tamaralovey.com)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/kristian.lovey)

</div>

---

### Hi, I'm Kristian

I build agentic AI systems on Azure by day and ship full-stack products by night. Currently finishing my **M.Sc. in Computer Engineering at FER** while working as a **Junior Technical Consultant at Nephos**, where I design and deploy autonomous, goal-driven systems with Azure OpenAI Service and Azure AI Foundry — from prompt and agent orchestration through to production deployment.

Everything I build outside work starts the same way: I notice something in my own life taking longer than it should, and I'd rather build the thing that speeds it up than keep doing it by hand. Writing training programs, tailoring a resume for every job posting, tracking focused work — each of those became a project. I'm also a competitive powerlifter and strength coach, so a lot of it lands somewhere between training data and software.

**Interests:** agentic workflows and multi-agent orchestration · cloud architecture on Azure · LLM pipelines that have to be reliable, not just impressive · applied ML on sensor data

---

### Featured Projects

#### LiftAI — AI strength coach *(Feb 2026 – present)*
A web and mobile app where an AI coach actually behaves like one. **The Coach** is a Gemini-based agent that interviews a lifter about their experience, goals and available equipment, then writes a structured powerlifting program that lands directly in a set-by-set tracker. Every morning the lifter rates sleep, energy, nutrition and hydration — if readiness is poor, the coach flags it and proposes concrete adjustments ("drop bench to 95 kg today, cap at RPE 7"), which the lifter can push back on and negotiate in chat.

I own the **AI pipeline** — prompt design, structured JSON output with schema enforcement, and provider fallback between LLMs — plus all of the **training logic**, the programming rules the model is constrained to follow.

`Gemini` · `Structured output / schema enforcement` · `Multi-provider fallback` · `Web + mobile`

#### LWL UP — powerlifting coaching platform *(Mar 2026 – present)* · [lwlup.com](https://lwlup.com)
A full-stack platform that puts coaches and lifters in one workspace. Coaches build periodized training across **blocks → weeks → days → exercises** with per-set planning (weight, reps, RPE, top sets, percentage back-offs). Lifters log through an optimistic, lag-free input flow and coaches see every entry land via real-time sync.

The analytics dashboard turns logged sets into insight: estimated 1RM progression using an RTS RPE/reps → %1RM model, actual top-set trends, training compliance, weekly volume by lift and variation, bodyweight trends, a strength-balance radar and a projected competition total — with progress charts annotated by training block so trends are read in context. Also includes a meet tracker, reusable block templates, a per-lifter priority scheduler and a yearly block-plan timeline.

Role-based access (admin / coach / lifter) is enforced with **Row-Level Security** plus service-role API routes for privileged actions.

`Next.js 14 (App Router)` · `TypeScript` · `Supabase (PostgreSQL, Auth, RLS, Realtime)` · `Custom dark-theme design system`

#### Resume Hunter — AI job application platform *(Jun 2026 – Jul 2026)*
Instead of rewriting a resume for every posting, you build your profile once — experience, education, skills, tone — then paste a job link. The system reads the posting, identifies its core requirements, and generates a tailored resume and cover letter aimed at exactly what that employer is looking for. Includes tone selection (professional / confident / friendly) and a dashboard tracking every application and version sent.

Cuts application time from roughly an hour to about two minutes per position.

`Next.js 16` · `React 19` · `TypeScript` · `Supabase (Auth + RLS)` · `Google AI` · `Tailwind CSS` · deployed on Vercel

#### PoppyTimer — focus dashboard *(Mar 2026 – present, WIP)*
Every tool I want for focused work in one warm, pastel, minimal interface: a Pomodoro timer with progress ring, session tracking and auto-repeat; a stopwatch with tagged activities and saved history; custom countdown timers with color coding and presets; a monthly calendar overview; and a notes editor with highlight and underline. Glassmorphism styling, Poppins throughout — productivity should feel pleasant.

Auth and cross-device data sync are next.

`Next.js 14 (App Router)` · `TypeScript` · `Tailwind CSS` · `Supabase` · `date-fns` · `lucide-react`

---

### Research

**Human Activity Recognition with mmWave Radar** — my Master's project and ongoing seminar work. Contactless activity classification using a **Texas Instruments IWR6843AOPEVM** sensor: range profiles of 129 bins per frame, windowed into 64 frames (~3.2 s) as network input. Activities are organised hierarchically into static classes (empty room, standing, sitting, lying, reading) and dynamic ones (walking, running, jumping, falling, crawling).

The baseline is a two-layer **LSTM** with 128 hidden units and dropout regularization; Conv1D+LSTM, TCN and Transformer-encoder variants are in progress. Target applications are smart homes and elderly-care monitoring, where radar preserves privacy in a way cameras cannot.

`PyTorch` · `FMCW radar` · `LSTM / TCN / Transformer` · `Signal processing`

---

### Other Repositories

| Repository | What it is | Stack |
| :--- | :--- | :--- |
| **Diplomski-projekt** | mmWave radar HAR — dataset pipeline, training, evaluation | Python, PyTorch |
| **eZgrada** | Full-stack residential building management app | React, .NET Core, PostgreSQL |
| **ML-Projekt-Vicuna** | Time-series forecasting of stock returns from historical data | Python, scikit-learn |
| **NM_GeneriranjePjesma** | Automated song generation | Python |
| **statisticko-analizirani** | Statistical data analysis project (SAP) | R |

---

### Tech Stack

| Category | Tools |
| :--- | :--- |
| **Cloud & AI** | Azure, Azure OpenAI Service, Azure AI Foundry, agentic workflows, multi-agent orchestration |
| **ML** | PyTorch, TensorFlow, scikit-learn, LSTM/TCN/Transformer architectures |
| **Web** | Next.js 14/16, React 19, TypeScript, .NET Core, Tailwind CSS, Framer Motion |
| **Data** | Supabase, PostgreSQL, Row-Level Security, SQL |
| **Languages** | Python, TypeScript, JavaScript, Java, C/C++, R, Bash |
| **Embedded & IoT** | ESP32 / ESP32-C6, ESP-IDF, FreeRTOS, MQTT, TI mmWave sensors, XBee/ZigBee |
| **Tooling** | GitHub Actions, Vercel, Unity |

---

### Certifications

- Microsoft Certified: **Azure AI Fundamentals** (AI-900)
- Microsoft Certified: **Azure Fundamentals** (AZ-900)
- **SQL (Intermediate)** Certificate
- Introduction to Data Analysis using Microsoft Excel

---

### Beyond the Code

Years under a heavy bar taught me patience, discipline and the stubbornness to keep solving a problem long after the initial excitement wears off. I bring the same persistence to systems that have to stay up.

Competitive **powerlifting** · **skiing** · **traveling**

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KristianLovey&theme=dracula&hide_border=false&include_all_commits=true&count_private=true" height="170px" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KristianLovey&theme=dracula&hide_border=false&include_all_commits=true&count_private=true&layout=compact" height="170px" />

</div>
