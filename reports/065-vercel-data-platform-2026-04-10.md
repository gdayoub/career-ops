# 065 · Vercel — Data Platform & Engineering Intern

**Score:** 3.5/5  
**URL:** https://job-boards.greenhouse.io/vercel/jobs/5810803004  
**PDF:** ❌  
**Date:** 2026-04-10  
**Verification:** Active (confirmed via Vercel careers page + LinkedIn posting March 2026)  
**⚠️ GRAD REQUIREMENT UNCONFIRMED** — Vercel's Engineering Summer Intern requires Dec 2026/May 2027 graduation. This Data Platform role may have the same constraint. **Verify before applying.** If grad req is flexible (no explicit 2026-2027 constraint), score rises to ~4.5/5.

---

## A · Role Analysis

**What this role is:**  
The Data Platform & Engineering Intern joins the team that builds and operates Vercel's internal data infrastructure — the systems powering analytics, experimentation, internal tooling, and AI-powered agents. The role is explicitly designed to flex between Data Platform Engineering and Data Engineering depending on the intern's strengths. This is a hands-on engineering role, not a business-analytics role.

**Why this matters for George:**  
This is a rare overlap of three of George's strongest areas: (1) data engineering pipelines (Seismos internship), (2) full-stack deployment (CoverMe on Vercel — the exact platform!), and (3) LLM/AI integration (Claude API, LionPlanner). The role focuses on "emerging AI-powered agents" and data infrastructure — George has shipped both.

**Key responsibilities (inferred from JD summary):**
- Build and maintain data pipelines powering company-wide analytics
- Contribute to experimentation infrastructure (A/B testing, feature flagging)
- Work on internal tooling and AI-powered agent workflows
- Support data engineering and platform engineering depending on strengths

**Risk flag:**  
The Engineering Summer Intern (different role, same company) requires "graduation date of December 2026 or May 2027". George graduates June 2028. If the Data Platform intern has the same constraint, this is a hard disqualifier. The Data Platform role JD uses "currently pursuing a BS or MS" without an explicit graduation date in available search data — but this is UNCONFIRMED. Verify at `vercel.com/careers/data-platform-and-engineering-intern-5810803004` before investing application time.

---

## B · Skills Match

| Requirement | George's Evidence | Strength |
|-------------|-------------------|----------|
| Python data engineering | Seismos: PDF extraction, SQL reporting pipelines; OSINT: PostgreSQL ingestion, data normalization | ✅ Strong |
| SQL / PostgreSQL | Seismos SQL pipelines; LionPlanner (PostgreSQL + Cloud SQL); CoverMe (Supabase/Postgres) | ✅ Strong |
| Data visualization | Seismos: Python visualizations; OSINT: Streamlit dashboard, KPI monitoring, trend viz | ✅ Strong |
| Vercel platform | CoverMe deployed on Vercel with Supabase auth + Stripe billing | ✅ Direct proof point |
| AI/LLM integration | CoverMe: Claude API; LionPlanner: Gemini API | ✅ Strong |
| Analytics / experimentation | SQL reporting pipelines at Seismos; Streamlit analytics | ✅ Partial |
| TypeScript / JavaScript | CoverMe (Next.js + TypeScript), LionPlanner (Next.js) | ✅ Strong |
| Go / Rust | Not in George's stack | ❌ Gap (listed as bonus) |
| Docker / infra | Arabic OSINT: Docker Compose; LionPlanner: Cloud Run | ✅ Solid |

**Stack verdict:** George matches 8/9 requirements. Missing Go/Rust (explicitly listed as bonus, not required). The Vercel deployment experience is an unusually strong proof point for this specific employer.

---

## C · Culture & Mission Fit

Vercel's mission is to make web development faster and more accessible. They ship infrastructure used by millions of developers. George's entire project portfolio is built on or closely aligned with this stack: CoverMe (Vercel + Supabase), LionPlanner (GCP Cloud Run). He's not an outsider applying to a company he doesn't know — he's a user who ships on their platform.

The Data Platform team specifically works on internal tools and AI agents, which aligns with George's builder identity ("ships end-to-end, idea to deployed product").

**Culture fit: High** — builder-first company, intern gets to work on real systems, strong engineering culture.

---

## D · Compensation & Location

| Factor | Details |
|--------|---------|
| Location | San Francisco, CA — hybrid |
| Comp | ~$9,500–$11,000/month est. (based on Vercel Engineering Summer Intern range; Data Platform intern likely similar) |
| Hourly equivalent | ~$59–$69/hr |
| Within target? | Yes — at top of $40-60/hr target, slightly above |
| Relocation | George is open to SF for summer |
| Timeline | Summer 2026 (dates unconfirmed for this role) |

---

## E · Application Strategy

**⚠️ VERIFY FIRST:** Before applying, confirm graduation date requirements at the official posting. If Dec 2026/May 2027 constraint applies → do not apply. If requirements say "pursuing a BS or MS" without graduation date → apply immediately.

**If eligible:**

**Cover letter hook:** "I deployed CoverMe on Vercel — it's live, processing real Stripe payments. I've been a Vercel user building on your platform, and now I want to help build the data infrastructure behind it."

**Tailor the application to emphasize:**
1. Seismos data internship: automated PDF extraction, SQL reporting pipelines, data visualization for cross-functional teams
2. CoverMe: production deployment on Vercel (direct platform credibility)
3. OSINT Platform: Streamlit analytics dashboard with live KPI monitoring — this is exactly what the Data Platform team builds internally
4. Python + PostgreSQL + Docker depth from 3 shipped projects

**Priority tier:** Conditional. If grad req is cleared → A-tier application, prioritize alongside Stripe/OpenAI. If grad req blocks → skip.

---

## F · STAR Stories to Highlight

**Story 1 — Data pipeline automation (Seismos):**  
- Situation: Engineering teams were manually preparing stage reports from raw PDFs  
- Task: Automate extraction and transform raw field data into analysis-ready Excel reports  
- Action: Built Python extraction pipeline using PDF parsing + structured data output  
- Result: Reduced manual report preparation time for engineering teams  
- Relevance: Maps directly to "build data pipelines powering analytics"

**Story 2 — Analytics dashboard (OSINT):**  
- Situation: Needed real-time intelligence monitoring across multilingual news sources  
- Task: Ship a live analytics dashboard with trend visualization and KPI monitoring  
- Action: Built Streamlit dashboard with PostgreSQL backend, deduplication, live KPI cards  
- Result: Working analytics product containerized with Docker Compose  
- Relevance: Maps directly to Vercel Data Platform internal analytics/experimentation work

**Story 3 — Deployed product on Vercel (CoverMe):**  
- Situation: Wanted to build a live SaaS with real users  
- Task: Architect full-stack AI product with auth, billing, and deployment  
- Action: Built on Next.js + Supabase + Stripe, deployed to Vercel  
- Result: Live SaaS with Stripe payments and Claude API integration  
- Relevance: Direct employer credibility — applicant has shipped to production on their platform
