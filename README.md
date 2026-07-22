# Consumer Finance Segmentation using K-Means Clustering

## consumer-finance-segmentation
Unsupervised machine learning project from WorldQuant University using the 2019 Survey of Consumer Finances (SCF). Built K-Means clustering models, applied PCA for visualization, evaluated clusters using inertia and silhouette scores, and deployed an interactive Plotly Dash dashboard for consumer finance segmentation.

## Overview

This project was completed as part of the **WorldQuant University – Data Science Lab: Unsupervised Learning for Consumer Finance Segmentation**.

The objective is to identify meaningful groups of households using financial information from the **2019 Survey of Consumer Finances (SCF)** through unsupervised machine learning techniques.

The project includes data preparation, feature engineering, dimensionality reduction, clustering, model evaluation, and an interactive dashboard for exploring household financial segments.

---

## Dataset

**Survey of Consumer Finances (SCF) 2019**

The analysis focuses on households that:

- Experienced or feared credit denial (`TURNFEAR == 1`)
- Have a net worth below \$2 million

---

## Project Workflow

- Load and clean SCF data
- Exploratory Data Analysis (EDA)
- Feature selection using variance and trimmed variance
- Feature scaling with StandardScaler
- K-Means clustering
- Cluster evaluation using:
  - Inertia
  - Silhouette Score
- PCA dimensionality reduction
- Interactive dashboard with Plotly Dash

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Dash
- Scikit-learn
- PCA
- K-Means Clustering
- SciPy

---

## Repository Structure

```
consumer-finance-segmentation/
│
├── data/
│   └── SCFP2019.csv.gz
│
├── notebooks/
│   └── Consumer_Finance_Segmentation.ipynb
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

## Dashboard Features

- Top variance feature comparison
- Trimmed vs untrimmed variance
- Adjustable number of clusters
- Inertia metric
- Silhouette score
- PCA visualization of household clusters

---

## Key Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Unsupervised Machine Learning
- K-Means Clustering
- Principal Component Analysis (PCA)
- Model Evaluation
- Interactive Dashboard Development
- Python Programming

---

## Author

**Luzuko Nzayo**

Mathematical Sciences Graduate

Aspiring Data Scientist
