# Math Foundation Rebuild — Control Systems Track

> You cannot build excellence on a foundation you have refused to repair.

A 14-week, self-paced roadmap to rebuild the mathematics needed for Control Systems Engineering — from the ground up. Built by a 2015 Electrical/Electronic Engineering graduate (3.52/5.0) and secondary school Mathematics teacher returning to graduate studies via Erasmus Mundus EU-CORE.

This is not a crash course. It is a foundation repair.

**Live Roadmap:** `https://udohlawrence.github.io/math-rebuild/`  
**Daily commitment:** 2 hours weekdays at 6pm, 3 hours Saturday Power Block

---

## Why this exists

I tried jumping straight back into undergraduate engineering maths and felt overwhelmed. I realized I had studied to pass exams, not to understand.

Inspired by the idea that the greatest progress is sometimes having the humility to go back to basics, I decided to rebuild properly:

### Core Fluency → Calculus Intuition → Linear Algebra + ODEs → Transforms & Stability

Teaching secondary maths kept my algebra sharp, but Control needs eigenvalues, Laplace, state-space — and those only stick when the floor underneath is solid.

## Who this is for

- EE grads returning after years away
- Teachers, self-learners, anyone who feels rusty on the maths behind control
- Applicants preparing for Control-focused masters like EU-CORE, EU4M

## Structure — 98 days

**Phase 1 — Core Fluency (Weeks 1-2)**
Complex numbers in Euler form, trig as phasors, vectors, functions. Goal: explain why $e^{j\pi} = -1$ without hand-waving.

**Phase 2 — Calculus as Intuition (Weeks 3-5)**
Limits as approximation, derivative as sensitivity, integral as accumulation. Connection: P, I, D.

**Phase 3 — The Control Core (Weeks 6-10)**
Matrices as transformations, eigenvalues as system modes, rank/nullspace, solving linear ODEs, $\dot{x}=Ax+Bu$.

**Phase 4 — Transforms & Stability (Weeks 11-14)**
Laplace, transfer functions, stability, Bode and root locus. Ends with a DC motor PID project.

## How I study each day — the 2-hour block

0-50m **Concept Deep Dive** — one topic, write definition in own words
50-80m **Hand Problems** — 3-4 problems, no calculator, show steps
80-100m **Teach-Back** — explain it in 30 seconds as if to SS2, record voice note
100-120m **Log** — What clicked? Where did I go back one step? Question for tomorrow?

Saturday: 3hr Power Block — synthesis + Python/【entity-MATLAB¦canonical_name=MATLAB】 + redo Monday without notes
Sunday: 30 min light review

## Features of this roadmap site

- Expandable daily cards with learning objectives, key definitions, why it matters for Control
- 3-4 mastery problems per day with hints and "mastery looks like" criteria
- 4-prompt daily log + confidence slider 1-5
- Weekly synthesis
- Persistent progress tracking — saves on reload via localStorage
- Single static file, hostable on GitHub Pages, no backend

## How to use

1. Open `index.html` — it is the whole site
2. Work through Day 1 → Day 98. Tick Concept / Hand Problems / Teach-Back / Log
3. Your progress, logs and streak survive reloads
4. Export snapshot via Copy button when you want a backup

## Host on GitHub Pages

1. Create repo: `math-rebuild`
2. Upload `index.html` to root
3. Settings → Pages → Source: Deploy from main branch, /root
4. Your site will be live at `https://yourusername.github.io/math-rebuild/`

## Tech

Vanilla HTML/CSS/JS. No frameworks. localStorage key: `math-rebuild`.

## Roadmap to Erasmus Mundus

This rebuild is designed to meet the maths prerequisites listed by programmes like EU-CORE: Linear algebra, Multivariable analysis, Transforms, Mathematical Statistics, plus Automatic Control. The final project (DC motor PID + state-feedback simulation) serves as proof of current ability for applications where professional experience is considered alongside grades.

## License

MIT — use, adapt, teach with it.

---

Built with humility, 2 hours at a time.
