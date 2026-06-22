# 🚗 Vehicle Insurance MLOps Pipeline

An end-to-end MLOps project for Vehicle Insurance Prediction that demonstrates the complete machine learning lifecycle—from data ingestion and validation to model deployment and CI/CD automation using AWS, Docker, GitHub Actions, and MongoDB Atlas.

## 📌 Project Overview

This project showcases industry-standard MLOps practices for building, deploying, and maintaining machine learning systems in production.

### Key Features

* End-to-End Machine Learning Pipeline
* MongoDB Atlas Data Storage
* Automated Data Validation & Transformation
* Model Training & Evaluation
* AWS S3 Model Versioning
* REST API Deployment
* Docker Containerization
* CI/CD using GitHub Actions
* AWS EC2 & ECR Deployment
* Modular and Scalable Architecture
* Logging & Exception Handling

---

## 🏗️ Architecture

```text
MongoDB Atlas
      │
      ▼
Data Ingestion
      │
      ▼
Data Validation
      │
      ▼
Data Transformation
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
AWS S3 Model Registry
      │
      ▼
Prediction Pipeline
      │
      ▼
Flask API
      │
      ▼
Docker Container
      │
      ▼
AWS EC2 Deployment
```

---

## 🛠️ Tech Stack

### Programming

* Python 3.10

### Database

* MongoDB Atlas

### Cloud Services

* AWS S3
* AWS EC2
* AWS ECR
* IAM

### MLOps Tools

* Docker
* GitHub Actions
* CI/CD Pipeline

### Machine Learning

* Scikit-Learn
* Pandas
* NumPy

### Web Framework

* Flask

---

## 📂 Project Structure

```text
Vehicle-Insurance-MLOps/
│
├── artifacts/
├── config/
├── notebook/
├── src/
│   ├── components/
│   ├── configuration/
│   ├── entity/
│   ├── pipeline/
│   ├── utils/
│   └── aws_storage/
│
├── static/
├── templates/
├── app.py
├── requirements.txt
├── setup.py
├── pyproject.toml
├── Dockerfile
└── .github/workflows/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/vehicle-insurance-mlops.git

cd vehicle-insurance-mlops
```

### Create Environment

```bash
conda create -n vehicle python=3.10 -y

conda activate vehicle
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🗄️ MongoDB Configuration

Create a MongoDB Atlas cluster and configure the connection string.

```bash
export MONGODB_URL="mongodb+srv://username:password@cluster.mongodb.net/"
```

Windows PowerShell:

```powershell
$env:MONGODB_URL="mongodb+srv://username:password@cluster.mongodb.net/"
```

---

## ☁️ AWS Configuration

Configure AWS credentials:

```bash
export AWS_ACCESS_KEY_ID="YOUR_ACCESS_KEY"

export AWS_SECRET_ACCESS_KEY="YOUR_SECRET_KEY"
```

Create an S3 bucket for storing trained models.

Example:

```text
vehicle-insurance-models
```

---

## 🚀 Running the Pipeline

### Data Ingestion

```bash
python demo.py
```

### Training Pipeline

```bash
python main.py
```

### Run Web Application

```bash
python app.py
```

Application URL:

```text
http://localhost:5080
```

---

## 🐳 Docker Deployment

Build Docker Image:

```bash
docker build -t vehicle-insurance-mlops .
```

Run Container:

```bash
docker run -p 5080:5080 vehicle-insurance-mlops
```

---

## 🔄 CI/CD Workflow

The project uses GitHub Actions to automate:

* Code Build
* Docker Image Creation
* AWS ECR Push
* EC2 Deployment
* Continuous Delivery

### Required GitHub Secrets

```text
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_DEFAULT_REGION
ECR_REPOSITORY
```

---

## 📈 Machine Learning Workflow

1. Data Collection from MongoDB
2. Data Validation
3. Feature Engineering
4. Data Transformation
5. Model Training
6. Model Evaluation
7. Model Versioning
8. Model Deployment
9. Prediction Serving

---

## 🎯 Business Use Case

Insurance companies receive thousands of customer applications daily. This project helps automate risk assessment by predicting whether a customer is likely to be interested in vehicle insurance based on demographic and historical information.

Benefits:

* Faster Decision Making
* Reduced Manual Effort
* Improved Customer Targeting
* Scalable Production Deployment

---

## 📊 Future Improvements

* MLflow Integration
* Kubernetes Deployment
* Monitoring & Alerting
* Drift Detection
* Automated Retraining
* Model Explainability Dashboard

---

## 👨‍💻 Author

Mohit Malviya

B.Tech – Artificial Intelligence & Data Science

Passionate about Machine Learning, MLOps, Data Science, and Cloud Technologies.

### Connect With Me

LinkedIn:
https://www.linkedin.com/in/mohitmalviya-ds

GitHub:
https://github.com/mohitmalviya0707

---

⭐ If you found this project useful, consider giving it a star on GitHub.

