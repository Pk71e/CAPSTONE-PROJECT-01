# CAPSTONE_PROJECT-1
AnomaData

# AnomaData (Automated Anomaly Detection for Predictive Maintenance) (AnomaData.xlsx)

This project builds an NLP-based machine learning model to classify customer text reviews into emotional intensities: **AnomaData**.

## 📁 Project Structure

```
AnomaData/
├── data/
│   └── AnomaData.xlsx
├── AnomaData.ipynb
├── AnomaData.pkl
├── README.md
└── report/
    └── final_report.pdf
```

## ⚙️ Installation

1. Clone the repository or extract the zip file.
2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## 🚀 Running the Project

1. Open the notebook:
   ```
   jupyter notebook AnomaData.ipynb
   ```

2. Follow the steps in the notebook to:
   - Load and clean the data
   - Train and evaluate the model
   - Tune hyperparameters
   - Save the final model

3. The final model is saved as `AnomaData.pkl` and can be used in a Flask API.

## 🧪 Model Performance

- Uses XGBoost - cross validation
- Accuracy > 98% on test data
- Includes classification report and F1 score

## 📦 Deployment

The model can be deployed using a Flask or FastAPI REST API for real-time predictions. Example snippet:

```python
from flask import Flask, request, jsonify
import joblib



## 📝 Anoma_data.csv(🔗)
https://kh3-ls-storage.s3.us-east-1.amazonaws.com/DS%20Project%20Guide%20Data%20Set/AnomaData.xlsx
