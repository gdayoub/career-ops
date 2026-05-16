# Planet Labs — Intern, AI/ML Engineer

**Score:** 3.8/5
**URL:** https://job-boards.greenhouse.io/planetlabs/jobs/7714373
**PDF:** ❌
**Date:** 2026-05-16
**Status:** Evaluated

---

## A — Role Snapshot

| Field | Value |
|-------|-------|
| Company | Planet Labs PBC (NASDAQ: PL) |
| Role | Intern, AI/ML Engineer |
| Team | Software Engineering — AI/ML |
| Location | San Francisco, CA — in-office |
| Pay | $35–$60/hr (range; verify — lower end below $40 target) |
| Timeline | June 1–Aug 21 or June 22–Sep 11, 2026 (12 weeks) |
| Level | Undergraduate or graduate student eligible |
| Visa | US Person required (export control) |

---

## B — Role Description

Planet operates the world's largest fleet of earth-observation satellites, capturing daily imagery of the entire Earth's surface. The AI/ML team builds algorithms that transform raw satellite imagery into actionable intelligence.

**Responsibilities:**
- Design, implement, and evaluate novel AI/ML algorithms for image understanding
- Translate algorithms into scalable software capabilities
- Work across the full ML lifecycle: R&D prototyping through productization
- Focus areas: geospatial analytics and computer vision

**Required Qualifications:**
- Ambitious undergraduate or graduate student
- Experience with computer vision and/or ML algorithms
- Python proficiency (implied by team stack)
- US Person status (citizenship, LPR, or asylee/refugee) — export control compliance

**Preferred:**
- Experience with geospatial data or remote sensing
- ML model deployment experience
- Image processing pipelines

---

## C — Fit Assessment

### Technical Match: 4.3/5

This role maps to George's strongest technical proof points:

- **Computer vision (direct)**: Gesture Controlled Interactive Canvas — OpenCV + MediaPipe for real-time hand landmark tracking, gesture state machine, exponential smoothing. This IS a computer vision project. Planet asks for CV algorithms.
- **ML pipeline (direct)**: OSINT platform — TF-IDF + Logistic Regression classifier with model evaluation and retraining support. End-to-end ML from data ingestion to model deployment.
- **End-to-end ML lifecycle**: OSINT (R&D prototype → production Streamlit dashboard) + Seismos (raw data → production deliverables) = full lifecycle experience Planet explicitly values
- **Python**: Strong across all projects

Gap: No satellite/geospatial domain knowledge. No deep learning (CNN/ViT) experience — Planet likely uses PyTorch for image analysis, George uses scikit-learn. This could be a meaningful gap if the role requires training large vision models.

### Domain Fit: 2.5/5

Geospatial analytics and satellite imagery is a niche domain George has no prior exposure to. However, the underlying techniques (computer vision, object detection, image classification) are domain-agnostic. Planet would need to teach the geospatial layer; George brings the ML engineering foundation.

### Compensation: 3.0/5

$35–$60/hr range is wide. Lower end ($35/hr) is below George's $40/hr target. A competitive candidate with strong CV could land at $50–$60. **Verify compensation before full application investment.** Planet is a public company with standard tech intern rates — likely mid-range for the SF market.

### Career Value: 4.5/5

Planet is unique: public company, real-world ML at global scale (tens of millions of daily images), applied computer vision with visible societal impact (environmental monitoring, disaster response, geopolitical intelligence). Resume-differentiating for ML roles.

### Logistics: 3.5/5

SF in-office (5 days/week implied for a 12-week program). Requires summer relocation. Export control: "US Person" requirement — George's profile shows "no sponsorship needed" which typically indicates US citizen or LPR = eligible.

---

## D — Verdict

**Score: 3.8/5 — APPLY (verify comp first)**

Strongest proof points:
1. **Gesture Canvas + OpenCV**: "Developed real-time CV application using MediaPipe and OpenCV with dual backend support" → direct computer vision experience Planet is looking for
2. **OSINT ML pipeline**: End-to-end: data ingestion → TF-IDF/LR classifier → Streamlit production dashboard → Docker Compose deployment = full ML lifecycle
3. **Seismos**: "Collaborated to validate end-to-end data pipelines ensuring data integrity" → production-grade data handling

Before applying: **Confirm compensation will be ≥$40/hr.** Ask recruiter or check Glassdoor for Planet 2026 intern rates. If confirmed $40+, this is a high-conviction application.

---

## E — Application Notes

- Lead with Gesture Canvas as computer vision proof point: frame as "built and deployed a real-time computer vision system using OpenCV and MediaPipe, including a gesture state machine and exponential smoothing for production-quality input handling"
- Frame OSINT as end-to-end ML: "designed, trained, and deployed a TF-IDF + logistic regression classifier from raw multilingual text to production analytics dashboard"
- Mention Seismos pipeline for data integrity at scale
- Note US Person status if applicable (don't leave export control as a question mark)
- Apply early: rolling deadline, in-office SF = competitive applicant pool

---

## F — Story Bank

**STAR story — Gesture Canvas (Computer Vision):**
- **S**: Needed a hands-free drawing system using only webcam input with no specialized hardware
- **T**: Build real-time CV pipeline that maps physical hand gestures to digital canvas actions
- **A**: Implemented dual-backend MediaPipe pipeline with OpenCV, applied exponential smoothing to reduce landmark jitter, designed state machine for gesture → action mapping
- **R**: Shipped working system with real-time inference, multiple gesture modes, and audio playback integration
- **Relevance**: Directly maps to "design, implement, and evaluate AI/ML algorithms for image understanding"
