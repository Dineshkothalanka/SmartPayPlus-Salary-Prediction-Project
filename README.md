# SmartPayPlus: Salary Prediction Project

## Overview
SmartPayPlus is a machine learning project that predicts average salaries for job postings based on job and company features. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and export for deployment.

## Project Structure
```
SmartPayPlus/
├── data/
│   ├── raw/
│   ├── enriched/
│   └── processed/
├── outputs/
│   └── (plots, model, and features)
├── smartpay_salary_prediction.ipynb
└── README.md
```

## Main Files
- `smartpay_salary_prediction.ipynb`: Main notebook with all code, EDA, model training, and results.
- `outputs/best_salary_model.joblib`: Exported trained model.
- `outputs/model_features.joblib`: List of feature columns used for model input.

## How to Run
1. Open `smartpay_salary_prediction.ipynb` in Jupyter or VS Code.
2. Run all cells in order to preprocess data, train models, and evaluate results.
3. The notebook will save the trained model and feature columns for future use.

## Data
- Place your raw data files in `data/raw/`.
- Processed and enriched data will be saved in `data/processed/` and `data/enriched/`.

## Model Deployment
- The exported model and feature columns can be used for deployment in a web app (e.g., Streamlit) or for batch predictions.

## Requirements
- Python 3.8+
- pandas, numpy, scikit-learn, matplotlib, seaborn, joblib, xgboost, shap

Install requirements with:
```
pip install pandas numpy scikit-learn matplotlib seaborn joblib xgboost shap
```

## Results
- The notebook includes EDA plots, model comparison (MAE, RMSE, R²), and SHAP feature importance.

## Notes
- No sensitive features (like gender) are used, so bias mitigation is not required.
- For deployment, ensure the same preprocessing and feature order as in training.

---
Created for educational purposes. For questions, contact the project author.
Email: dineshkothalanka2003@gmail.com
LinkedIn:https://www.linkedin.com/in/dinesh-kothalanka-96362424b
