# 222 — Apple | Software Engineering Intern (Machine Learning & AI Workflows)

**Score:** 3.0/5
**URL:** https://jobs.apple.com/en-us/details/200655115-1731/software-engineering-intern-machine-learning-ai-workflows
**PDF:** ❌
**Date:** 2026-07-04
**Verification:** unconfirmed (web scan)

---

## A — Offer Snapshot

| Field | Detail |
|-------|--------|
| Company | Apple |
| Role | Software Engineering Intern (Machine Learning & AI Workflows) |
| Job ID | 200655115-1731 |
| Team | Video Computer Vision (VCV) — gaze tracking, Vision Pro, next-gen computer vision |
| Location | Cupertino, CA (on-site; also Munich listing seen) |
| Work Model | On-site |
| Duration | Standard Apple intern cycle (~12–16 weeks) |
| Pay | ~$55–65/hr estimated (Apple intern range from prior reports 035, 144, 197) |
| Degree Required | BS/MS/PhD CS or related; must return to school after OR this must be the final graduation requirement; "ideal for 2026/2027 graduates" but not hard exclusion |
| Application Deadline | Rolling — no specific deadline found |
| Work Auth | Standard US work auth assumed |
| Related Postings | report 035 (Apple AI/ML Siri, job 200606145), report 144 (ML/AI General, job 200606469), report 197 (ML/AI Undergrad, job 200664780) — all distinct job IDs |

This is a **research-engineering hybrid** role on Apple's Video Computer Vision team, which built the gaze tracking system at the core of Apple Vision Pro. Work involves ML model development, analysis, and deployment using AI workflows — pushing the boundary of what ML can do on device. The team operates closer to research than product — not typical intern-ships-a-feature work.

---

## B — George Fit Analysis + Action

**Fit:** Below threshold. The role requires hands-on PyTorch familiarity and solid experience writing ML training loops — skills George doesn't have. His Gesture Canvas project (OpenCV/MediaPipe) is the closest proof point (real-time CV with hand landmark detection), but MediaPipe is a pre-trained API, not custom model training. The VCV team builds foundation CV systems — the gap between George's cv.md and what they need is meaningful.

**Soft graduation mismatch:** The posting says "ideal for candidates graduating in 2026 or 2027." George graduates June 2028 — he qualifies technically (returns to school after summer) but is not the ideal candidate profile.

| Dimension | George | Role | Gap |
|-----------|--------|------|-----|
| PyTorch | None | Required — "hands-on familiarity" + ML training loops | ❌ Primary gap — hard requirement |
| Computer vision | Gesture Canvas: OpenCV + MediaPipe (pre-trained, real-time, exponential smoothing state machine) | VCV team — gaze tracking, Vision Pro, fundamental CV research | ⚠️ CV surface-level experience vs research depth |
| Python | Strong — multiple projects | Required ("fluency in Python") | ✅ |
| ML fundamentals | TF-IDF + Logistic Regression (scikit-learn) | Solid ML foundation required | ⚠️ Classical ML; no deep learning |
| Grad year | June 2028, returns to school | "Ideal for 2026/2027 grads"; must return to school | ⚠️ Soft mismatch — not ideal profile |

**Action:** Apply only after all 3.5+ roles are submitted. The PyTorch gap is a real blocker — Apple's screening will likely filter here. If George has time to work through PyTorch basics (fast.ai, Andrej Karpathy's neural networks course) before applying, his candidacy improves meaningfully. Do not misrepresent ML depth. The Gesture Canvas proof point is honest but not deep enough for this team's expectations.

**SKIP if:** George's application bandwidth is limited. Better uses of time are Censys (189), Snorkel AI (183), Cloudflare MLE (194), Microsoft Applied Science (220). Return to this one if those don't pan out and George has learned PyTorch by then.
