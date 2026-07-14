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

An **AI coaching agent that teaches you to code and never writes the code for you.** It reads what you write, grades it against a real rubric, tracks what you've actually mastered, and decides the next lesson from the evidence — a personal tutor that observes, explains, and points the way, but makes *you* write every line.

<p align="center">
  <img src="assets/acc-hero-landing.png" alt="AI Code Coach — a live coaching session" width="100%">
</p>

> Private beta in progress — walkthrough available on request.
>
> 📖 **[Read the full case study →](https://github.com/jrletner/ai-code-coach-case-study)** — architecture, the AI teaching model, and how it's built.

### What it does

- **🚫 Never ghostwrites — a hard constraint.** The agent will not complete, fill in, or hand over a single line of your code. Mid-exercise help explains the *concept* with a worked example in a **different** domain and different variable names, so the answer can't leak. The real solution appears only in the post-submission review.

- **🎓 A four-beat teaching loop.** Every lesson runs **Tell → Show → You Do → I Check**: teach from first principles (jargon defined before use), show a runnable commented example in a *different* scenario than the exercise, hand you a blank file to write yourself, then run your code and grade the real output against the requirement — "it ran" ≠ "it's correct."

- **📊 Evidence-based mastery tracking.** Every skill is scored on a 0–100 rubric (Correctness · Tests · Standards · Readability · Concept grasp) and moved through `not started → learning → practiced → mastered` only on objective evidence: a skill is *mastered* only after **two clean, un-hinted reps on separate, spaced occasions.** No self-certification.

- **🚦 Advancement gates that won't let you skip.** You advance past a lesson only when you score ≥ 60 **and** have no blocking skills below `practiced`. Weak areas trigger targeted re-teaching in a new scenario; proven mastery triggers acceleration (compress drills, offer a test-out). The pace adapts in both directions.

- **🔬 Reads the docs *with* you, not *for* you.** Every library lesson teaches you to decode a real VS Code hover signature into plain English yourself — token by token, rating your own confidence — so your reliance on AI drops instead of growing. Verified against current official docs, never taught from memory.

- **📈 Spaced-repetition + adaptive drills.** Standing commands — `drill me`, `leet me`, `test your skills` — pull what's due from a spacing schedule and weight toward your current weak spots. A read-only `how am I doing?` gives an honest snapshot of scores, gaps, and what's next, any time.

- **🛡️ Learner guardrails that watch for trouble.** Silent detectors for frustration, copy-paste/AI-submitted work (met with "walk me through line N"), perfectionism (every task is time-boxed), and vocabulary gaps — each one changes how the agent teaches on the fly.

- **🗺️ A 16-module curriculum to employment-ready.** A fixed dependency ladder from JavaScript and Git fundamentals through TypeScript, React, full-stack Next.js, databases, auth, testing, security, CI/CD, and a three-app AI portfolio (LLM apps, RAG, and agents) — ending interview-ready in the AI niche.

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
