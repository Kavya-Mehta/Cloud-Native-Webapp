# AWS Cloud Web Application

## 📌 Project Overview

This repository contains a **cloud‑ready web application** designed to be deployed on **AWS infrastructure provisioned using Terraform**. The project demonstrates end‑to‑end cloud application development, including **CI/CD automation**, secure configuration, and infrastructure–application separation.

The application follows modern backend development practices and integrates seamlessly with AWS services using a scalable and maintainable architecture.

---

## 🎯 Project Objectives

* Build a production‑ready web application
* Deploy the application on AWS cloud infrastructure
* Implement **CI/CD pipelines** for automated build, test, and deployment
* Follow cloud and DevOps best practices
* Maintain clean separation between infrastructure and application code

---

## 🧩 Key Features

* RESTful API design
* Environment‑based configuration
* Automated CI/CD pipeline
* Cloud‑native deployment on AWS EC2
* Secure handling of secrets and credentials
* Integration with Terraform‑provisioned infrastructure

---

## 🏗️ High‑Level Architecture

1. Infrastructure is provisioned using Terraform (VPC, subnets, routing, security groups)
2. Web application is built and tested using CI pipeline
3. Application artifacts are deployed automatically via CD pipeline
4. Application runs on EC2 instances inside a custom AWS VPC
5. Network access is controlled using security groups and routing rules

---

## 📂 Repository Structure

```
aws-cloud-webapp/
│── src/
│   ├── controllers/
│   ├── routes/
│   ├── services/
│   ├── models/
│
│── config/
│── tests/
│── scripts/
│── .github/workflows/   # CI/CD workflows
│── package.json
│── README.md
```

---

## ⚙️ Requirements

Server Operating System: Windows
Programming Language: JavaScript
Relational Database: MySQL
Backend Framework: NodeJS
ORM Framework:Sequelize

---

## 🚀 Local Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/Kavya-Mehta/aws-cloud-webapp.git
cd aws-cloud-webapp
```

### 2️⃣ Install Dependencies

```
npm install
```

### 3️⃣ Environment Configuration

Create a `.env` file with required variables such as:

* Application port
* Database credentials (if applicable)
* AWS‑specific configuration

⚠️ Environment files are **not committed** to version control.

---

## ▶️ Running the Application Locally

```
npm start
```

The application will start on the configured port.

---

## 🔄 CI/CD Pipeline

This project implements **Continuous Integration and Continuous Deployment (CI/CD)** using **GitHub Actions**.

### ✅ Continuous Integration (CI)

* Triggered on pull requests and pushes
* Installs dependencies
* Runs automated tests
* Performs basic validation checks

### 🚀 Continuous Deployment (CD)

* Triggered on merge to the main branch
* Builds the application
* Deploys the latest version to AWS EC2
* Ensures consistent and repeatable deployments

This automation improves reliability, reduces manual effort, and ensures faster delivery.

---

## ☁️ Cloud Deployment Flow

1. Terraform provisions AWS networking and compute resources
2. CI pipeline validates code changes
3. CD pipeline deploys the application to EC2
4. Application becomes accessible via configured endpoints

---

## 🔒 Security Best Practices

* Secrets managed via environment variables
* IAM roles used instead of hard‑coded credentials
* Network isolation using VPC and security groups
* Principle of least privilege followed

---

## 🧠 Learning Outcomes

* Cloud application deployment on AWS
* CI/CD pipeline implementation
* Infrastructure and application separation
* Secure cloud networking fundamentals
* Real‑world DevOps workflow exposure

---

## 👩‍💻 Author

**Kavya Mehta**

---

## 📄 License

This project is intended for academic and learning purposes.
