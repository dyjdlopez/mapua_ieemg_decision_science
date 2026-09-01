# IE152-S — Classification Techniques in Data Mining

Welcome! This folder contains the lecture materials for **IE152-S: Classification Techniques in Data Mining**. This README explains what the course covers, what you're expected to be able to do by the end of it, and what software you'll need to follow along.

---

## Course Description

This course introduces you to classification techniques in data mining — including neural networks, decision trees, and their ensembles. You'll work through realistic business, operations, and management scenarios and apply classification techniques as decision-making tools in industrial and management engineering contexts, connecting each technique to a real, authentic application rather than treating it as pure theory.

**Prerequisite:** Third-year standing; prior coursework in probability and statistics is recommended.

**Note on tools:** all hands-on work in this course is done **in Python**, run on Google Colab.

---

## Course Objectives

By the end of this course, you should be able to:

1. **Interpret data-driven problems** and identify which classification technique fits a given problem.
2. **Apply decision trees and neural network derivatives** to evaluate real-world problems.
3. **Interpret classification results** and draw conclusions/decisions for real-world transactions.

---

## Course Content

The course is organized into three modules:

### Module 1 — Decision Trees and Derivatives
- Introduction to machine learning and classification methods
- Statistical and mathematical basis of classification: t-tests, chi-square
- Linear classifiers and decision boundaries
- Classification metrics (confusion matrix, accuracy, precision, recall, F1)
- Tree-based classification: decision trees, random forests
- Support Vector Machines (SVMs and SVCs)

### Module 2 — Neural Networks and Derivatives
- Introduction to deep learning
- Artificial Neural Networks: multilayer perceptrons, backpropagation
- Convolutional Neural Networks (CNNs)
- Transformer networks

### Module 3 — Software Application and Project in Real-World Scenarios
- Independent research study applying course concepts to a real dataset/problem
- Culminates in a project paper

---

## Libraries You'll Need

All notebooks run on **Google Colab**, so most of what you need is already installed — you won't need to set up a local Python environment.

| Library | What it's for |
|---|---|
| `pandas` | Loading, cleaning, and organizing your data |
| `numpy` | Numerical calculations |
| `matplotlib` | Basic plots and charts |
| `seaborn` | Statistical visualizations (distributions, correlation heatmaps) |
| `scikit-learn` (`sklearn`) | Classification models (decision trees, random forests, SVMs) and evaluation metrics |
| `scipy` | Statistical tests (t-tests, chi-square) |
| `statsmodels` | Regression/statistical diagnostics used in Module 1 — may need `!pip install statsmodels` if not already available in your Colab session |
| `tensorflow` / `keras` | Deep learning models in Module 2 (ANNs, CNNs, transformers) |

You don't need to install these yourself unless a notebook tells you to — just run the first cell of each notebook, which will handle any missing packages.

---

## How to Use These Materials

- **Presentations** are provided as PDFs — download them and review before or after each session.
- **Notebooks** (where provided) are meant to be run in Google Colab. Open the file, click "Open in Colab," and run the cells in order from top to bottom.
- If a notebook has a "TODO" or a guided exercise, that's your cue to fill something in yourself — the rest of the notebook is fully worked for you to read and run.

---

© 2026 Engr. Dylan Josh D. Lopez. Course materials for IE152-S, Mapúa University.
