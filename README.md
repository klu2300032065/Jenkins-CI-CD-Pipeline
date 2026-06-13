# 🚀 Jenkins CI/CD Pipeline using GitHub & Maven

## 📌 Project Overview

This project demonstrates a Continuous Integration (CI) pipeline using **Jenkins**, **GitHub**, and **Apache Maven**. Whenever code is pushed to GitHub, Jenkins fetches the latest source code, builds the project, executes tests, and packages the application automatically.

---

## 🛠️ Tech Stack

- Jenkins
- Git & GitHub
- Apache Maven
- Java
- Ubuntu 24.04
- Pipeline as Code (Jenkinsfile)

---

## 📂 Project Structure

```
Jenkins-CI-CD-Pipeline/
│
├── src/
│   ├── main/
│   └── test/
│
├── pom.xml
├── Jenkinsfile
├── README.md
└── .gitignore
```

---

## ⚙️ CI/CD Workflow

```
Developer
     │
     ▼
Push Code to GitHub
     │
     ▼
Jenkins Pipeline Trigger
     │
     ▼
Checkout Source Code
     │
     ▼
Maven Build
     │
     ▼
Run Tests
     │
     ▼
Package JAR
     │
     ▼
Build Successful
```

---

## 🔹 Pipeline Stages

- Checkout Source Code
- Build Project using Maven
- Execute Unit Tests
- Package Application
- Display Build Status

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/klu2300032065/Jenkins-CI-CD-Pipeline.git
```

### Navigate

```bash
cd Jenkins-CI-CD-Pipeline
```

### Build

```bash
mvn clean package
```

### Run Tests

```bash
mvn test
```

---

## 📸 Screenshots

Add screenshots of:
## Jenkins Build Success
<img width="2856" height="1562" alt="Screenshot 2026-06-13 132440" src="https://github.com/user-attachments/assets/5a55f947-8ae3-497b-9aeb-62077db27320" />

## Pipeline Execution Steps
<img width="2574" height="1538" alt="Screenshot 2026-06-13 132513" src="https://github.com/user-attachments/assets/aa5af0f5-cd18-4774-91ef-e13a7c16648f" />

## Console Output
<img width="2826" height="1568" alt="Screenshot 2026-06-13 132607" src="https://github.com/user-attachments/assets/4ddf298f-6ba4-405d-bc0a-99343e328e06" />


## 📈 Features

- Automated Build Process
- Continuous Integration
- Maven Build Automation
- Jenkins Pipeline as Code
- GitHub Integration
- Easy Deployment Ready

---

## 🎯 Future Enhancements

- Docker Integration
- Docker Hub Push
- Kubernetes Deployment
- AWS EC2 Deployment
- GitHub Webhooks
- SonarQube Code Analysis
- Email Notifications

---

## 👨‍💻 Author

**Charan Sai**

GitHub: https://github.com/klu2300032065

---

## ⭐ If you like this project, don't forget to Star the repository!
