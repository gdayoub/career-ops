# 196 — Scale AI | AI Builder Intern (Summer 2026)

**Score:** 3.8/5
**URL:** https://job-boards.greenhouse.io/scaleai/jobs/4703343005
**PDF:** ❌
**Status:** Evaluated
**Date:** 2026-06-16
**Verification:** unconfirmed (batch mode — Playwright unavailable; direct WebFetch to greenhouse/scale.com/aggregator pages all returned 403, role confirmed via WebSearch snippet aggregation across multiple sources)

---

## A — Summary

Scale AI is hiring an AI Builder Intern on the Data & Technology team for Summer 2026, based in San Francisco, CA. This is explicitly framed as a *building* role, not a research internship: "you'll spend it building — shipping AI-powered tools, automating workflows, and deploying agentic systems that real teams at Scale AI use every day." The intern works directly alongside engineers, data scientists, and ops leads on live internal automation initiatives — designing multi-step agentic workflows with LLM frameworks (LangChain, LangGraph, CrewAI or similar), building API-connected automations tying together Slack/Salesforce/Notion/internal data systems, and building React/JavaScript UI components for internal dashboards.

Compensation is posted as a full-time annualized band of $74,400–$111,600/yr, which converts to roughly $35.77–$53.65/hr (2080 hr/yr basis) — the lower end sits below George's $40/hr floor but the midpoint (~$44.70/hr) clears it comfortably, and George's profile allows flexibility for strong fit.

**Distinct from** report_012 (Scale AI Software Engineering Intern, 3.6/5, 2026-04-06 — graduation-mismatch flagged then) and from two other Scale AI postings found this scan that are NOT being reported: "Technical Advisor Intern – GenAI (Winter/Spring 2026)" (wrong season) and "ICLR 2026 – University Recruiting" (a recruiting event, not an internship). Unlike most roles found in this scan cycle, this posting has **no explicit graduation-year restriction** — it requires only current enrollment in an undergrad or grad CS/data science/engineering program.

---

## B — Role Analysis

**Team:** Data & Technology — builds internal AI tooling/automation used by Scale AI's own engineers, data scientists, and ops teams (not a customer-facing product team, not the research org).

**Core work:**
- Build AI-powered tools and workflow automations for internal Scale AI teams
- Design and deploy multi-step agentic workflows using LLM-integrated frameworks (LangChain, LangGraph, CrewAI, or similar)
- Build API-connected automations linking internal tools (Slack, Salesforce, Notion, internal data systems)
- Build UI components/dashboards in React/JavaScript
- Instrument work with usage signals and ROI tagging

**Stack:** Python and/or JavaScript; LLM APIs (OpenAI, Anthropic); agentic/automation frameworks (LangChain, AutoGen, n8n, Zapier+LLM); React for UI.

**Degree:** Currently enrolled undergrad or grad student in CS, data science, or related engineering field — no explicit grad-year cutoff found (a clear positive relative to most other roles found this cycle, many of which require Dec 2026/2027 graduation).

**Location/timing:** San Francisco, CA — most consistent signal across ZipRecruiter and the Glassdoor analog SWE internship listing for the same company/season; one low-quality aggregator (aidoos.com) labeled it "remote," which is not corroborated elsewhere and is treated as unreliable. Summer 2026 program; exact start/end dates for this specific requisition could not be confirmed (all direct page fetches returned 403) — Scale AI's general Summer 2026 intern cohort runs roughly June–August per pattern from prior tracked Scale AI postings.

---

## C — George Fit

**Matches:**
| Requirement | George's Proof Point |
|-------------|---------------------|
| LLM API experience (OpenAI/Anthropic) | CoverMe uses the Claude API with an iterative AI refinement system (cv.md) |
| LLM API experience (alt. provider) | LionPlanner uses the Google Gemini API for natural-language schedule explanations (cv.md) |
| Python | Seismos internship (PDF extraction, SQL pipelines), OSINT NLP pipeline, LionPlanner backend (cv.md) |
| JavaScript/React for internal tools/UI | CoverMe and LionPlanner both built on Next.js + TypeScript (cv.md) |
| Building automations / pipelines | OSINT platform: multilingual NLP ingestion pipeline with dedup, normalization, scoring, containerized with Docker Compose (cv.md) |
| "Bias for building over theorizing" | Both CoverMe and LionPlanner are live, deployed products, not class projects (cv.md) |
| Prompt engineering / RAG | Listed directly under Technical Skills → AI & ML: "LLM API Integration, Prompt Engineering, RAG Pipelines" (cv.md) |

