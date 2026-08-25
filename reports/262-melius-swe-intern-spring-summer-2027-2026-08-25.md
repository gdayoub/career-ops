# 262 — Melius: Software Engineering Intern [Spring/Summer 2027]

**Score:** 3.7/5  
**URL:** https://jobs.ashbyhq.com/melius/b61f063a-4f94-4e50-a4ef-05aaab552280  
**PDF:** ❌  
**Date:** 2026-08-25  
**Verification:** unconfirmed (batch mode — Ashby EGRESS_BLOCKED; job surfaced via WebSearch)

---

## A — Company

**Melius** is building the "agents lab for creative work" — described as a real-time AI operating system where humans and agents generate, orchestrate, and scale next-generation media workflows together. Product site: melius.com / trymelius.com.

- Stage: Early-stage startup (funding unconfirmed publicly)
- Focus: AI agent orchestration for creative professionals (media, design, content workflows)
- Stack: TypeScript, React, Next.js, LLMs
- Location: New York City (onsite)

**Assessment:** Novel niche (creative AI OS), but less prominent funding than Netic/CTGT comparable peers. Engineering culture appears serious given the LLM-first stack. Unknown stage is the main risk — verify funding before committing.

---

## B — Role Fit

**Stack match:** Very strong.
- TypeScript + React + Next.js: **CoverMe is built on this exact stack** (Next.js 14, TypeScript, Supabase). Direct proof.
- LLMs: CoverMe uses Claude API for cover letter generation + iterative AI refinement. LionPlanner uses Gemini API. George has shipped production LLM integrations.
- AI agent framing: CoverMe's AI refinement loop is the closest analog to agentic creative workflows.

**Role type:** Full-stack SWE with LLM/agent focus. Matches George's "AI Engineering Intern" archetype exactly.

**Gaps:** "Creative AI OS" is a niche George hasn't worked in specifically (seismic data + cover letters + academic planning), but the stack is the same. No gap in technical skills.

**Graduation requirement:** Not specified in available details. Listing says "Spring/Summer 2027" which targets rising juniors (graduating 2028+). George qualifies.

**⚠️ Timing note:** Spring 2027 track = PSU spring semester conflict. Apply exclusively for the **Summer 2027 track**. Confirm with Melius that summer-only track is available when applying.

---

## C — Compensation

- **Listed:** $8,500/month
- **Hourly equivalent:** ~$53/hr (8,500 / 4 weeks / ~40 hrs) ✅ within $40-60 target
- **No housing stipend** mentioned
- **Net assessment:** Meets target. Verify monthly figure holds for summer-only start.

---

## D — Logistics

| Factor | Detail |
|--------|--------|
| Location | New York City, Onsite (relocation required) |
| Duration | Spring/Summer 2027 — confirm summer-only track available |
| Visa | No sponsorship requirement mentioned |
| Format | Onsite full-time |
| Relocation | George open to NYC for summer ✅ |

---

## E — Application Strategy

**Lead proof point:** CoverMe — exact same stack (Next.js + TypeScript + LLM API + Supabase). Frame as: "I've shipped a production AI SaaS product on this exact stack — CoverMe is live with Stripe payments, Claude API integration, and 5 LaTeX templates."

**Secondary proof points:**
- LionPlanner: Gemini API integration, Google Cloud Run deployment, production-scale
- OSINT platform: Python NLP pipeline (demonstrates AI engineering breadth beyond just frontend)

**Application note:**
- URL directs to Ashby (blocked in this session) — apply directly at jobs.ashbyhq.com/melius
- Confirm summer-only availability in cover letter intro
- Ask about comp confirmation ($8,500/mo) during recruiter screen

**Priority:** Medium-high. Strong stack match and competitive comp. Apply October-November 2026 for Summer 2027 track. Verify funding/company stage before final decision.

---

## F — STAR Stories

**Story 1 — LLM Product Engineering (CoverMe)**
> *Situation:* Needed to build a full-stack SaaS where the AI component was the core product, not a bolt-on feature.  
> *Task:* Architect CoverMe to generate ATS-optimized cover letters from resume+JD using Claude API, with iterative refinement.  
> *Action:* Built Next.js frontend, TypeScript API routes, Supabase auth + RLS, Stripe billing, LaTeX→HTML preview renderer, and a multi-turn Claude API refinement loop.  
> *Result:* Live SaaS on Vercel with 5 templates, Stripe subscription tiers, and persistent letter history.  
> *Relevance:* Melius builds AI agent workflows on the same exact stack — CoverMe is the proof.

**Story 2 — End-to-end AI Platform (LionPlanner)**
> *Situation:* Penn State students had no tool to optimize course schedules with real data on professor quality and GPA distribution.  
> *Task:* Build a full AI planning platform from scratch — data collection, solver, LLM explanations, deployment.  
> *Action:* Scraped LionPATH + RateMyProfessors with Selenium, built a backtracking constraint solver generating 200+ conflict-free schedules, integrated Gemini for NL explanations, deployed on GCP Cloud Run with Prisma + PostgreSQL 15.  
> *Result:* Containerized production app serving Penn State students.  
> *Relevance:* Demonstrates that George deploys AI products, not just builds demos.
