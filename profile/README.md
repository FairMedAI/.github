# FairMed AI
**Research Lab · est. 2026 — Built for ALL Medical AI, not just dermatology.**

> If you can't hash it, split it, and report the gap, it doesn't count.

FairMed AI is an independent research lab auditing **medical AI systems** — dermatology, radiology, ophthalmology, pathology — for skin-tone and demographic fairness.

Most medical AI papers report high accuracy but never report:
1. Does it fail on darker skin tones?
2. Did the same image leak from train into test?

We audit that.

### Protocol (works for any medical imaging)
- **SHA256** — Hash every image, kill duplicates / leakage
- **60/20/20** — Stratified split, **seed 42**, reproducible
- **GAP REPORTED** — Per-skin-tone & per-demographic AUC / F1 / Fairness Gap

### Domains
- Dermatology [first audit]
- Radiology
- Ophthalmology
- Pathology
- Any medical imaging where fairness matters

### Open Science
MIT Code / CC-BY-4.0 Papers / Zenodo DOIs

**Links:** fairmedai.vercel.app | linkedin.com/company/fairmedai

Founder: Shanmuka Gottimukkala
