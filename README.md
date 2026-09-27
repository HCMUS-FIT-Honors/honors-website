# HCMUS FIT Honors Program Website — v3
Homepage redesigned around 25 cohorts (2002–2026), ~1,100 students who have studied or are studying, and 900+ alumni.

## GitHub Pages update
Upload/replace `index.html`, `assets/css/style.css`, and the `cohorts` folder in the repository root.
GitHub Pages will redeploy automatically after commit.

Note: cohort counts 2002–2022 are based on the supplied workbook data; 2023–2026 are currently shown approximately (~40/cohort) until official rosters are added.

## v4 update
- Refined hero typography.
- “Khoa Công nghệ Thông tin” stays on a single line on normal desktop/tablet widths.
- Mobile remains responsive and may wrap naturally on narrow screens.

## v5 — cohort data
- Generated cohort pages for CNTN 2002–2022 from the supplied thesis workbook.
- Public pages intentionally omit student IDs and other administrative/private fields.
- Each cohort has a JSON data file under `data/cohorts/`.
- 2023–2026 pages are prepared as placeholders pending confirmed public data.
- Counts on these pages mean records found in the thesis workbook, not necessarily original enrollment.

## v6 — exact thesis grouping
Thesis cards are grouped by the STT structure in the original workbook.
All student rows belonging to the same STT are shown together on one thesis card.
No MSSV is published.
