# 🧬 Skin Cancer Detection using Deep Learning and MLOps

This project aims to detect skin cancer from images using a Convolutional Neural Network (CNN) based on **DenseNet201**. It integrates a full-stack web application (Django frontend & backend), a CI/CD pipeline, containerization with Docker and Kubernetes, and monitoring/logging with the ELK stack. It also utilizes **DAGsHub** and **MLflow** for experiment tracking and model management.

---

## 🚀 Features

- **Deep Learning Model**: Skin cancer classifier built using CNN with **DenseNet201**.
- **Web Application**:
  - Django-based frontend and backend.
  - Secure login and image upload functionality.
- **CI/CD Pipeline**:
  - Automated steps to build, test, and deploy the application locally.
- **Containerization & Orchestration**:
  - Docker used for containerizing the app.
  - Kubernetes used for orchestrating multiple services.
- **Monitoring & Logging**:
  - **ELK Stack (Elasticsearch, Logstash, Kibana)** for real-time monitoring and log analysis.
- **MLOps Tools**:
  - **MLflow** for experiment tracking and model lifecycle management.
  - **DAGsHub** for data versioning and collaboration.

---

## 🛠️ Tech Stack

| Component            | Technology                     |
|---------------------|---------------------------------|
| Model               | TensorFlow / Keras, DenseNet201 |
| Backend             | Django                          |
| Frontend            | HTML, CSS, Django Templates     |
| CI/CD               | GitHub|
| Containerization    | Docker                          |
| Orchestration       | Kubernetes                      |
| Monitoring/Logging  | ELK Stack (Elasticsearch, Logstash, Kibana) |
| Experiment Tracking | MLflow, DAGsHub                 |

---

## 📦 Setup Instructions

### Prerequisites

- Python 3.8+
- Docker
- Kubernetes (Minikube or other)
- Git
- MLflow & DAGsHub accounts (optional but recommended)

