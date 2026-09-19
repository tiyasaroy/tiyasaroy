# Profile refresh - 2026-09-19

## Purpose

Position the profile around combined analytics and data-science work, with a concise, recruiter-readable introduction and only completed work featured publicly.

## Changes made

- Replaced the original README with an Analytics + Data Science portfolio introduction.
- Added `assets/data-to-report-to-model.gif`, a 24-frame looping hero animation that visualizes data flowing into reports, models, and decisions.
- Reworked the header into a compact two-column introduction and replaced the visible hero with the user-selected hosted data-points GIF.
- Corrected the email link to a `mailto:` link.
- Added short, evidence-based descriptions for the two featured completed projects.
- Preserved the exact original README in `profile-history/README-before-2026-09-19.md`.

## Profile settings changed outside this repository

- Bio changed from `I am enthusiast of Data` to `Data Analyst & Data Scientist | Analytics, machine learning, and data products`.
- Pinned repositories changed from Global Market Intelligence, Amazon Sales 2025, Multi-Agent Marketing Data Scientist, and Multi-Agent Newsroom to Global Market Intelligence and Multi-Agent Marketing Data Scientist.

## Project classification used for the profile

### Completed

- `multi-agent-marketing-data-scientist`: reproducible data, analytics modules, FastAPI dashboard, evaluation code, tests, and a substantive commit history are present.
- `AI-Driven-Global-Market-Intelligence--ML-Project`: the executed notebook contains model training, validation, tuned XGBoost, SHAP interpretation, and final predictions with no recorded error outputs.

### Under Work

- `Amazon-Sales-2025`: README promises dashboard files, screenshots, outputs, and a live demo that are absent from the repository.
- `Data---Detective`: README explicitly lists production roadmap work including authentication, persistence, async jobs, and human review.
- `multi-agent-newsroom`: README identifies the project as foundation development and describes a future agent orchestrator.
- `bigquery-google-analytics-ecommerce`: README promises dashboard, data, and image directories that are absent from the published tree.
- `Heart-Attack-Analysis-Prediction`: no README or project documentation is present.
- `Crime-data-2025`: README currently contains only a one-line description.

## Revert

To revert the repository portion, restore `README.md` from `profile-history/README-before-2026-09-19.md` and remove `assets/data-to-report-to-model.gif`, or run `git revert <profile-refresh-commit>` from a local clone. Restore the previous four pins manually from the profile's **Customize your pins** dialog if desired.
