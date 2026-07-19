# Changelog

All notable changes to the résumé repository are documented here.  
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [2026.07.19] — 2026-07-19

### Added
- Nested variant structure under `resumes/`:
  ```
  resumes/
  ├── resume/          1-page résumé
  │   ├── classic/     Default font — ATS optimised  (resume.tex + resume.pdf)
  │   └── modern/      Roboto — human-friendly       (resume.tex + resume.pdf)
  └── cv/              2-page curriculum vitae
      ├── classic/     Default font — ATS optimised  (cv.tex + cv.pdf)
      └── modern/      Roboto — human-friendly       (cv.tex + cv.pdf)
  ```
- LaTeX source (`.tex`) for all 4 variants stored alongside their compiled PDF
- Compiled PDFs for all 4 variants (latest as of 2026-07-19)

### Notes
- Release assets on GitHub should be named: `resume-modern.pdf`, `resume-classic.pdf`,
  `cv-modern.pdf`, `cv-classic.pdf` to match the `/releases/latest/download/` URLs
  referenced by the portfolio site.

---

## [2025.x] — legacy (prior to 2026.07.19)

- `resumes/general/satyamtg_resume_general.pdf` — single flat PDF (superseded by above structure)