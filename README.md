# 🛡️ Network Security Project – Phishing Detection Using Machine Learning & MLOps

A complete **End-to-End Machine Learning and MLOps project** for detecting phishing attacks.  
This system builds, tracks, packages, and deploys a phishing detection ML model using:

- **Machine Learning Algorithms**
- **FastAPI** backend  
- **MongoDB Atlas** cloud database  
- **MLflow** for experiment tracking  
- **DagsHub** for data + model versioning  
- **GitHub Actions** for CI/CD  
- **Docker** containerization  
- **AWS ECR + EC2** for production deployment  

This is a fully automated and production-ready cybersecurity system.

---

## 🚀 Project Overview

This project identifies phishing or malicious URLs/data using ML-based classification models.  
It includes:

- Data ingestion & preprocessing  
- Feature engineering  
- Model training & evaluation  
- MLflow experiment tracking  
- API creation using FastAPI  
- Database logging using MongoDB Atlas  
- CI/CD automation with GitHub Actions  
- Docker-based deployment on AWS EC2 using AWS ECR  

---

## 🧠 Machine Learning

Multiple ML models were trained and evaluated, including:

- Logistic Regression  
- Random Forest  
- XGBoost  
- SVM  
- Gradient Boosting  
- Decision Tree  

All experiments are tracked using **MLflow**, and the best model is selected based on evaluation metrics.

---

## 📈 Model Performance (Sample Metrics)

> ⚠️ *These are placeholder values. Replace them with actual metrics when your model is trained.*

| Metric        | Score   |
|---------------|---------|
| **Accuracy**  | 96.4%   |
| **Precision** | 95.8%   |
| **Recall**    | 96.9%   |
| **F1 Score**  | 96.3%   |
| **ROC–AUC**   | 0.985   |

---

## ⚡ FastAPI Application

A **FastAPI backend** is used to serve the phishing detection model.

### Features:
- `/predict` endpoint for real-time prediction  
- MongoDB logging of each request  
- Swagger API documentation  
- High performance (async support)

### Run FastAPI locally:

```bash
uvicorn app:app --host 0.0.0.0 --port 8000


All experimentation is tracked using **MLflow**, and results/data are stored using **DagsHub**.


## 📁 Project Structure

📦 Network Security Project (Phishing Detection)
├── data/
├── notebooks/
├── src/
│   ├── data_ingestion.py
│   ├── data_transformation.py
│   ├── model_trainer.py
│   ├── utils.py
│   └── prediction_pipeline.py
├── Dockerfile
├── requirements.txt
├── setup.py
├── app.py
├── .github/workflows/cicd.yaml
└── README.md



## 📊 MLflow Tracking

This project uses **MLflow** for:

- Experiment tracking  
- Model versioning  
- Parameter logging  
- Metrics comparison  
- Artifact storage  

All MLflow logs and metrics are synced with **DagsHub**, making experiments traceable and reproducible.

---

## 🤖 CI/CD Pipeline (GitHub Actions)

A robust CI/CD pipeline is implemented using **GitHub Actions**:

### **CI Pipeline**
- Code linting  
- Unit testing  
- Build validation  
- Docker build test  

### **CD Pipeline**
- Build Docker image  
- Push image to **AWS ECR**  
- Trigger EC2 deployment  

Workflow file is located at:


---

 🐳 Docker Containerization

The project is fully dockerized for reproducibility.


### Features

Complete ML pipeline

CI/CD automation

MLflow tracking

DagsHub integration

Cloud deployment on AWS

Docker containerization

Real-time phishing URL scanning
