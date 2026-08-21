# Mapúa University IEEMG Decision Science Online Repository
**Mapúa University — IE-EMG Department**

This repository holds the presentations, notebooks, and content/design standards for the IE15x-S data mining and computational applications course sequence, built for Q1 AY2026–2027.

**Active material development is currently focused on IE152-S and IE151P-S**, which share a unified design standard and are built in parallel.

---

## Courses in This Repo

| Code | Title | Format | Status |
|---|---|---|---|
| **IE152-S** | Classification Techniques in Data Mining | LaTeX Beamer decks + Colab notebooks | 🟢 In progress |
| **IE151P-S** | Advanced Computer Applications (Python-exclusive) | LaTeX Beamer decks | 🟢 In progress |
| IE153-S | Unsupervised and Association Rule Mining in Data Mining | — | ⚪ Not yet started |
| IE154-S | Introduction to Metaheuristics | — | ⚪ Not yet started |

IE153-S and IE154-S are part of the broader IE15x-S sequence; no presentations or notebooks have been built for them yet.

---

## Repository Structure

```
.
├── IE152-S/
│   ├── Module1/
│   │   ├── presentations/
│   │   │   └── 1.0_IntroToClassification_PRES/   # compiled .pdf
│   │   └── notebooks/
│   │       └── 1.2_RegressionReview_NB.ipynb
│   ├── Module2/                              # planned: AI/ML/DL, ANN, CNN, Sequence, Transformers
│   └── Module3/                              # planned: Data Collection Automation, Deployment & Pipelining
│
└── IE151P-S/
    ├── Module1/
    │   └── presentations/
    │       └── 1.1_IntroToComputationalTheories_PRES/
    ├── Module2/                              # planned: Data Visualization & Regression
    └── Module3/                              # planned: Data Analytics in Real-World Scenarios
```

---

## Current Build Status

### Presentations (PDF)

| Deck | Module.Lesson | Slides | Status |
|---|---|---|---|
| IE152-S — Introduction to Classification & Machine Learning | 1.0 | 26 | ✅ Complete |
| IE151P-S — Introduction to Computational Theories | 1.1 | 25 | ✅ Complete |
| *"What Do We Classify?" (data types deck)* | — | — | 🔲 Deferred from 1.0, not yet built |

### Notebooks (Google Colab)

| Notebook | Module.Lesson | Status |
|---|---|---|
| Regression Review | 1.2 | 🟡 Drafted |
| Validation Metrics | 1.3 | 🔲 Planned |
| Decision Trees | 1.4 | 🔲 Planned |
| Random Forests | 1.5 | 🔲 Planned |
| SVMs | 1.6 | 🔲 Planned |

### On the Horizon

- Deferred data-types presentation (structured → unstructured)
- Module 1 notebooks 1.3–1.6
- **Module 2:** AI/ML/DL Theory, ANN Forward & Backward Propagation, CNN Theory, Sequence Analysis, Transformers (decks + notebooks), TensorFlow/Keras Primer notebook, Cross-sectional Classification notebook
- **Module 3:** Data Collection Automation presentation, Model Deployment & Pipelining notebook

---

## Standards

All materials follow a set of house standards maintained by the instructor:

- **Content Standards** — audience profile, notebook section structure (Concept Primer → Worked Example → Guided Practice → Independent Activity → Wrap-Up), code style rules, dataset conventions, and file naming.
- **Presentation Design Principles** — Beamer workflow (discuss → build in batches of 6–8 slides → render → inspect), engine constraints (`pdflatex`-safe only), color theming, reusable macros, and documented pitfalls. This standard is the baseline for **all** IE15x-S decks, not just IE152-S.

**Audience:** Third-year Industrial Engineering majors — no CS background assumed. Notebooks emphasize demystified, explicit code (no comprehensions/lambdas) over Pythonic compactness; presentations are visual-first with minimal, always-annotated math notation.

---

## Tech Stack

- **Presentations:** Built in LaTeX Beamer (`aspectratio=169`, Madrid theme, burgundy accent `RGB(128,0,32)`); distributed as compiled PDFs — no build step required to view or use them
- **Notebooks:** Google Colab (Python, `sklearn`)
- **Datasets:** AI4I 2020 Predictive Maintenance Dataset (Module 1 shared core), Concrete Compressive Strength dataset (contrasting dataset, Lesson 1.2)

---

## Libraries & Dependencies

### Notebooks (Python / Google Colab)

All notebooks assume the Colab-preinstalled stack; only non-preinstalled packages need `!pip install`.

| Library | Purpose | Preinstalled on Colab? |
|---|---|---|
| `pandas` | Data loading, cleaning, tabular manipulation | ✅ |
| `numpy` | Numerical operations | ✅ |
| `matplotlib` | Plotting, intermediate result visualization | ✅ |
| `seaborn` | Statistical plots (distributions, correlation heatmaps) | ✅ |
| `scikit-learn` (`sklearn`) | Regression, classification models, metrics, train/test splitting | ✅ |
| `scipy` | Statistical properties checks (e.g., heteroskedasticity tests) | ✅ |
| `statsmodels` | Regression diagnostics (multicollinearity/VIF, heteroskedasticity) | ⚠️ verify per notebook; `!pip install statsmodels` if missing |

Module 2 (ANN/CNN/Transformers) and the TensorFlow/Keras Primer will additionally require:

| Library | Purpose |
|---|---|
| `tensorflow` / `keras` | Deep learning model building (ANN, CNN, Transformer notebooks) | 

This table will be extended as Module 2 and Module 3 notebooks are built.

---

## File Naming Conventions

```
Presentations:  IE152S_[Module].[Lesson]_[ShortTitle]_PRES.pdf
Notebooks:      [Module].[Lesson]_[ShortTitle]_NB.ipynb
```

---

## License

© 2026 Engr. Dylan Josh D. Lopez. All rights reserved. Course materials for internal use in IE-EMG, Mapúa University.
