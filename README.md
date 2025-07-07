# CV | Mohammad Ful Hossain Seikh

[![PDF Build](https://github.com/Mohammad-Neutrino/CV/actions/workflows/latex.yml/badge.svg)](https://github.com/Mohammad-Neutrino/CV/actions)
[![Overleaf Sync](https://img.shields.io/badge/Edit_on-Overleaf-47A141?logo=overleaf)](https://www.overleaf.com/project/686b4f6c89d672924116d5c4)

**LaTeX-based CV** for Mohammad Ful Hossain Seikh, Ph.D. Candidate in Astroparticle Physics at the University of Kansas.  
This repository contains the source files for my dynamically updated academic curriculum vitae.

---

## Latest PDF
**[Download CV (PDF)](https://github.com/Mohammad-Neutrino/CV/blob/trunk/CV.pdf)** *(Compiled in Overleaf)*

### How to Update:
1. **Edit** `CV_Type*.tex` in Overleaf.
2. **Recompile** (click "PDF" button in Overleaf).
3. **Download** the new `CV.pdf` and upload it to this repo (or use Overleaf's GitHub sync).

---

## Technical Details
- **Template**: Custom LaTeX (`report` class) with hyperref, xurl, and modern formatting.
- **Sections**: 
  - Education, Research Experience, Publications (First-Author & Collaborative)
  - Professional Service, Technical Skills, Honors/Awards
  - Outreach, Invited Lectures, Conference Presentations
- **Key Features**:
  - Hyperlinked DOIs/arXiv entries
  - Compact itemize/enumerate layouts
  - Mobile-friendly design (tested with `hyperref`) 

---

## How to Edit
### Option 1: Overleaf (Recommended)
1. **Import** this repo into [Overleaf](https://www.overleaf.com) via GitHub integration.
2. Edit `CV_Type2.tex` with real-time LaTeX preview.
3. Push changes back to GitHub via Overleaf’s Git sync.

### Option 2: Local LaTeX Editor
```bash
git clone https://github.com/Mohammad-Neutrino/CV.git
pdflatex CV_Type2.tex  # Compile locally
```

---

## Automatic Compilation
- GitHub Actions compiles the PDF on every git push (see .github/workflows/latex.yml).
- Requires latexmk and full TeX Live installation.

---

## Citation & Reuse
- **Attribution**: If adapting this template, please credit/link to this repository.
- **License**: CC-BY-NC 4.0 (Non-commercial use with attribution).

---

## Contact
- **Email**: fulhossain@ku.edu
- **Academic Profiles**:<br>
  **ORCiD**: https://orcid.org/0000-0002-4464-7354<br>
  **InspireHEP**: https://inspirehep.net/authors/2014116?ui-citation-summary=true<br>
  **Google Scholar**: https://scholar.google.com/citations?user=dSwfpWQAAAAJ<br>
  **Researchgate**: https://www.researchgate.net/profile/Mohammad-Ful-Hossain-Seikh<br>
