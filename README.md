# 🛡️ Network Security Project – Phishing Detection Using Machine Learning

An end-to-end **Network Security & Phishing Detection** project using Machine Learning and full MLOps integration.  
This system detects phishing or malicious data using ML algorithms and is fully automated using CI/CD, MLflow, Docker, and AWS cloud deployment.

---

## 🚀 Project Overview

Cybersecurity threats such as **phishing** are increasing rapidly.  
This project develops a scalable ML-based system that:

- Detects phishing URLs/data  
- Automatically trains and evaluates ML models  
- Tracks all experiments using MLflow  
- Uses GitHub Actions for CI/CD  
- Containers the model using Docker  
- Deploys the final model on **AWS EC2** through **AWS ECR**

---

## 🧠 Machine Learning Approach

We used several ML algorithms to detect phishing attacks, including:

- Logistic Regression  
- Random Forest  
- XGBoost  
- Decision Tree  
- SVM  
- Gradient Boosting  

The best-performing model is selected based on:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

All experimentation is tracked using **MLflow**, and results/data are stored using **DagsHub**.

---

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



---

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

## 🐳 Docker Containerization

The project is fully dockerized for reproducibility.


### Features

Complete ML pipeline

CI/CD automation

MLflow tracking

DagsHub integration

Cloud deployment on AWS

Docker containerization

Model version control

Reproducible experiments

📌 Future Enhancements

Deploy using AWS Lambda (serverless)

Add deep learning models (LSTM/Transformers)

Add a React/Streamlit web dashboard

Real-time phishing URL scanning
