# 261 — Microsoft | Software Engineer: Fullstack Intern (Summer 2027)

**Score:** 3.6/5
**URL:** https://jobs.careers.microsoft.com/global/en/job/1751922/Software-Engineer:-Fullstack-Intern-Opportunities-for-University-Students,-Redmond
**PDF:** ❌
**Date:** 2026-08-22
**Verification:** unconfirmed (web scan — listed by SimplifyJobs/Prosple trackers; direct fetch blocked by proxy)

🟡 **NEW as of ~Aug 8-22, 2026 — Fullstack-specific track (TypeScript/React front + C#/Java/Golang back). Redmond WA + Atlanta GA locations. BS eligible. Comp floor may touch below $40/hr — verify.**

DISTINCT from report_034/083 (SWE general, job 1763841), report_091 (AI/ML, job 1766916), report_135 (Applied AI/ML, job 1872468), report_147 (Data Science, job 1767736), report_246 (CoreAI, job 1970393556951950).

---

## A — Offer Snapshot

| Field | Detail |
|-------|--------|
| Company | Microsoft |
| Role | Software Engineer: Fullstack Intern Opportunities for University Students |
| Job ID | 1751922 (Redmond) / 1787038 (Atlanta) |
| Location | Redmond, WA or Atlanta, GA (on-site, 3-month summer) |
| Work Model | On-site |
| Duration | 12 weeks, Summer 2027 |
| Pay | $5,460–$10,680/mo listed range (~$34–$67/hr); BS interns at Redmond historically ~$46–52/hr (unconfirmed for this track — verify ≥$40/hr before accepting) |
| Degree Required | BS or MS in CS, Engineering, or related; at least 1 semester/term remaining after internship |
| Application Deadline | Rolling — no stated close date |
| Work Auth | No sponsorship listed |
| Related Postings | reports 034, 083, 091, 135, 147, 246 — all distinct job IDs and teams |

Fullstack-specialized Microsoft intern track (distinct from the general SWE umbrella). Front-end emphasis: TypeScript/JavaScript with React, HTML/CSS fundamentals, accessibility. Back-end emphasis: C#, Java, Golang, Kotlin, or C++ with API/microservice design. Teams span Azure, M365, Xbox, and other product divisions depending on placement. Interns ship production features, own a defined project scope, and participate in mentor-led learning sprints.

---

## B — George Fit Analysis

**Overall:** George is a strong match on the front-end half of this role — TypeScript/React is his daily stack (CoverMe, LionPlanner). The back-end languages are where the mismatch shows: Microsoft lists C#, Java, Golang, Kotlin, or C++ and George's primary back-end is Python and Node.js/TypeScript (not listed). However, Node.js/TypeScript back-end is an adjacent capability, and "Fullstack" roles at large companies often accommodate students who demonstrate the architectural thinking even if the exact language differs. The front-end strength is real and demonstrable.

| Dimension | George | Role | Gap |
|-----------|--------|------|-----|
| TypeScript / JavaScript | Primary language — CoverMe (Next.js/TypeScript), LionPlanner (Next.js/TypeScript) | Required (front-end) | ✅ Direct |
| React / Next.js | CoverMe: real-time LaTeX renderer, sidebar/two-column/classic layout parser; LionPlanner: schedule advisor UI | TypeScript/JavaScript + modern framework (React) | ✅ Exact match |
| HTML / CSS | Both projects: production-quality, user-facing layouts | HTML/CSS fundamentals | ✅ |
| C# / Java / Golang / C++ | None | Required (back-end) | ❌ Primary gap |
| Python back-end | Seismos (PDF ETL, SQL pipelines); OSINT (NLP ingestion pipeline); CoverMe (API backend) | Not listed — implies C#/Java/Go | ⚠️ Partial: Python proven but not the stated requirement |
| API / microservice design | CoverMe: REST API + Supabase auth + Stripe webhooks; LionPlanner: Cloud Run + Prisma ORM | Designing APIs, working with microservices | ✅ Architectural pattern match |
| Full-stack ownership | CoverMe: auth → billing → inference → PDF → deploy (end-to-end); LionPlanner: solver → DB → GCP | Coursework/projects across front and back end | ✅ Production proof, not just projects |
| SQL / PostgreSQL | Seismos: SQL reporting pipelines; LionPlanner: Cloud SQL + Prisma; OSINT: PostgreSQL ingestion | Back-end data layer | ✅ |
| Cloud / deployment | LionPlanner: GCP Cloud Run + Secret Manager; OSINT: Docker Compose; CoverMe: Vercel | N/A (not explicitly required) | ✅ Extra credential |
| Grad year | June 2028 — multiple semesters remaining | At least 1 semester remaining after internship | ✅ |

**Score breakdown:**
- Role fit: 3.5/5 (front-end exact match; back-end language gap C#/Java/Go)
- Company / brand: 5/5 (FAANG; Microsoft summer = strong resume line)
- Comp: 3.0/5 (unconfirmed band; historically ~$46–52/hr for BS Redmond SWE; floor risks touching below $40 target)
- Timing: 5/5 (BS, Summer 2027, George qualifies on remaining-semesters criterion)
- Competition: 3.0/5 (Microsoft interviews widely; DSA + system design required)
- Red flags: -1.5 (back-end language gap; comp floor uncertainty; similar to existing 6 MS reports so diminishing returns)
- **Global: 3.6/5**

---

## C — Proof Points from cv.md

| Role Requirement | George's Evidence |
|-----------------|-------------------|
| "TypeScript/JavaScript, React — front-end" | CoverMe: real-time LaTeX-to-HTML preview renderer, sidebar + two-column + classic layouts; LionPlanner: academic schedule advisor UI — both shipped, both TypeScript/Next.js |
| "HTML/CSS fundamentals, accessibility" | Both projects have user-facing interfaces with production-quality styling; not explicitly documented in cv.md but implied by shipped products |
| "Designing APIs, microservice patterns" | CoverMe: REST API layer + Supabase Row-Level Security + Stripe webhook handler; LionPlanner: Cloud Run serverless API + Prisma ORM + Google Secret Manager |
| "Back-end languages: C# / Java / Golang" | ⚠️ Not directly provable — Python is George's back-end. Note: Node.js/TypeScript (via Next.js API routes) is an adjacent back-end capability but is not the listed requirement |
| "SQL, data layer" | LionPlanner: Cloud SQL + Prisma ORM (PostgreSQL 15); Seismos: SQL reporting pipelines; OSINT: PostgreSQL ingestion + deduplication |
| "Ship features to production" | CoverMe: live Vercel deployment, active Stripe billing, real users; LionPlanner: GCP Cloud Run serving Penn State students |

---

## D — Risks & Concerns

1. **Back-end language gap (C#/Java/Golang):** This is the primary mismatch. George cannot demonstrate these languages. He can argue Python → C# is a small leap conceptually (OOP, type system), and Next.js API routes give him back-end TypeScript — but the listing specifically calls for the stated languages. Risk: screened out at resume stage if the team is strict on language requirements.
2. **Comp floor uncertainty:** The listed range ($34–$67/hr) is wide and the floor is below George's $40 target. Historical data for BS SWE interns at Redmond is ~$46–52/hr, but this Fullstack track may pay differently. Verify actual offer band before committing.
3. **Diminishing returns on Microsoft applications:** George already has 6 Microsoft tracks being tracked (reports 034, 083, 091, 135, 147, 246). Adding a seventh creates application management overhead. Apply this one only if the front-end/full-stack angle gives genuinely different positioning vs the CoreAI (246) or general SWE (083) applications.
4. **On-site Redmond or Atlanta:** Relocation required. George is open to this for summer — not a blocker.
5. **PyTorch/ML not relevant here:** Unlike CoreAI (report_246), this role doesn't require ML knowledge. George's strongest AI proof points (CoverMe Claude API, LionPlanner Gemini) still apply for general production engineering, but the "LLM developer" angle is less central.

---

## E — Application Strategy

1. **Apply after CoreAI (246) and general SWE (083) are submitted** — those are higher-fit Microsoft tracks. This one is a good supplement if those apps are already in.
2. **Front-end lead:** Frame George as "TypeScript-native fullstack developer" in the resume. CoverMe's LaTeX renderer and LionPlanner's schedule advisor UI are the strongest proof points. Open with the front-end story.
3. **Back-end framing:** Highlight Next.js API routes (CoverMe backend), Prisma ORM (LionPlanner), and Cloud Run serverless back-end as demonstrations of back-end thinking — even if the language isn't C# or Java. Note: "proficient in Python; can ramp on C# / Java with minimal lead time given shared OOP paradigms."
4. **Location:** Both Redmond and Atlanta listed — apply to both job IDs (1751922 and 1787038) as separate applications if allowed.
5. **Interview prep:** Standard Microsoft prep applies (DSA: arrays, trees, graphs, DP). Add system design for a full-stack web application (e.g., design CoverMe's architecture: auth, storage, API, billing, AI layer).
6. **Verify comp before accepting:** Confirm offer ≥ $40/hr.

---

## F — Recommendation

**Apply — secondary Microsoft target for Summer 2027.** The front-end TypeScript/React match is strong, but the back-end language gap (C#/Java/Golang vs George's Python) is real and may be a filter. Given George already has 6 Microsoft applications tracked, this should be submitted after the higher-priority CoreAI (report_246, 4.0/5) and Applied AI/ML (report_135, 4.0/5) tracks are in.

The fullstack angle is a useful differentiation: George can position CoverMe and LionPlanner as production full-stack proof points in a way that the AI-specialized MS tracks don't fully capture. Worth the 20-minute application time once higher-priority MS apps are submitted.

**Comp estimate:** ~$46–52/hr × 40 hrs × 12 weeks = ~$22,000–25,000 for summer (BS Redmond estimate, unconfirmed).

**⚠️ Action items:**
- Submit after reports 246 and 135 are applied to (avoid Microsoft over-saturation)
- Apply to both job IDs: 1751922 (Redmond) and 1787038 (Atlanta)
- Verify comp band ≥$40/hr at offer stage
- Prepare a 5-min verbal walk-through of CoverMe's full-stack architecture for the interview
