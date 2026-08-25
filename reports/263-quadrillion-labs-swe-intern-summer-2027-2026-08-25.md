# 263 — Quadrillion Labs: Software Engineering Intern (Summer 2027)

**Score:** 3.8/5  
**URL:** https://jobs.ashbyhq.com/quadrillion-labs/a4acc44c-31ce-41a0-ab44-2500487b4d05  
**PDF:** ❌  
**Date:** 2026-08-25  
**Verification:** unconfirmed (batch mode — Ashby EGRESS_BLOCKED; job surfaced via WebSearch + careers.quadrillion.io)

---

## A — Company

**Quadrillion Labs** builds **Qualia**, an agentic research intelligence platform that does real computational research — running experiments, analyzing data, and surfacing insights automatically.

- **Funding:** $18M from Conviction, Audacious, Bloomberg Beta, ex/ante
- **Angel investors:** Wes McKinney (creator of Pandas/NumPy), others
- **Team pedigree:** Stanford NLP, HRT, Citadel, Jane Street, Google Research, Harvard Med
- **Location:** Midtown Manhattan, NYC
- **Stage:** Well-funded seed/Series A (Conviction-backed = serious)

**Assessment:** Strong founding team pedigree (quant + NLP + research) and credible backers. Conviction Capital is a top-tier VC. Wes McKinney as angel signals the data engineering seriousness. The "agentic research intelligence" space is directly adjacent to George's OSINT platform (multilingual intel analysis, automated scoring, trend surfacing). One of the more technically credible early-stage finds in this scan.

---

## B — Role Fit

**Stack match:** Strong.
- **Python:** George's primary language. Used at Seismos (SQL pipelines, data viz), OSINT platform (NLP pipeline, TF-IDF classifier, PostgreSQL), Gesture Canvas (OpenCV/MediaPipe). Deep Python background.
- **React:** Used in CoverMe (Next.js/React) and LionPlanner (Next.js). ✅
- **"Sophomores and juniors preferred":** George is rising junior (Class of 2028). ✅ Explicitly targeted.

**Role type:** SWE on "AI Research Platform" (Qualia). The platform runs experiments and surfaces research insights — this is where George's OSINT platform is the strongest analogue: he built a system that ingests multilingual data, applies ML classification, and surfaces geopolitical intelligence summaries with a live dashboard.

**OSINT → Qualia alignment:**
| OSINT Platform | Qualia (Quadrillion) |
|---------------|---------------------|
| Ingests Arabic news from 3 sources | Ingests research data across sources |
| TF-IDF + LR classifier for topic categorization | ML models for experiment analysis |
| Automated geopolitical threat scoring | Automated research insight scoring |
| Streamlit dashboard with KPI monitoring | Research intelligence dashboard |
| Docker Compose containerized stack | Production research platform |

This is not a stretch — the architecture is nearly identical at the conceptual level.

**Gaps:** Quadrillion's "research intelligence" is more academic/scientific domain (computational research) vs. George's geopolitical/data science work. No deep academic research publication background. But the engineering bar is what matters for a SWE intern.

---

## C — Compensation

- **Listed:** UNCONFIRMED
- **Search result indicated:** "$3K-$5K/week" — likely a misquote of full-time salaries. Treat as unverified.
- **Estimated range:** For a $18M-funded NYC AI startup with Conviction backing: likely $7K-$12K/month (~$43-75/hr)
- **⚠️ MUST VERIFY ≥$40/hr before applying.** Email recruiting or ask at first contact.

---

## D — Logistics

| Factor | Detail |
|--------|--------|
| Location | Midtown Manhattan, NYC — 5 days/week onsite |
| Duration | Summer 2027 (12 weeks est.) |
| Visa | Not specified |
| Format | Onsite full-time, 5d/wk |
| Relocation | George open to NYC for summer ✅ |
| Benefits | Medical/dental/vision, lunch + dinner covered, stipends mentioned |

---

## E — Application Strategy

**Lead proof point:** OSINT Intelligence Platform — most direct structural analogue to Qualia's "agentic research intelligence" mission.

Frame as: "I built a multilingual NLP pipeline that ingests data from 3 Arabic news sources, runs TF-IDF classification, applies automated threat scoring, and surfaces weekly intelligence summaries in a live Streamlit dashboard — it's a self-contained research intelligence system."

**Secondary proof points:**
- Seismos internship: "PDF extraction + SQL pipelines = automating data workflows for cross-functional teams" — this is what Qualia does for researchers
- CoverMe: Python backend + AI API integration shows production LLM experience
- LionPlanner: Backtracking constraint solver + GCP Cloud Run = complex algorithmic backend deployment

**Application note:**
- Apply via Ashby: jobs.ashbyhq.com/quadrillion-labs
- **FIRST**: verify compensation ≥ $40/hr (email hello@quadrillion.io or note in application)
- Explicitly mention you're a rising junior at Penn State graduating June 2028 — they prefer this cohort
- Target timeline: Apply September-October 2026 for Summer 2027

**Priority:** Medium-high, conditional on comp confirmation. If comp ≥ $43/hr (likely given Conviction funding), this is a top Summer 2027 AI startup target — better technical backing than most YC startups with similar profiles. Apply alongside CTGT (217) and Netic (237/250).

---

## F — STAR Stories

**Story 1 — Agentic Research Intelligence (OSINT Platform)**
> *Situation:* Needed to monitor and analyze geopolitical threats from Arabic news sources with no labeled dataset and limited compute.  
> *Task:* Build an end-to-end pipeline: ingestion, dedup, NLP classification, threat scoring, and live dashboard — containerized and redeployable.  
> *Action:* Built Python pipeline ingesting Al Jazeera, BBC Arabic, CNN Arabic into PostgreSQL with deduplication + normalization. Trained TF-IDF + Logistic Regression classifier for topic categorization. Built rule-based threat scoring system. Shipped Streamlit dashboard with KPI tiles, trend charts, weekly summaries. Containerized with Docker Compose.  
> *Result:* Fully deployed research intelligence platform — ingests, classifies, scores, and surfaces geopolitical signals automatically.  
> *Relevance:* Qualia does exactly this for computational research. The architecture (pipeline → ML → scoring → dashboard) is identical.

**Story 2 — Data Pipeline Engineering (Seismos)**
> *Situation:* Engineering teams at Seismos were manually processing PJR field data from PDFs into Excel reports — slow and error-prone.  
> *Task:* Automate extraction, structuring, and reporting for seismic datasets across multiple clients.  
> *Action:* Built Python scripts to extract and structure PJR data from raw PDFs. Developed SQL reporting pipelines and Python visualizations to surface efficiency trends across seismic datasets. Collaborated with cross-functional teams to validate data integrity end-to-end.  
> *Result:* Eliminated manual stage report preparation for engineering teams; accelerated cross-functional decision-making.  
> *Relevance:* Automating research data workflows is core to Quadrillion's value proposition.
