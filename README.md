# 🛡️ PhishNetAI

PhishNetAI is an AI-powered phishing detection system designed to analyze and classify suspicious network traffic using machine learning. It provides scalable deployment, real-time threat analysis, and seamless integration with AWS infrastructure.

---

## 🚀 Features

- ✅ AI-driven phishing detection
- 🔍 Real-time monitoring and threat classification
- 📦 Docker-based deployment
- ☁️ Integrated with AWS ECR & EC2 for CI/CD
- 📊 MongoDB backend for data persistence
- 📁 Structured logging and data pipeline

---

## 📦 Tech Stack

- **Python 3.8+**
- **Flask** – Web framework
- **Pandas, NumPy, Scikit-learn** – Data handling & ML
- **Docker** – Containerization
- **MongoDB** – NoSQL Database
- **GitHub Actions** – CI/CD
- **AWS EC2 + ECR** – Cloud deployment

---
## Clone the repo 
```bash 
git clone https://github.com/shreyash4145/PhishNetAI.git
cd PhishNetAI
```
## Install Dependencies
```bash 
pip install -r requirements.txt
```


Setup github secrets:
AWS_ACCESS_KEY_ID= "Your key"

AWS_SECRET_ACCESS_KEY= "Your key"

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = "Your URI"
ECR_REPOSITORY_NAME = "Your Repo Name"


Docker Setup In EC2 commands to be Executed
#optinal
```bash
sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh
```

sudo usermod -aG docker ubuntu

newgrp docker
