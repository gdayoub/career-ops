# 068 — Amazon | 2026 Data Engineer Internship

**Score:** 4.1/5
**URL:** https://www.amazon.jobs/en/jobs/3145530/2026-data-engineer-internship
**PDF:** ❌
**Date:** 2026-04-13
**Verification:** unconfirmed (batch mode)

---

## A — Offer Snapshot

| Field | Detail |
|-------|--------|
| Company | Amazon |
| Role | 2026 Data Engineer Internship |
| Job ID | 3145530 |
| Location | Seattle WA, Bay Area CA, DC/MD/VA, Austin TX, NYC, Minneapolis MN |
| Work Model | In-office Mon–Fri |
| Duration | 12 weeks (ideal 6 months but 12-week track available) |
| Pay | ~$52/hr (Levels.fyi); range $91K–$185K/yr ($44–89/hr) depending on market |
| Degree Required | B.S./M.S. in CS, CE, Info Systems, Data Science or related STEM; graduation Oct 2026 – Dec 2029 |
| Application Status | Open |

Amazon Data Engineer interns design and implement distributed systems for log collection, data warehouse schemas, ETL pipelines, and build internal dashboards and analytics tools. This is a data-first role — not pure ML, but deeply technical data infrastructure.

---

## B — George Fit Analysis

**Overall:** Very strong match for George's Seismos background. The JD reads like a job description for what George already did: PDF/raw data → structured pipelines → SQL reporting → stakeholder dashboards.

| Dimension | George | Role | Gap |
|-----------|--------|------|-----|
| Graduation | June 2028 | Oct 2026 – Dec 2029 | ✅ Perfect window |
| SQL | PostgreSQL (LionPlanner, Seismos), MySQL | SQL (primary requirement) | ✅ Strong match |
| Python | Seismos (extraction scripts), OSINT (NLP pipeline), LionPlanner | Python (scripting required) | ✅ Strong match |
| Data pipelines | Seismos: raw PDF → Excel/analysis-ready reports; OSINT: ingestion pipeline | "Design, implement, automate data pipelines" | ✅ Direct experience |
| Data warehousing | SQL reporting at Seismos, PostgreSQL schemas | "Operate internal data warehouses, SQL/NoSQL" | ✅ Good match |
| ETL experience | PDF extraction → SQL (Seismos), Al Jazeera news → PostgreSQL (OSINT) | "ETL processes" (preferred) | ✅ Real-world ETL |
| Metrics/dashboards | Streamlit dashboard (OSINT), Plotly/Power BI (skills) | "Ongoing metrics, reports, dashboards" | ✅ Strong match |
| AWS | Listed in skills | AWS preferred | 🟡 GCP primary, some AWS |
| Big data (Hadoop/Spark) | Not listed | Preferred | ❌ Gap, but "preferred" not required |

**Key differentiators:**
- Seismos: "Automated extraction and structuring of PJR field data from raw PDFs into analysis-ready Excel reports" — this is literally the job description
- OSINT: Built "multilingual NLP pipeline ingesting Arabic news... into PostgreSQL with deduplication, text normalization" — demonstrates data ingestion + schema design + dedup logic
- Streamlit dashboard with "live KPI monitoring, trend visualizations, and weekly intelligence summaries" — exactly the dashboard/monitoring work described

---

## C — Proof Points from cv.md

| Role Requirement | George's Evidence |
|-----------------|-------------------|
| "Design, implement, and automate deployment of distributed systems for collecting and processing log events from multiple sources" | Seismos: automated PDF data extraction across multiple client reports; OSINT: multi-source news ingestion (Al Jazeera, BBC Arabic, CNN Arabic) |
| "Design data schema and operate internal data warehouses and SQL/NoSQL database systems" | LionPlanner: PostgreSQL 15 + Prisma ORM schema design; Seismos: structured Excel schemas from raw field data |
| "Own design, development and maintenance of ongoing metrics, reports, analyses, and dashboards" | OSINT: Streamlit analytics dashboard with live KPI monitoring + weekly intelligence summaries |
| "Monitor and troubleshoot data pipelines" | Seismos: "validated end-to-end data pipelines, ensuring data integrity and accuracy" |
| "Drive architectural plans for future data storage, reporting, analytic solutions" | LionPlanner: Cloud SQL + Google Secret Manager architecture; OSINT: Docker Compose stack |
| "Experience with Python and SQL (required)" | Both used at Seismos and OSINT platform; Python (pandas, SQLAlchemy) + PostgreSQL |
| "Experience with AWS (preferred)" | Listed in skills section alongside GCP |
| "Experience building data pipelines or automated ETL (preferred)" | Seismos PDF extraction pipeline = ETL in practice |

---

## D — Risks & Concerns

1. **Competition:** Still competitive (FAANG brand), but DE track is often less saturated than SDE track.
2. **6-month vs 12-week:** Job posting says "ideal length 6 months" — George can only do 12 weeks (summer). Most Amazon DE internships offer a 12-week track; confirm at application/interview stage.
3. **Big data tools gap:** Hadoop/Spark listed as preferred but not required. Not a dealbreaker for a junior.
4. **Pay:** ~$52/hr vs SDE's $75/hr — still above target ($40–60/hr). Note: this is slightly below SDE intern comp.
5. **Graduation window confirmed:** Oct 2026 – Dec 2029. George (June 2028) qualifies. ✅

---

## E — Application Strategy

1. **Apply alongside report_067 (SDE Intern)** — the two roles don't conflict; Amazon tracks applications separately. Apply to both.
2. **Resume tailoring:** Lead with Seismos (data pipelines, SQL reporting, PDF extraction). The description maps almost perfectly to that experience. Then OSINT platform (multi-source ingestion, PostgreSQL, Streamlit dashboard).
3. **Clarify internship length:** In the application, note "available May–August 2026 (12 weeks)". The 6-month preferred duration won't exclude you — many positions offer 12-week tracks.
4. **Interview prep:** Amazon DE interviews typically include SQL query writing, Python scripting, system design (data warehouse/pipeline), and behavioral LPs. Prepare: window functions, CTEs, GROUP BY aggregations.
5. **Leadership Principles:** Same STAR stories as SDE application, but angle toward: "Customer Obsession" (Seismos quality deliverables), "Invent and Simplify" (automating PDF extraction), "Deliver Results" (SQL dashboards enabling faster decisions).

---

## F — Recommendation

**APPLY — HIGH PRIORITY.** George's Seismos internship experience is a near-direct match for this role's JD. Not many summer 2026 applicants will have real-world ETL pipeline work from an actual internship plus a deployed data dashboard project. The graduation window fits perfectly. Apply to this *alongside* the SDE Intern (report_067) — they are different tracks. Start with DE if forced to prioritize one application effort, since the experience match is stronger here.

**Comp:** ~$52/hr × 40 hrs × 12 weeks = ~$24,960 for the summer (meets target, below SDE track)
