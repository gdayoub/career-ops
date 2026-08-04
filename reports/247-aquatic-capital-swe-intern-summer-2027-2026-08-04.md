# 247 — Aquatic Capital Management | Software Engineer, Intern (Summer 2027)

**Score:** 3.7/5
**URL:** https://job-boards.greenhouse.io/aquaticcapitalmanagement/jobs/8489233002
**PDF:** ❌
**Date:** 2026-08-04
**Verification:** unconfirmed (Greenhouse API blocked by egress policy; listing confirmed via search aggregators: ZipRecruiter, Teal, LinkedIn job 4409017809; Levels.fyi confirms $135/hr rate for this company)

🟡 **NEW company — Summer 2027 cycle open. Exceptional comp ($135/hr + $10K sign-on). Chicago in-office. Apply September–October 2026 alongside other quant targets (Citadel #039, D.E. Shaw #215, Two Sigma #245).**

DISTINCT from all existing tracker entries. First evaluation of Aquatic Capital Management.

---

## A — Offer Snapshot

| Field | Detail |
|-------|--------|
| Company | Aquatic Capital Management |
| Role | Software Engineer, Intern (Summer 2027) |
| Job ID | 8489233002 |
| Location | Chicago, IL (in-office) |
| Work Model | In-office — standard for quantitative trading firms |
| Duration | ~10–12 weeks summer (typical quant internship) |
| Pay | $135/hr confirmed (Levels.fyi Summer 2026 rate; expected same for 2027) + $10,000 sign-on bonus |
| Total Package | ~$135 × 40 × 11 weeks + $10K sign-on ≈ $69,400 total — among the highest SWE intern packages in the US |
| Degree Required | BS, MS, or PhD in mathematics, statistics, machine learning, physics, computer science, or related scientific disciplines |
| Grad Requirement | Expected graduation between Fall 2027 and Spring 2028 — George (June 2028) QUALIFIES ✅ |
| Application Deadline | Rolling — apply late September/October 2026 for peak Summer 2027 recruiting window |
| Work Auth | No sponsorship expected (standard for quant firms) |
| Return Offer | High conversion rate typical for quant firms that give interns real projects |

Aquatic Capital Management is a quantitative investment manager that uses scientific research and technology to navigate global financial markets. They build high-performance, distributed systems powering both research workflows and live trading infrastructure. Culture: collaboration, meritocracy, ambition, calm determination. Company is in early-stage growth — interns have meaningful impact compared to large-firm programs.

Intern responsibilities: design tools, improve system reliability, optimize platform for low-latency/high-throughput data processing, work alongside experienced engineers and quants on real production infrastructure.

---

## B — George Fit Analysis

**Overall:** The role is engineering-focused (not quant research), which plays to George's strengths. Python is explicitly accepted (Python and/or C++). The work is building infrastructure that powers trading — not financial modeling. George's strongest proof points are data pipeline work (Seismos) and end-to-end shipping (CoverMe, LionPlanner). The gap is the distributed systems/HFT-grade infrastructure context and the C++ expectation at quant firms. Comp is exceptional — the reach is worth it.

| Dimension | George | Role | Gap |
|-----------|--------|------|-----|
| Python | Primary language — Seismos, OSINT, CoverMe backend | Python and/or C++ required | ✅ Strong match |
| C++ | Not in CV | C++ common at quant firms even when Python listed | ❌ Real gap — Python-only may be OK but risky |
| Algorithms / data structures | CS fundamentals + backtracking solver in LionPlanner; no competitive programming | Strong algorithms and systems understanding expected | ⚠️ Gap — needs LeetCode hard prep |
| Distributed systems | Docker Compose (OSINT), Cloud Run (LionPlanner), Supabase — cloud managed services | High-performance, distributed, low-latency production systems | ⚠️ Managed services ≠ bare-metal distributed systems |
| Data pipelines | Seismos: PDF extraction → Excel/SQL reports; OSINT: multi-source ingestion → PostgreSQL | Tool design for research/trading workflows | ✅ Closest relevant proof point |
| Systems programming | No low-level systems (OS, networking, concurrency) | Low-latency, high-throughput optimization expected | ❌ Gap |
| Finance domain | None | Quant trading context — not modeling, but domain familiarity helps | ⚠️ Gap — not disqualifying for SWE track |
| Grad year | June 2028 | Fall 2027 – Spring 2028 | ✅ Perfect match |
| Relocation | Open to relocation for summer | Chicago, IL in-office | ✅ |

**Score breakdown:**
- Role fit: 3.5/5 (Python match + data pipeline experience; distributed systems and C++ gap are real)
- Company / brand: 4.0/5 (elite quant firm, strong resume signal in finance and tech)
- Comp: 5/5 ($135/hr + $10K sign-on is exceptional — top 1% of intern packages nationwide)
- Timing: 5/5 (grad match is clean; Summer 2027 = exactly George's target cycle)
- Competition: 2.5/5 (quant firms are highly selective; algo prep required)
- Red flags: -1.3 (C++ gap; HFT-grade systems = stretch; Chicago relocation; domain unfamiliarity)
- **Global: 3.7/5**

---

## C — Proof Points from cv.md

| Role Requirement | George's Evidence |
|-----------------|-------------------|
| "High-performance distributed systems" | LionPlanner: containerized Cloud Run service with backtracking solver + Prisma ORM + PostgreSQL under load; OSINT: Docker Compose multi-service stack with PostgreSQL + Streamlit + NLP pipeline |
| "Design tools for engineers/quants" | Seismos: automated PDF extraction pipeline reducing manual engineering report prep time — built a tool for domain experts (engineers); Seismos SQL reporting pipelines enabling faster engineering decisions |
| "System reliability and optimization" | Seismos: collaborated with engineers to validate end-to-end data pipelines, ensured accuracy across client-facing deliverables; LionPlanner: backtracking constraint solver generating 200+ conflict-free schedules at scale |
| "High-throughput data processing" | OSINT: multilingual NLP pipeline ingesting news from Al Jazeera, BBC Arabic, CNN Arabic with dedup + normalization; Seismos: structured ETL from raw PDFs |
| "Python proficiency" | Python across all 4 major projects: Seismos, OSINT, CoverMe, Gesture Canvas; primary language in CV |
| "Algorithms and computer architecture understanding" | LionPlanner backtracking constraint solver; Gesture Canvas exponential smoothing algorithm; TF-IDF + logistic regression implementation in OSINT |

---

## D — Risks & Concerns

1. **C++ gap:** Quant firms list Python and/or C++ but historically expect C++ fluency for SWE roles. George's Python is strong, but he may be screened out early if interviews pivot to C++ (pointer arithmetic, templates, STL). Mitigate: study basic C++ (data structures, smart pointers, basic STL) before the application interview.
2. **HFT-grade distributed systems is a stretch:** Managed cloud services (Cloud Run, Supabase) are not the same as hand-rolled low-latency distributed systems. Be honest about experience level; frame Cloud Run/Docker as infra thinking, not infra expertise.
3. **Algorithm interview depth:** Quant firms probe harder on algorithms than product companies. LeetCode Hard tier is expected. George should prepare more intensively than for standard SWE internship algorithms.
4. **No finance domain:** While the SWE track doesn't require quant modeling, familiarity with trading concepts (order books, market microstructure, latency) is valued. Read: "Flash Boys" or "Quantitative Finance" basics.
5. **Sign-on compensation uncertainty:** The $135/hr + $10K sign-on is from Levels.fyi Summer 2026 data. Summer 2027 may differ slightly — verify before negotiating.

---

## E — Application Strategy

1. **Apply September–October 2026** alongside other quant targets: Citadel (#039), Citadel Securities (#228), D.E. Shaw (#215/216), Two Sigma (#245), Optiver (#225), IMC (#226). Aquatic is a secondary quant target behind the first four but worth applying given the exceptional comp and cleaner grad match.
2. **Lead resume angle:** Seismos data pipeline work (automated PDF → SQL ETL for engineering teams) is the closest analog to Aquatic's "design tools for quants" mission. Quantify the impact: "reduced manual stage report preparation time for engineering teams."
3. **Cover letter hook:** "I build the infrastructure that lets domain experts focus on their work" — Seismos is exactly this (George built the pipeline so engineers could spend time on seismic analysis, not data cleaning). Aquatic SWE interns do the same for quants.
4. **Algorithm prep:** Start LeetCode Hard now. Aquatic will probe algorithms. Focus on: arrays/graphs/trees, dynamic programming, and basic concurrency patterns.
5. **Consider applying to both tracks:** Aquatic also has a Quantitative Research Intern (Summer 2027) track. That requires stronger quant background — apply SWE first; secondary consideration for Quant Research.

---

## F — Recommendation

**Apply — exceptional comp justifies the reach.** $135/hr + $10K sign-on makes this one of the highest-paying intern packages in the US. The role is SWE-track (not quant research), which plays to George's engineering strengths. Python is explicitly OK. The gaps (C++, HFT-grade systems, algorithms) are real but not disqualifying — quant firms hire strong generalist engineers too. Apply in October 2026 alongside other quant targets.

**Expected comp:** $135/hr × 40 hrs × 11 weeks + $10K sign-on ≈ **$69,400 for the summer** — top 1% of intern packages nationwide.

**⚠️ Action items:**
- Apply October 2026 (rolling but peak window)
- Prep LeetCode Hard before applying — quant interview standards are higher
- Study basic C++ before phone screen in case they probe it
- Lead with Seismos on resume and cover letter — most direct analog to "tools for domain experts"
- Verify comp details when offer arrives ($135/hr historical; confirm 2027 rate)
