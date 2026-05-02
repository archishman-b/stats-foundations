# Statistical Foundations for Strategy Professionals

> A structured reference guidebook — 18 chapters, ~340 terms — explaining the statistical vocabulary that underpins every predictive model, experiment, and analytical decision in modern business.

**Live site →** [archishman-b.github.io/stats-foundations](https://archishman-b.github.io/stats-foundations)  
**Companion →** [ML Strategy Playbook](https://archishman-b.github.io/ml-for-strategy/ML_Strategy_Playbook.html)

---

## What this is

This guidebook bridges the gap between *understanding that statistics matters* and *knowing what to ask when a data scientist presents results*. Built for strategy consultants, product managers, and analytics-adjacent professionals who need to work fluently with quantitative evidence — not to build models, but to challenge, interpret, and act on them.

Each of the ~340 terms is explained through five lenses:

| Field                | What it captures                                                   |
| -------------------- | ------------------------------------------------------------------ |
| **Intuition**        | What the concept *tells you* in plain language                     |
| **Formula / Rule**   | The math plus a plain-English translation                          |
| **When you see it**  | The business contexts where it appears                             |
| **Red flag**         | The one question to ask before trusting any result that invokes it |
| **Business example** | A realistic industry scenario with actual numbers                  |

---

## Curriculum

### Part 1 — Thinking With Data

| Ch  | Title                                          | Key Topics                                                                   |
| --- | ---------------------------------------------- | ---------------------------------------------------------------------------- |
| 01  | Statistical Thinking and the Analytics Mindset | Variation, signal/noise, inference, cognitive bias, association vs causation |
| 02  | Data Fundamentals — Types, Quality & Structure | Variable types, MCAR/MAR/MNAR, leakage, concept drift, PSI                   |

### Part 2 — Describing What You Have

| Ch  | Title                         | Key Topics                                                              |
| --- | ----------------------------- | ----------------------------------------------------------------------- |
| 03  | Measures of Centre and Spread | Mean, median, variance, IQR, skewness, kurtosis, z-score, normalisation |

### Part 3 — Probability and Uncertainty

| Ch  | Title                                             | Key Topics                                                                                 |
| --- | ------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| 04  | Probability Foundations — Language of Uncertainty | Conditional probability, Bayes' theorem, prior/posterior, base rate neglect, distributions |

### Part 4 — Inference: From Sample to Truth

| Ch  | Title                                             | Key Topics                                                                            |
| --- | ------------------------------------------------- | ------------------------------------------------------------------------------------- |
| 05  | Sampling, Estimation & Confidence Intervals       | Sampling bias, CLT, standard error, bootstrap, MLE, bias-variance tradeoff            |
| 06  | Hypothesis Testing — Is This Real or Noise?       | p-value, Type I/II errors, statistical power, multiple testing, Bonferroni, p-hacking |
| 07  | Comparing Groups — t-Tests, ANOVA & Nonparametric | Two-sample t-test, paired t-test, ANOVA, chi-square, Mann-Whitney, effect size        |

### Part 5 — Relationships in Data

| Ch  | Title                                   | Key Topics                                                                                  |
| --- | --------------------------------------- | ------------------------------------------------------------------------------------------- |
| 08  | Correlation, Association & Common Traps | Pearson, Spearman, Cramér's V, spurious correlation, Simpson's paradox, ecological fallacy  |
| 09  | Regression Fundamentals                 | OLS, coefficient interpretation, R², residuals, multicollinearity, VIF, logistic regression |
| 10  | Causal Inference & Experimental Design  | Potential outcomes, RCT, DiD, IV, RDD, uplift modelling, SRM                                |

### Part 6 — Prediction

| Ch  | Title                                      | Key Topics                                                                               |
| --- | ------------------------------------------ | ---------------------------------------------------------------------------------------- |
| 11  | Predictive Modeling Fundamentals           | Bias-variance tradeoff, cross-validation, train/val/test split, feature engineering, GBM |
| 12  | Regularisation & Model Complexity          | Ridge (L2), Lasso (L1), ElasticNet, hyperparameter tuning, dropout                       |
| 13  | Classification Metrics                     | Confusion matrix, precision, recall, F1, AUC-ROC, Gini, KS statistic, calibration        |
| 14  | Regression, Forecast & Calibration Metrics | MAE, RMSE, MAPE, forecast bias, rolling bias drift, prediction intervals, pinball loss   |

### Part 7 — Unsupervised Methods

| Ch  | Title                     | Key Topics                                                            |
| --- | ------------------------- | --------------------------------------------------------------------- |
| 15  | Segmentation & Clustering | K-means, hierarchical, DBSCAN, GMM, silhouette score, scree plot, PCA |

### Part 8 — Time and Sequential Data

| Ch  | Title                     | Key Topics                                                                          |
| --- | ------------------------- | ----------------------------------------------------------------------------------- |
| 16  | Time Series & Forecasting | STL decomposition, stationarity, ADF test, ARIMA/SARIMA, structural breaks, Prophet |

### Part 9 — Applied Analytics

| Ch  | Title                           | Key Topics                                                                              |
| --- | ------------------------------- | --------------------------------------------------------------------------------------- |
| 17  | Business Analytics Applications | CLV, survival analysis (Kaplan-Meier, Cox PH), anomaly detection, price elasticity, MMM |

### Part 10 — Responsible Analytics

| Ch  | Title                                       | Key Topics                                                                              |
| --- | ------------------------------------------- | --------------------------------------------------------------------------------------- |
| 18  | Model Governance, Explainability & Fairness | Model risk (SR 11-7), model cards, SHAP, PDP/ICE, demographic parity, equal opportunity |

---

## Design

- **Typography** — Playfair Display (headings) · Source Serif 4 (body) · JetBrains Mono (labels, formulas)
- **Dark mode** — full `prefers-color-scheme: dark` support across all chapters
- **Keyboard shortcuts** — press `e` to expand all terms, `c` to collapse all
- **Self-contained** — each chapter is a standalone HTML file; no build step, no dependencies, no server required

---

## Repository structure

	stats-foundations/
	├── index.html                        ← Landing page and chapter navigator
	├── ch01_statistical_thinking.html
	├── ch02_data_fundamentals.html
	├── ch03_descriptive_stats.html
	├── ch04_probability.html
	├── ch05_sampling_estimation.html
	├── ch06_hypothesis_testing.html
	├── ch07_comparing_groups.html
	├── ch08_correlation.html
	├── ch09_regression.html
	├── ch10_causal_inference.html
	├── ch11_predictive_modeling.html
	├── ch12_regularisation.html
	├── ch13_classification_metrics.html
	├── ch14_forecast_metrics.html
	├── ch15_segmentation_clustering.html
	├── ch16_time_series.html
	├── ch17_business_analytics.html
	└── ch18_model_governance.html

---

## Part of the 50-week portfolio

This guidebook is one artifact in a 50-week GitHub portfolio building public evidence of strategy-analytics capability.

| Artifact                   | Link                                                                                                               |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Career Intelligence Map    | [archishman-b.github.io/career-intelligence-map](https://archishman-b.github.io/career-intelligence-map/)          |
| ML Strategy Playbook       | [archishman-b.github.io/ml-for-strategy](https://archishman-b.github.io/ml-for-strategy/ML_Strategy_Playbook.html) |
| DataBridge                 | [archishman-b.github.io/databridge](https://archishman-b.github.io/databridge/databridge.html)                     |
| Portfolio Roadmap          | [archishman-b.github.io/portfolio-roadmap](https://archishman-b.github.io/portfolio-roadmap/)                      |
| Stats Foundations *(this)* | [archishman-b.github.io/stats-foundations](https://archishman-b.github.io/stats-foundations)                       |

---

*Built by [Archishman Bandyopadhyay](https://archishman-b.github.io) · Strategy Consultant, Accenture Technology Strategy*
