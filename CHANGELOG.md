# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2026-11-26] - Visual Contrast Fixes

### Fixed
- Set a solid dark background (`#0b0d17`) on `html` and `body`, removing the `background-attachment: fixed` gradient that only painted behind the viewport and left the lower page white. All section headings (white on dark) now keep high contrast across the full document and in full-page screenshots.
- Styled Contact card links in a readable light blue (`#60a5fa`, hover `#93c5fd`, underline on hover) matching the project-link palette, replacing the default dark-blue browser link colour on the dark card.

### Changed
- Renamed the third Skills card to "Data Analytics and Reporting" and the Torbay bullet to "Excel-to-Power BI Data Preparation" to avoid "Engineering" framing outside the Electrical Engineering degree. The bundled canonical CV PDF was left untouched.

## [2026-11-26] - CV Alignment 2026

### Changed
- Rewrote `index.html` to match the approved two-page UK Master CV exactly in facts, employers, dates, degrees, certifications, projects and skills.
- Set the professional title strictly to Data Analyst and the location strictly to England, UK (Willing to Relocate).
- Added Unipart Logistics at Jaguar Land Rover GPLC (via Siamo Group), Torbay Council (via Red Snapper Recruitment), and the additional UK experience entries from the Master CV.
- Updated Education to show MSc Data Science and Analytics (Distinction) and Bachelor of Electrical Engineering with CGPA 3.23 / 4.
- Updated Skills to cover Google BigQuery medallion architecture, Looker Studio (Data Studio), full Power BI stack, SQL Server and SSIS and SSRS, Azure SQL, SAP EWM and SAP ERP, Python, R (zoo), Advanced Excel and Google Apps Script.
- Updated Projects with the exact titles and tech stacks from the Master CV and removed the unverified R2 metric claim.
- Replaced the bundled `Muhammad Faizan Tariq CV.pdf` with the canonical approved two-page A4 Master CV.
- Refreshed `README.md` and confirmed all public links resolve.

### Added
- `CHANGELOG.md` and `.gitignore`.

### Security
- Confirmed zero occurrences of home address, home town, postcode, confidential employer project tokens, or job-title fabrication across all tracked files.
