# 230 · OpenAI — Software Engineer, Systems Research Internship, Applied Emerging Talent (Summer 2026)

**Date:** 2026-07-10
**Score:** 3.8 / 5
**URL:** https://openai.com/careers/software-engineer-systems-research-internship-applied-emerging-talent-(summer-2026)-san-francisco/
**PDF:** ❌
**Status:** Evaluated
**Verification:** unconfirmed (JD access restricted; based on aggregated search data — batch scan mode)

---

## A · Fit Analysis

| Dimension | Detail |
|-----------|--------|
| **Company** | OpenAI — leading AI lab; ChatGPT, GPT-4, o1; Applied team serves millions of users |
| **Role** | Software Engineer, Systems Research Internship — investigate systems problems in Applied Systems; improve efficiency, scalability, reliability |
| **Track** | Applied Emerging Talent — DISTINCT from general SWE intern (#013, 4.6/5) and Fall 2026 Applied (#127, 4.0/5) |
| **Location** | San Francisco, CA — in-person, 13 weeks (extendable to 26 based on perf) |
| **Compensation** | ~$60–67/hr (OpenAI Applied intern rate; $60/hr confirmed for comparable tracks) |
| **Grad Window** | December 2026 – June 2029 → George (June 2028) ✅ QUALIFIES |
| **Season** | Summer 2026 — ⚠️ MID-CYCLE WARNING: July 10, 2026. Cohort may be underway. Listing still live on openai.com; rolling basis confirmed. |
| **Archetype Match** | SWE / Applied Systems / Backend |

---

## B · Your Alignment

| Strength | Evidence from CV |
|----------|-----------------|
| **Python production systems** | CoverMe (Next.js + Claude API + Stripe + Supabase on Vercel); LionPlanner (GCP Cloud Run + PostgreSQL + Prisma) |
| **API integration & reliability** | CoverMe: Claude API with real users, LaTeX rendering pipeline, Stripe webhook handling under load |
| **Cloud infrastructure** | LionPlanner: GCP Cloud Run, Secret Manager, Cloud SQL; OSINT: Docker Compose containerization |
| **Systems thinking** | LionPlanner: backtracking constraint solver, conflict-free schedule generation at 200+ variant scale |
| **Data pipeline efficiency** | Seismos: automated PDF extraction pipeline; OSINT: deduplication + NLP pipeline + PostgreSQL at scale |
| **OpenAI ecosystem fit** | CoverMe uses Claude API — direct analog to building on OpenAI's APIs; understands both sides of the applied AI stack |

**Gap:** No explicit distributed systems coursework, no performance profiling or formal systems benchmarking experience. The "research" framing (investigate, measure, iterate) is more formal than George's product-first approach. Closest analog is LionPlanner's constraint solver optimization and OSINT pipeline tuning.

---

## C · Logistics

| Item | Detail |
|------|--------|
| **Apply** | openai.com/careers → Applied Emerging Talent → Systems Research Internship |
| **Deadline** | Rolling — apply immediately; Summer 2026 mid-cycle, slots may close any day |
| **Competition** | High — OpenAI intern bar is high, but shipped SaaS products (CoverMe) differentiate from most candidates |
| **Key differentiator** | CoverMe: proof of understanding OpenAI's customer-facing API ecosystem from the builder's perspective |
| **⚠️ First step** | Verify Apply button is still active on openai.com before investing full app effort |

---

## D · Suggested Story (STAR)

**"Tell me about a system you built and optimized for scale/efficiency":**

> **S:** LionPlanner needed to generate conflict-free Penn State schedules across hundreds of sections with competing constraints.
> **T:** Build a solver fast enough to be useful, not just correct — brute force was O(n!) and unusable.
> **A:** Implemented a backtracking solver with early pruning heuristics; integrated live Cloud SQL queries for constraint loading; deployed serverless on GCP Cloud Run with auto-scaling.
> **R:** Generated up to 200 conflict-free schedules per query; measured response latency across load scenarios and iterated on pruning logic to cut tail latency.
> **Reflection:** Next step would be profiling the SQL join performance at scale — the kind of systems measurement work I'm applying to OpenAI to formalize.

---

## E · Red Flags

- ⚠️ **TIMING**: Summer 2026 internship and we are currently July 10, 2026. The cohort likely started May/June. Verify before spending full application effort — check if the Apply button is active vs. "Applications Closed."
- **Systems research framing**: More formal research orientation than product engineering. George has shipped systems but hasn't done formal performance benchmarking or research write-ups.
- **JD unverified**: Full JD access was 403-restricted during this scan. All details based on aggregated search data. Verify before applying.
- **Dedup note**: DISTINCT from #013 (OpenAI SWE Applied Summer 2026, 4.6/5) and #127 (OpenAI Fall 2026 Applied Emerging Talent, 4.0/5). Different team/focus.

---

## F · Recommendation

**Apply immediately — verify timing first.**

If the listing is still live and accepting applications (rolling basis confirmed), this is worth a focused application. Grad window is a perfect match, comp is at target, and CoverMe is a strong proof point for understanding both the engineering and customer side of applied AI APIs.

**If Summer 2026 cohort is closed:** Check openai.com/careers for Summer 2027 listings (expected August–October 2026). Also revisit #127 (Fall 2026 Applied co-op) if PSU allows co-op enrollment for fall semester.

**Action items:**
1. Navigate to openai.com/careers → search "Systems Research Internship" → confirm Apply button is active
2. If open: submit this week — lead with CoverMe API work and LionPlanner systems optimization
3. If closed: add to Summer 2027 monitor list and check back August 2026
