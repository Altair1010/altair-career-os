# Altair Career OS

A local-first, bilingual (Vietnamese/English) marketing and creative job-search tracker.

## GitHub Pages
Website: https://altair1010.github.io/altair-career-os/

## Features
- Job descriptions, filters for remote/hybrid/on-site, office hours and level.
- Heuristic JD/CV matching with skill evidence, gaps, priority rationale and action checklist.
- Role-specific CV and portfolio text versions, cover-letter drafts.
- Application pipeline from Unreviewed through Offer/Rejected.
- Job board reference directory and tracked GitHub tool links.
- Local audit history and JSON/CSV backup/restore.

## Data and privacy
Code is public. Application data is **not** stored in GitHub: it remains in the browser's localStorage. Different browsers/devices do not sync. Export JSON backups regularly and do not commit private documents, API tokens or passwords to this repository.

## Start on MSI
Double-click `index.html`, or from this folder run:
```powershell
python -m http.server 4173
```
Then open http://localhost:4173.

## Scoring
Fit: skill match (55%), target role (20%), seniority (15%), work arrangement (10%).
Priority: fit (65%), deadline urgency (20%), personal interest (15%).
Scores are heuristic and not an official ATS or employer assessment.