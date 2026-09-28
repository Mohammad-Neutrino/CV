# CV | Mohammad Ful Hossain Seikh

[![PDF Build](https://github.com/Mohammad-Neutrino/CV/actions/workflows/latex.yml/badge.svg)](https://github.com/Mohammad-Neutrino/CV/actions)
[![Overleaf Sync](https://img.shields.io/badge/Edit_on-Overleaf-47A141?logo=overleaf)](https://www.overleaf.com/project/686b4f6c89d672924116d5c4)

LaTeX-based academic CV for Mohammad Ful Hossain Seikh, Postdoctoral Researcher in Particle Astrophysics at the University of Kansas.

The canonical source is `cv.tex`. GitHub Actions automatically compiles it into `cv.pdf` whenever the source is updated.

---

## Latest PDF

**[Download CV (PDF)](https://github.com/Mohammad-Neutrino/CV/raw/refs/heads/trunk/cv.pdf)**

**[View LaTeX source](https://github.com/Mohammad-Neutrino/CV/blob/trunk/cv.tex)**

---

## Updating the CV

### Overleaf

1. Edit `cv.tex`.
2. Push or sync the updated source to the `trunk` branch.
3. GitHub Actions automatically compiles and commits the updated `cv.pdf`.

### Local editing

```bash
git clone https://github.com/Mohammad-Neutrino/CV.git
cd CV
pdflatex cv.tex
```

For routine updates, only `cv.tex` needs to be maintained.

---

## Automatic Compilation

The workflow in `.github/workflows/latex.yml`:

1. checks out the repository,
2. compiles `cv.tex`,
3. verifies that `cv.pdf` was produced,
4. commits the updated PDF back to `trunk`.

The workflow also supports manual execution from the GitHub Actions interface.

---

## Repository Structure

- `cv.tex` - current academic CV
- `cv.pdf` - automatically generated PDF
- `cv-default.tex` - earlier/default CV version
- `.github/workflows/latex.yml` - automatic PDF build workflow

---

## Citation & Reuse

The LaTeX structure and formatting of this CV may be adapted for personal academic use.

If you reuse or substantially adapt the template, please credit Mohammad Ful Hossain Seikh and link to this repository.

The biographical, scholarly, employment, publication, presentation, and other personal content in this repository is not intended for reuse.

---

## Academic Profiles

- [ORCID](https://orcid.org/0000-0002-4464-7354)
- [INSPIRE HEP](https://inspirehep.net/authors/2014116)
- [Google Scholar](https://scholar.google.com/citations?user=dSwfpWQAAAAJ)
- [ResearchGate](https://www.researchgate.net/profile/Mohammad-Ful-Hossain-Seikh)

---

## Contact

**Email:** fulhossain@ku.edu

**Website:** https://mohammad-neutrino.github.io/
