# Phase 4 — Harvard Data Science Professional Certificate (10–14 weeks, ~150 hrs)

This is the anchor "Harvard" piece of the roadmap: HarvardX's **Professional Certificate in Data Science**, a 9-course series taught by Prof. Rafael Irizarry, built around real case studies (including actual epidemiological and public health data). It's rigorous, R-based (a deliberate and valuable contrast to the Python-heavy rest of this roadmap — many DS teams use both), and widely respected.

- Series home: https://www.edx.org/professional-certificate/harvardx-data-science
- Harvard's own listing: https://pll.harvard.edu/series/professional-certificate-data-science
- **Every course can be audited for free.** You only pay if you want a verified certificate for each course — see [`CERTIFICATION-PATHS.md`](../../CERTIFICATION-PATHS.md).

## The 9 courses

1. **R Basics** — syntax, data structures, vectors, functions.
2. **Visualization** — ggplot2, principles of visual data communication.
3. **Probability** — the mathematical foundation for everything that follows (builds directly on Phase 2's MIT 18.05).
4. **Inference and Modeling** — how election forecasting and polling actually work, taught through real historical election data.
5. **Productivity Tools** — Unix/Linux shell, Git/GitHub, R Markdown — practical skills for reproducible work.
6. **Wrangling** — importing, cleaning, and reshaping real (messy) data.
7. **Linear Regression** — the workhorse model, taught rigorously from the ground up.
8. **Machine Learning** — classification, regression, cross-validation, and the famous case study of building a movie recommendation system (the same dataset used in the real Netflix Prize competition).
9. **Capstone** — you apply everything to two full projects, including recreating a movie recommendation system and analyzing a real dataset of your choosing.

## Why this phase exists in the roadmap

Phases 1–3 gave you Python-centric practitioner skills. This phase gives you the same material taught the way a top university actually teaches it — theory-first, case-study-driven, with real assessments — and does it in R, which is still heavily used in biostatistics, academic research, and some industry data science teams. Being bilingual in Python and R is a genuine differentiator on a resume, and directly supports the "doctorate-equivalent training" goal: this is, essentially, an accelerated version of the first-year coursework in an actual Harvard data science graduate program, released publicly.

## Suggested pace

Roughly one course every 1–1.5 weeks at 10–15 hrs/week, in the order listed above — later courses depend on earlier ones (Probability before Inference and Modeling; Wrangling before Linear Regression; everything before the Capstone).

## Portfolio output

The **Capstone course itself produces two portfolio-ready projects**: the MovieLens recommendation system and a capstone analysis of a dataset you choose. Push both, cleaned up with proper READMEs, to `projects/` — see [`projects/README.md`](../../projects/README.md).

## You're done when

- All 9 courses are completed (audited, with certificates purchased if pursuing the credential — see [`CERTIFICATION-PATHS.md`](../../CERTIFICATION-PATHS.md)).
- You can write clean, idiomatic R using the tidyverse (dplyr, ggplot2) as comfortably as you now write pandas/matplotlib in Python.
- Your capstone projects are finished, documented, and pushed to `projects/`.

Move to [Phase 5](../05-machine-learning/README.md).
