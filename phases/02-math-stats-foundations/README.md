# Phase 2 — Math & Statistics Foundations (10–12 weeks, ~140 hrs)

This is the phase that most self-taught data scientists skip or rush, and it's exactly the phase that separates "can call `.fit()` on a model" from "understands what the model is actually doing" — which is the whole difference employers mean when they say they want someone with "real" depth. It's also the phase most directly answering the "doctorate-equivalent" part of your goal: this is genuine MIT undergraduate math coursework, not a simplified version of it.

## Courses

### 1. Khan Academy — Statistics and Probability
**~30–40 hrs.**
- https://www.khanacademy.org/math/statistics-probability
- Free, interactive, self-paced, with practice problems and instant feedback — the best on-ramp before tackling MIT's more rigorous treatment below. Covers descriptive statistics, distributions, sampling, confidence intervals, hypothesis testing, and regression basics.

### 2. Khan Academy — Precalculus / Calculus gap-filling
**~10–20 hrs, as needed.**
- https://www.khanacademy.org/math
- If it's been years since algebra, functions, or derivatives, spend time here first. Skip anything you're already comfortable with — this is remediation, not a full course, and MTSU coursework likely already covers a good chunk of it.

### 3. MIT OpenCourseWare 18.06 — Linear Algebra (Gilbert Strang)
**~50–60 hrs.**
- https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/
- The actual MIT course, full lecture videos, problem sets, and exams, free. Strang's teaching here is legendary for a reason — this is the single most important math course for understanding how machine learning actually works under the hood (vectors, matrices, eigenvalues/eigenvectors, singular value decomposition — all of which show up directly in PCA, embeddings, and neural network internals).
- Don't just watch — do the problem sets. Passive watching won't build the intuition you need later.

### 4. MIT OpenCourseWare 18.05 — Introduction to Probability and Statistics
**~50–60 hrs.**
- https://ocw.mit.edu/courses/18-05-introduction-to-probability-and-statistics-spring-2022/
- MIT's actual course materials: lecture notes, problem sets, and R-based labs. This is where Khan Academy's intuition gets formalized into the real mathematical machinery — Bayes' theorem, likelihood, estimation, hypothesis testing — that underlies every statistical method you'll use later.

## Suggested order

1. Khan Academy Statistics & Probability first (builds intuition fast, low friction).
2. MIT 18.06 Linear Algebra in parallel or immediately after (it doesn't depend on the statistics course).
3. MIT 18.05 last — it moves faster and assumes the intuition Khan Academy already gave you.

## Why this matters for the "doctorate-equivalent" goal

Every methods course later in this roadmap — regression, machine learning, deep learning — is, underneath, linear algebra plus probability plus optimization. Skipping this phase means those later courses become "follow the recipe" instead of "understand the mechanism," which is exactly the gap between a bootcamp-level practitioner and someone who can reason about *why* a model is failing, tune it intelligently, or read a research paper and actually follow the math. This phase is what closes that gap.

## You're done when

- You can compute eigenvalues/eigenvectors of a small matrix by hand and explain what they mean geometrically.
- You can explain the difference between a p-value and a confidence interval to a non-technical person, correctly.
- You can derive (or at least closely follow the derivation of) linear regression's normal equations from calculus/linear algebra first principles.

Move to [Phase 3](../03-data-analysis-visualization/README.md).
