🚀 MLOps Pipeline with Data Drift Detection
📌 Project Description

This repository demonstrates a production-ready MLOps pipeline that automates the end-to-end lifecycle of a machine learning model. It integrates data processing, model training, evaluation, monitoring, and continuous improvement through automated retraining.

A key highlight of this project is the implementation of data drift detection, ensuring model reliability when faced with changing data distributions in real-world environments.

🧩 Key Features
📥 Data ingestion and validation
🔄 Data preprocessing and feature engineering
🤖 Model training and performance evaluation
📊 Data drift detection using Evidently AI
🔁 Automated model retraining pipeline
🗂️ Model versioning and comparison
⚙️ Workflow

The pipeline follows a structured workflow:

Dataset Loading – Import and prepare raw data
Initial Training – Train baseline model (v1)
Evaluation – Assess model performance using metrics
Drift Simulation – Introduce changes in input data
Drift Detection – Identify distribution shifts
Retraining – Train updated model (v2)
Comparison – Analyze performance improvements
📁 Project Structure
├── models/
│   ├── model_v1.pkl
│   └── model_v2.pkl
├── reports/
│   └── drift_report.html
├── src/
│   ├── data_ingestion.py
│   ├── preprocessing.py
│   ├── training.py
│   ├── drift_detection.py
│   └── retraining.py
├── notebooks/
├── requirements.txt
└── README.md
📊 Outputs
✅ Trained Models
model_v1.pkl – Baseline model
model_v2.pkl – Retrained model
📈 Drift Report
Interactive HTML report generated using Evidently
🛠️ Tech Stack
Category	Tools/Frameworks
Language	Python
ML Library	Scikit-learn
Data Handling	Pandas
Monitoring	Evidently AI
▶️ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/mlops-drift-pipeline.git
cd mlops-drift-pipeline
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Pipeline
python src/training.py
python src/drift_detection.py
📌 Use Cases
Monitoring ML models in production
Detecting data distribution shifts
Automating retraining workflows
Building scalable MLOps systems
📈 Future Enhancements
Integration with CI/CD pipelines
Deployment using Docker & Kubernetes
Real-time drift monitoring
Experiment tracking with MLflow
🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

📄 License

This project is licensed under the MIT License.
