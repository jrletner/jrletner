<h1 align="center">Hi, I'm Joe 👋</h1>
<h3 align="center">I build AI-powered products.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/React-149ECA?logo=react&logoColor=white" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Claude-D97757?logo=anthropic&logoColor=white" alt="Claude">
</p>

---

## 🚀 AI Code Coach &nbsp;<sub>🚧 in active development</sub>

An **AI coding tutor that reads a student's code and coaches them** — it observes, explains, and points the way, but never writes their code for them. I'm building the tutor I wished my own students had.

<p align="center">
  <img src="assets/acc-hero-landing.png" alt="AI Code Coach — a live coaching session" width="100%">
</p>

**Built with**

<p>
  <img src="https://img.shields.io/badge/Next.js_16-000000?logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Better_Auth-1A1A1A" alt="Better Auth">
  <img src="https://img.shields.io/badge/Neon_Postgres-008B8B?logo=postgresql&logoColor=white" alt="Neon Postgres">
  <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?logo=drizzle&logoColor=black" alt="Drizzle ORM">
  <img src="https://img.shields.io/badge/Vercel_AI_SDK_+_Claude-000000?logo=vercel&logoColor=white" alt="Vercel AI SDK + Claude">
  <img src="https://img.shields.io/badge/Upstash-00E9A3?logo=upstash&logoColor=white" alt="Upstash">
  <img src="https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white" alt="Stripe">
  <img src="https://img.shields.io/badge/Tailwind-38BDF8?logo=tailwindcss&logoColor=white" alt="Tailwind">
</p>

> Private beta in progress — walkthrough available on request.

### How it uses AI to teach

The coaching model *is* the product. The system prompt is engineered around a few hard rules:

- **A no-code hard constraint** — the AI never writes, completes, or fills in a single line of the student's code. It reads their code and gives line-specific observations; any worked example uses a *different* domain and variable names so it can't leak the answer.
- **Socratic by design** — instead of handing over a solution, it asks the next guiding question and lets the student write it. (See the FizzBuzz exchange below.)
- **Adapts to the learner** — selectable learning style (visual, with auto-generated Mermaid diagrams; step-by-step; or Socratic), four skill levels, and a strictness/tone dial from warm-and-encouraging to direct-and-unsparing.
- **Prompt-injection safe** — student code and rendered output are passed to the model strictly as data, never as instructions, so lesson content can't hijack the coach.

<p align="center">
  <img src="assets/acc-how-it-works.png" alt="The method: write first, get coached, tuned to you" width="100%">
</p>
<p align="center"><em>The method: write it yourself first, get coached (never corrected), tuned to your level.</em></p>

<p align="center">
  <img src="assets/acc-compare.png" alt="Coach vs ghostwriter — the AI asks a guiding question instead of writing the code" width="100%">
</p>
<p align="center"><em>Same question, two answers: a ghostwriter hands over the code; the coach asks what the remainder should be.</em></p>

## 🧰 Tech I work with

**Frontend** — React · Next.js · TypeScript · Tailwind · shadcn/ui
**Backend** — Node · Drizzle ORM · Postgres · MongoDB
**AI** — Vercel AI SDK · Claude · LLM app architecture · prompt engineering

## 🛠 Projects

A few of the repos I also use to teach people to code:

- **[FE_Lectures](https://github.com/jrletner/FE_Lectures)** — Live-coded front-end lessons. *6 student forks.*
- **[react_todo](https://github.com/jrletner/react_todo)** — Full-stack reference app: React + TypeScript + Node/Express + MongoDB.
- **[vanilla_js_todo](https://github.com/jrletner/vanilla_js_todo)** — Framework-free JS fundamentals: DOM, fetch, state, CRUD from scratch.

## 📫 Connect

✉️ jrletner@gmail.com &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/joe-letner-4a37ba99/)
