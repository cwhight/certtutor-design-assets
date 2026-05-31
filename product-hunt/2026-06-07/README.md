# CertTutor — Product Hunt launch demo screenshots

Portrait-mobile screenshots of the core CertTutor flow, **re-captured on 2026-05-31**
from production (https://certtutor.io) for the **Product Hunt launch on 2026-06-07**.

These are intended for the **Product Hunt Arcade demo** (the interactive,
click-through product walkthrough on the PH listing).

- **Device / viewport:** iPhone 13, portrait, 390x844 (mobile, touch); deviceScaleFactor 2,
  so viewport shots are 1170x1992 px. Consistent framing across all shots.
- **Source:** live production, real demo account (`demo@certtutor.io`) on SAA-C03
  (AWS Solutions Architect Associate).
- **Realistic demo data:** the diagnostic scored **65%** with a **readiness score of 59**
  (below the 72 "exam-ready" target, so the practice CTA makes sense). The gap map shows a
  genuine mix — two strong domains (Secure Architectures 83%, Resilient Architectures 80%,
  green) and two weak "Focus area" domains (High-Performing Architectures 40%,
  Cost-Optimized Architectures 50%, red). No more all-red 0% gap map.
- **AI explanation (08):** the "why you got this wrong" explanation now renders **fully
  formatted** — bold section headings, bold inline emphasis, proper paragraphs — after the
  markdown-rendering fix shipped to production. No literal `##` / `**` markers.
- **Clean mobile frame:** cookie banner pre-consented so it never appears; the floating
  "Give feedback" widget is hidden; tall pages (gap map, dashboard, AI explanation) are
  captured without any clipped content.

## Flow / order

The eight shots walk through the full new-user-to-value journey in order:

1. `01-landing.png` — Marketing landing page.
2. `02-diagnostic-intro.png` — Diagnostic intro ("before you start").
3. `03-diagnostic-question.png` — A diagnostic question with answer options.
4. `04-gap-map.png` — Gap map: per-domain accuracy breakdown with "focus area"
   weak domains highlighted.
5. `05-readiness-score.png` — Readiness score (session results hero, score vs. target).
6. `06-dashboard.png` — Dashboard hero: active cert (SAA-C03), readiness score, and
   adaptive practice CTA.
7. `07-adaptive-session.png` — Adaptive practice session: a question targeting the
   user's weakest domains with answer options.
8. `08-ai-explanation.png` — AI "why you got this wrong" explanation, streamed and
   fully rendered after answering a question.
