# Industrial Manufacturing Machine Efficiency Prediction using MLOps 🚀

This project demonstrates a full MLOps pipeline for predicting the efficiency of smart manufacturing machines using real-time telemetry data. Built with cloud-native technologies and deployed via CI/CD automation using Jenkins, ArgoCD, and Kubernetes on Google Cloud VMs.

## 📌 Objective

To build and deploy a machine learning model that predicts whether industrial machines are operating efficiently based on parameters like temperature, power usage, and frequency. The pipeline integrates data processing, model training, containerization, deployment, monitoring, and a user interface.

---

## 🧰 Tech Stack

- **Programming:** Python  
- **ML & Data:** Pandas, Scikit-learn, Jupyter Notebook  
- **API & UI:** Flask, ChatGPT integration  
- **DevOps & MLOps:** Jenkins, ArgoCD, GitHub Actions, Docker, GitOps  
- **Cloud & Infra:** Google Cloud VM, Kubernetes, Minikube  
- **Monitoring:** Prometheus, Grafana  

---

## 📁 Project Structure

```bash
.
├── artifacts/               # Stored model artifacts
├── manifests/               # Kubernetes deployment manifests
├── notebook/                # EDA, model training, and testing notebooks
├── pipeline/                # Custom pipeline scripts for automation
├── src/                     # Core source code and utilities
├── static/                  # Static files for web UI
├── templates/               # HTML templates for the Flask app
├── application.py           # Flask app for user interaction
├── Dockerfile               # Containerization config
├── Jenkinsfile              # CI/CD pipeline definition
├── requirements.txt         # Python dependencies
├── setup.py                 # Packaging script
└── README.md                # You're here