**Gaps:**
| Gap | Severity | Mitigation |
|-----|----------|-----------|
| No explicit LangChain/LangGraph/CrewAI/AutoGen experience | Moderate | cv.md lists "RAG Pipelines" and direct LLM API integration (Claude, Gemini) as adjacent experience; framework itself is learnable, the underlying pattern (chaining LLM calls, iterative refinement) is already proven in CoverMe |
| No internal-tooling-for-Slack/Salesforce/Notion experience | Minor | Not a hard requirement — role asks for API-connected automation skill generally, which George has shown via LionPlanner's Selenium scraping + Cloud SQL integration and CoverMe's Stripe/Supabase integrations |
| Comp lower bound ($35.77/hr) below $40/hr floor | Minor-Moderate | Midpoint (~$44.70/hr) clears the target range; profile notes flexibility for strong-fit roles |

**Location:** San Francisco, CA, likely on-site/hybrid. George is open to relocation anywhere in the US for summer 2026. ✅ (scores 5.0 per location policy)

**Net assessment:** This is one of the stronger matches found in this scan cycle — it is the only roughly-AI-engineering-shaped internship found with no graduation-year blocker, and the core ask (ship AI-powered tools using LLM APIs + build the surrounding UI) is close to a direct restatement of what George already built with CoverMe and LionPlanner. The main open risk is the unconfirmed framework-specific tooling (LangChain et al.) and a small amount of comp ambiguity at the lower end of the posted band.

---

## D — Proof Points

**Lead with CoverMe (Claude API + iterative refinement):**
> "Built CoverMe, a live SaaS that generates ATS-optimized cover letters using the Claude API with an iterative AI refinement system — the same 'shipping AI-powered tools that real users rely on' pattern this role is built around, not a research prototype."

**Follow with LionPlanner (Gemini API + automation):**
> "Built LionPlanner end-to-end: a backtracking constraint solver generating up to 200 conflict-free schedules, Google Gemini for natural-language explanations, and Selenium scraping pipelines feeding a Cloud SQL database — direct experience building the kind of API-connected automation this role asks for."

**OSINT platform (pipeline + automation + dashboard):**
> "Built a multilingual NLP ingestion pipeline (Arabic news sources → PostgreSQL, with dedup and automated scoring) and shipped a Streamlit dashboard for live monitoring — the same 'automate a workflow end-to-end and put a UI on it' shape as this role's dashboards."

---

## E — Draft Materials

**Cover note angle:**
George should lead with the framing that he has already shipped the exact pattern this role hires for: LLM-API-powered tools with a real interface, not research notebooks. Calling out that CoverMe's "iterative AI refinement system" is conceptually a single-step version of the multi-step agentic workflows this role asks for is a credible, honest bridge — it doesn't claim LangChain experience he doesn't have, just adjacent and provable LLM-orchestration experience.

**Tailored summary (for application portal):**
> Rising junior at Penn State (Computational Data Science) who ships AI-powered products end-to-end, not just notebooks. Built CoverMe, a live SaaS using the Claude API with an iterative AI refinement system, and LionPlanner, an AI academic planner using the Gemini API with a custom backtracking solver and Selenium-based data pipelines, deployed on GCP Cloud Run. Comfortable across Python, TypeScript/React, SQL, and API integrations — excited to build the internal AI tooling and agentic automations Scale AI's own teams rely on.

---

## F — Action Items

1. **Verify posting is still active** at https://job-boards.greenhouse.io/scaleai/jobs/4703343005 before applying — all automated fetch attempts this scan returned 403, so confirm manually (browser) that the req is still open and re-check the exact location (SF vs. remote) and dates.
2. **Spend 1-2 hours before applying** skimming LangChain or LangGraph basics so the application/interview can speak to the specific framework names in the JD, even though George's underlying experience (Claude/Gemini API integration, iterative refinement) is real and directly relevant.
3. **Prioritize** alongside other 3.8-4.0 scored roles; below the 4.3+ tier (Salesforce AI, Duolingo, Robinhood MLE Agentic) but ahead of lower-confidence/comp-ambiguous roles like Lambda ML Research (192, 3.0/5).
4. **Tailor resume**: lead with CoverMe's Claude API + refinement system, then LionPlanner's Gemini API + automation pipeline, then OSINT Docker/dashboard pipeline.
5. **In the application, ask directly** (if there's a "questions for us" field) whether the role is on-site/hybrid/remote, since public listings disagree — this avoids a surprise after an offer.
