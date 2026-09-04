# Diabetes Risk Classification — Historical ML Project

> Historical machine-learning project from my earlier Data Science work. It is preserved as part of my progression toward Data Engineering and production data systems.

## Overview

This repository explores a binary classification problem using structured clinical variables from the included `diabetes.csv` dataset. The original notebook covers data exploration, preprocessing and predictive modeling.

**Important:** this is an educational data-science project. It is **not** a medical device, diagnostic system or substitute for clinical judgment.

## Data fields

| Feature | Meaning |
|---|---|
| `Pregnancies` | Number of pregnancies |
| `Glucose` | Glucose measurement |
| `BloodPressure` | Blood-pressure measurement |
| `SkinThickness` | Skin-fold thickness |
| `Insulin` | Insulin measurement |
| `BMI` | Body Mass Index |
| `DiabetesPedigreeFunction` | Family-history-related score |
| `Age` | Age |
| `Outcome` | Binary target (`0` / `1`) |

## Repository structure

```text
.
├── diabetes_risk_classification.ipynb  # analysis and modeling
├── diabetes.csv                         # dataset used by the notebook
├── requirements.txt                     # reproducibility dependencies
└── .github/workflows/quality.yml         # lightweight data/notebook checks
```

## Reproduce locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook diabetes_risk_classification.ipynb
```

## What this project demonstrates

- exploratory analysis of tabular data;
- binary classification workflow;
- feature preparation and model evaluation;
- use of Python, Pandas and scikit-learn in a notebook workflow.

## Portfolio context

My current work is centered on **Data Engineering, lakehouse architecture, distributed processing, data quality and cloud data platforms**. See [`harrisvailvelame/pedrohvel`](https://github.com/harrisvailvelame/pedrohvel) for the current engineering portfolio.

---

**Author:** Harrison Grant Vail  
[LinkedIn](https://www.linkedin.com/in/harrison-grant-vail) · [GitHub](https://github.com/harrisvailvelame)
