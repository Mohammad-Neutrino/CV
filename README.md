
# Academic CV

**Mohammad Ful Hossain Seikh**  
Postdoctoral Researcher, Department of Physics & Astronomy, University of Kansas

[![Build CV PDF](https://github.com/Mohammad-Neutrino/CV/actions/workflows/latex.yml/badge.svg)](https://github.com/Mohammad-Neutrino/CV/actions/workflows/latex.yml)

**[View or download the latest CV (PDF)](https://github.com/Mohammad-Neutrino/CV/blob/trunk/cv.pdf)** · [Complete publication list (PDF)](https://github.com/Mohammad-Neutrino/Publications/blob/trunk/Publications.pdf) · [Personal website](https://mohammad-neutrino.github.io/) · [INSPIRE-HEP](https://inspirehep.net/authors/2014116) · [Google Scholar](https://scholar.google.com/citations?user=dSwfpWQAAAAJ) · [ORCID](https://orcid.org/0000-0002-4464-7354)

This repository contains the LaTeX source and maintained PDF of my academic curriculum vitae. My research focuses on particle astrophysics and neutrino astronomy, particularly radio detection of ultra-high energy particles, detector instrumentation, calibration, and data analysis.

## About the CV

The document includes:

- Education, research appointments, and analysis roles.
- Scientific software development, field experience, and selected research projects.
- First-author publications, manuscripts, and selected collaborative papers.
- Invited talks, teaching, research mentoring, and professional service.
- Conference presentations, technical proficiencies, honors, and awards.

The CV highlights a selection of collaborative publications. The [full publication record](https://github.com/Mohammad-Neutrino/Publications/blob/trunk/Publications.pdf), maintained in a separate repository, includes additional contributions to the ARA, RNO-G, ARIANNA, IceCube, IceCube-Gen2, PUEO, TAROGE-M, and RET Collaborations.

## Repository files

| Path | Purpose |
| --- | --- |
| [`cv.pdf`](cv.pdf) | Latest compiled CV, maintained by GitHub Actions. |
| [`cv.tex`](cv.tex) | Main LaTeX source and authoritative version of the CV. |
| [`.github/workflows/latex.yml`](.github/workflows/latex.yml) | GitHub Actions workflow for compiling and updating the PDF. |
| [`.gitignore`](.gitignore) | Excludes temporary LaTeX and system files. |

## Updating the CV

The LaTeX source is maintained in a separate Overleaf project and synchronized with the `trunk` branch of this repository.

1. Edit and compile `cv.tex` in Overleaf using **XeLaTeX**.
2. Pull any newer GitHub changes into Overleaf first, when applicable.
3. Use the Overleaf GitHub integration to push source changes to `trunk`.
4. The [CV build workflow](https://github.com/Mohammad-Neutrino/CV/actions/workflows/latex.yml) compiles `cv.tex` and commits the updated `cv.pdf`.

Saving in Overleaf does not automatically push changes to GitHub. The updated PDF becomes available after the source is pushed and compilation succeeds.

### Compiling locally

Install a LaTeX distribution supporting XeLaTeX, `latexmk`, `academicons`, `fontawesome5`, and the packages required by `cv.tex`.

```bash
git clone https://github.com/Mohammad-Neutrino/CV.git
cd CV
latexmk -xelatex cv.tex
```

This produces `cv.pdf` locally. XeLaTeX is required for the academic profile icons used in the current CV.

## Maintenance notes

- Maintain the latest CV in `cv.tex`; the PDF is a generated output.
- Keep appointments, talks, publications, honors, and dates current.
- Keep selected collaborative publications consistent with the [complete publication list](https://github.com/Mohammad-Neutrino/Publications).
- Verify hyperlinks, publication identifiers, and citation information before publishing changes.
- Include only material approved for public release, particularly when describing manuscripts under collaboration review.

## Attribution and reuse

The LaTeX formatting is shared for transparency and may be adapted for personal academic use with attribution to Mohammad Ful Hossain Seikh and a link to this repository.

The biographical details, appointments, achievements, and scholarly content are specific to the author and are not intended for reuse.

## Academic profiles and contact

[Personal website](https://mohammad-neutrino.github.io/) · [INSPIRE-HEP](https://inspirehep.net/authors/2014116) · [Google Scholar](https://scholar.google.com/citations?user=dSwfpWQAAAAJ) · [ORCID](https://orcid.org/0000-0002-4464-7354) · [ResearchGate](https://www.researchgate.net/profile/Mohammad-Ful-Hossain-Seikh) · [Scopus](https://www.scopus.com/authid/detail.uri?authorId=57426893600)

For corrections or professional inquiries: **[fulhossain@ku.edu](mailto:fulhossain@ku.edu)**.
