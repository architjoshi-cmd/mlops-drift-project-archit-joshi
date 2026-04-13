# 🚀 MLOps Pipeline with Data Drift Detection

## 📌 Overview
This project implements a complete **MLOps pipeline** that automates the lifecycle of a machine learning model, from data ingestion to monitoring and retraining. It also includes **data drift detection** to ensure model performance remains stable when input data changes over time.

---

## 🧩 Features
- Data ingestion and preprocessing  
- Model training and evaluation  
- Data drift detection using Evidently AI  
- Automated model retraining  
- Model versioning and comparison  

---

## ⚙️ Workflow
1. Load and preprocess dataset  
2. Train baseline model (v1)  
3. Evaluate model performance  
4. Simulate data drift  
5. Detect drift using Evidently  
6. Retrain model (v2)  
7. Compare model performance  

---

## 📁 Project Structure
├── models/
│ ├── model_v1.pkl
│ └── model_v2.pkl
├── reports/
│ └── drift_report.html
├── src/
│ ├── data_ingestion.py
│ ├── preprocessing.py
│ ├── training.py
│ ├── drift_detection.py
│ └── retraining.py
├── notebooks/
├── requirements.txt
└── README.md


---

## 📊 Outputs
- **Models**
  - `models/model_v1.pkl`
  - `models/model_v2.pkl`

- **Drift Report**
  - `reports/drift_report.html`

---

## 🛠️ Tech Stack
- Python  
- Scikit-learn  
- Pandas  
- Evidently AI  

---

## ▶️ Installation & Usage

### Clone the repository
```bash
git clone https://github.com/your-username/mlops-drift-pipeline.git
cd mlops-drift-pipeline

