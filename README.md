<div align="center">

# AlgoVizuals

**See the algorithm. Solve the problem. Land the interview.**

*A next-generation platform for mastering algorithms through step-by-step trace visualizations, rigorous practice, and AI-powered mentorship.*

---

![Status](https://img.shields.io/badge/status-live-success?style=flat-square)
![Region](https://img.shields.io/badge/region-ap--south--1-blue?style=flat-square)
![Stack](https://img.shields.io/badge/stack-Next.js%20%7C%20FastAPI%20%7C%20Postgres-black?style=flat-square)
![Made with](https://img.shields.io/badge/made%20with-care-ff69b4?style=flat-square)

</div>

---

## What is AlgoVisuals?

AlgoVisuals is a learning platform built around a simple belief:

> *Algorithms click when you can **see** them run.*

We pair the rigor of a competitive-coding judge with the clarity of a great teacher — every problem ships with **animated, step-by-step traces** of every solution approach, so learners don't just submit code, they understand it.

## The Product

| Pillar | What it does |
|--------|--------------|
| **Problem Library** | A curated catalogue of interview-grade problems — Easy, Medium, Hard — with crisp statements, edge cases, and starter code in multiple languages. |
| **Trial Run & Submission** | An in-editor *Run* button for fast iteration plus a graded *Submit* path that updates streaks and acceptance rate. |
| **Trace Visualizer** | Each accepted approach has a hand-built or AI-generated *Trace* — a step-by-step replay of the algorithm executing on real input. |
| **Daily Challenge** | One Easy, one Medium, one Hard — refreshed at UTC midnight, shared globally, never repeating within 7 days. |
| **Streaks** | Consecutive-day momentum, with *Restoration Tickets* so a single missed day doesn't undo a month of work. |
| **Editorials** | Beginner-friendly, worked-example walkthroughs for every optimal solution — not just a wall of code. |

## Why we built it

LeetCode-style platforms test you. Textbooks explain to you. Almost nothing **shows** you what a heap rebalances into, or how a sliding window actually slides. That gap is where most learners stall. AlgoVisuals closes it.

## The Stack

A polyglot workspace of focused services, each in its own repo:

```
algovisuals/
├── service/              FastAPI backend — problems, submissions, streaks
├── judge-service/        Sandboxed code execution and grading
├── ui/                   Next.js frontend
├── algovisuals-problems/ Problem definitions, test cases, trace generators
├── algovisuals-deploy/   AWS CDK infra (api gw + lambda + RDS + judge VM)
└── docs/                 Workspace-level documentation
```

**Deployed on AWS** (ap-south-1) with API Gateway, Lambda, RDS Postgres, a dedicated judge VM, and GitHub Actions CI/CD via OIDC.

---

## Where We're Going

We're heads-down on three tracks for the next quarter:

### Now: Polish & Depth
- Visualizer overhaul — smoother animations, better edge-case rendering, side-by-side compare across approaches.
- Editorial redesign — every optimal solution gets the *teach-a-beginner* treatment.
- Problem audit — quality pass across the full catalogue.

### Next: Reach
- Public profiles, shareable trace links, and a lightweight discussion layer.
- Mobile-first reading experience for editorials and traces.

---

## The Big Bets — Future Roadmap

These are the moves we believe will define the next chapter of AlgoVisuals.

### 1. AI-Powered Voice-Interactive Tutor

A real-time, conversational tutor you can **talk to** while you solve.

- **Think aloud, get nudged.** Walk through your approach verbally — the tutor listens, asks clarifying questions, and points out gaps without spoiling the answer.
- **Socratic by default.** Hints are progressive: a gentle nudge first, then a stronger one, then a worked partial step — never the full solution unless you ask.
- **Code-aware.** The tutor sees your editor state, your test results, and the problem's trace data, so its guidance is grounded in *your* code, not generic advice.
- **Interview simulation.** A "mock interview" mode where the tutor plays the role of a senior engineer — timed, probing, with a written debrief at the end.

> *The goal: every learner gets a patient, infinitely-available mentor — the kind that, until now, only the luckiest among us had.*

### 2. Focused Interview Prep — Study Plans

Personalized, time-boxed roadmaps that turn *"I have an interview in 6 weeks"* into a concrete daily plan.

- **Target the role.** Pick your target company tier and role (frontend, backend, systems, ML) — the plan adapts to the patterns those interviews actually test.
- **Calibrated difficulty.** A short diagnostic gauges your current level; the plan starts where *you* are, not at problem #1.
- **Pattern-first sequencing.** Topics are ordered the way they build on each other — two pointers → sliding window → monotonic deque — not alphabetically.
- **Daily rhythm.** Each day mixes a new concept, a guided problem, a fresh problem, and spaced-repetition review of past stumbles.
- **Progress that means something.** Mastery is measured by problems solved *without hints* on first attempt, not raw submission count.

> *The goal: replace the anxiety of "what do I study tonight?" with a plan you can trust.*

---

## Get Involved

AlgoVisuals is built in the open across this workspace. If you're a learner, an educator, or just curious — explore the repos, file issues, and tell us what's missing.

- **Product:** [algovizuals.com](https://algovizuals.com) *(replace with live URL)*
- **Issues & feedback:** open a GitHub issue on any of the service repos
- **Contact:** [vashiraj2000@gmail.com](mailto:vashiraj2000@gmail.com)

---

<div align="center">

*Built with rigor. Designed for clarity. Made for the next generation of engineers.*

**AlgoVisuals**

</div>
