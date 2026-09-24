# Phase 5 — Machine Learning (10–12 weeks, ~140 hrs)

Goal: go from "I did ML inside the HarvardX course" to genuinely fluent, industry-standard machine learning — the actual center of the "Data Scientist" title.

## Courses

### 1. Machine Learning Specialization — Stanford / DeepLearning.AI (Andrew Ng)
**~60–70 hrs** across all 3 courses, auditable free on Coursera.
- https://www.coursera.org/specializations/machine-learning-introduction
- This is the modern, actively-maintained successor to Andrew Ng's original legendary Stanford ML course — the single most-recommended machine learning course on the internet, for good reason. Covers supervised learning (regression, classification), neural network basics, and unsupervised learning (clustering, anomaly detection, recommender systems), all with real coding exercises in Python/NumPy.
- For the more mathematically rigorous original version of this material, Stanford's actual **CS229 lecture videos** are free on YouTube and worth dipping into for a deeper theoretical treatment of anything the Specialization moves quickly through: https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU — course site: https://cs229.stanford.edu/

### 2. Kaggle Learn — Intro to Machine Learning, Intermediate Machine Learning, Feature Engineering
**~15 hrs total.**
- https://www.kaggle.com/learn
- Fast, hands-on, scikit-learn-based. "Intermediate Machine Learning" specifically covers missing values, categorical encoding, pipelines, cross-validation, and XGBoost — all things you'll be expected to know cold in a DS interview.

### 3. MIT 6.0002 — Introduction to Computational Thinking and Data Science
**~30–40 hrs.**
- https://ocw.mit.edu/courses/6-0002-introduction-to-computational-thinking-and-data-science-fall-2016/
- MIT's own intro to the computational side of data science: optimization, stochastic thinking, sampling, Monte Carlo simulation, and machine learning fundamentals, all in Python. A different (and useful) angle on material you've now seen from Stanford/DeepLearning.AI and Harvard.

### 4. Google Advanced Data Analytics Professional Certificate (audit or full)
**~50–60 hrs** for the technical content (full suggested pace is ~6 months part-time; move faster).
- https://www.coursera.org/professional-certificates/google-advanced-data-analytics
- The direct follow-on to the Google Data Analytics certificate from Phase 3. Adds Python-based statistics, regression, machine learning, and — notably — a full capstone project structured explicitly like a real workplace data science project, which is excellent portfolio material and interview-story material ("walk me through a project" answers write themselves from this).

## Suggested order

1. Machine Learning Specialization first — it's the conceptual backbone.
2. Kaggle Learn's ML tracks alongside it, for hands-on scikit-learn reps.
3. MIT 6.0002 for a second pass at the underlying computational thinking.
4. Google Advanced Data Analytics Professional Certificate last — by this point its material will move quickly, and its capstone becomes a strong portfolio piece.

## Portfolio output

An **end-to-end supervised machine learning project**: pick a prediction problem (classification or regression) on a real dataset, do a proper train/validation/test split, try at least two model types, tune hyperparameters, and report honest evaluation metrics (not just accuracy — precision/recall/F1 or RMSE/MAE as appropriate, and a discussion of *why* the metric you chose fits the problem). This, plus the Google Advanced Data Analytics capstone, gives you two strong ML projects for `projects/`.

## You're done when

- You can explain bias/variance tradeoff, overfitting, and cross-validation without notes.
- You can build a scikit-learn pipeline from raw data to evaluated model without copy-pasting a tutorial.
- You have at least one finished, evaluated, documented ML project in `projects/`.

Move to [Phase 6](../06-deep-learning-advanced/README.md).
