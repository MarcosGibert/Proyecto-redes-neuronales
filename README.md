# Employee Attrition: ANN vs Ensemble Models

Code repository for the paper **"Predicción de la rotación laboral mediante Redes Neuronales Multicapa: una comparación con modelos clásicos de machine learning"**, Universitat Politècnica de València, May 2026.

## Overview

This project investigates whether a well-designed Artificial Neural Network (ANN) can match the performance of classical machine learning models — Logistic Regression, Random Forest and XGBoost — on a tabular HR analytics dataset.

## Repository structure

```
├── Employee_Attrition_Final.ipynb   # Main notebook
├── attrition.csv                    # Dataset (HR Analytics: Job Change of Data Scientists)
└── README.md
```

## Requirements

```
tensorflow
scikit-learn
xgboost
shap
pandas
numpy
matplotlib
```

Install all dependencies with:

```bash
pip install tensorflow scikit-learn xgboost shap pandas numpy matplotlib
```

## Usage

The notebook is self-contained and runs top to bottom. Set the `DATA_PATH` variable at the top of the notebook to point to `attrition.csv` if needed.

If running on Google Colab, upload `attrition.csv` to your Drive and update the path accordingly.

## Dataset

HR Analytics: Job Change of Data Scientists, available on [Kaggle](https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists).

## Authors

Josselyn Bonilla Albán & Marcos Gibert Robles  
Máster en Ingeniería en Análisis de Datos, Mejora de Procesos y Toma de Decisiones  
Universitat Politècnica de València
