# Heart Disease Prediction Pipeline

This project is an end-to-end machine learning pipeline to predict heart disease using the UCI Heart Disease dataset. It was developed as part of the Applied Machine Learning (AML) course at Columbia University (Fall 2025).

## 📌 Goals

- Clean and transform noisy, incomplete medical data
- Engineer meaningful features
- Compare Naive Bayes and Linear Regression for classification
- Evaluate models with proper metrics and visualizations
- Reflect on AI-assisted workflows

## 🔍 Dataset

- Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- Task: Binary classification — does a patient have heart disease?

## 📁 Structure

- `notebook/` — Jupyter Notebook with the full ML pipeline
- `report/` — Final PDF report and visualizations
- `data/` — (Optional) Contains instructions or scripts to download the dataset
- `requirements.txt` — Dependencies

## 📈 Models Used

- Naive Bayes (GaussianNB)
- Linear Regression (with Ridge & LASSO variants)

## 🧠 AI Tool Disclosure

Tools used (e.g., ChatGPT) and their roles are detailed in the final report under the AI Usage Disclosure section.

## Project Structure

```
heart-disease-ml-pipeline/
│
├── data/                 # (optional) raw and cleaned datasets (or instructions to download)
│
├── notebook/             # Jupyter notebook(s)
│   └── heart_disease_ml_pipeline.ipynb
│
├── report/               # PDF and supporting figures
│   ├── report.pdf
│   └── figures/          # confusion matrix, ROC curve, etc.
│
├── README.md             # Project summary, setup, goals, usage
├── requirements.txt      # Python dependencies
├── .gitignore            # Ignore dataset, checkpoints, etc.
└── LICENSE               # (optional) license information
```

## 📅 Timeline

Project developed and updated daily between Sep 30 – Oct 6, 2025.
