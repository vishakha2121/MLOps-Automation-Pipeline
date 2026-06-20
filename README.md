# 🚀 End-to-End MLOps Automation Pipeline

> **Enterprise-grade MLOps solution** with automated training, model versioning, drift detection, and real-time monitoring dashboard.

![MLOps Pipeline](https://img.shields.io/badge/MLOps-Automation-blue)
![Python](https://img.shields.io/badge/Python-3.10+-green)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-teal)
![React](https://img.shields.io/badge/React-18.2+-cyan)
![MLflow](https://img.shields.io/badge/MLflow-2.0+-orange)
![DVC](https://img.shields.io/badge/DVC-2.0+-purple)
![Docker](https://img.shields.io/badge/Docker-24.0+-blue)

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Project Structure](#-project-structure)
- [Quick Start](#-quick-start)
- [Detailed Setup](#-detailed-setup)
- [API Documentation](#-api-documentation)
- [Frontend Dashboard](#-frontend-dashboard)
- [ML Pipeline](#-ml-pipeline)
- [Drift Detection](#-drift-detection)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Overview

This project demonstrates a **complete MLOps pipeline** that automates the entire machine learning lifecycle:

1. **Data Versioning** with DVC
2. **Automated Training** with MLflow tracking
3. **Model Registry** for version management
4. **RESTful API** for real-time predictions
5. **Drift Detection** for monitoring model performance
6. **Interactive Dashboard** for visualization

---

## 🔥 Key Features

| Feature | Description | Status |
|---------|-------------|--------|
| **Data Version Control** | Track and version datasets using DVC | ✅ |
| **Automated Training** | Scheduled retraining pipeline | ✅ |
| **Model Versioning** | MLflow experiment tracking & registry | ✅ |
| **Prediction API** | FastAPI with `/predict` endpoint | ✅ |
| **Drift Detection** | PSI (Population Stability Index) monitoring | ✅ |
| **Monitoring Dashboard** | Real-time React + Tailwind UI | ✅ |
| **Docker Support** | Containerized microservices | ✅ |
| **CI/CD Ready** | GitHub Actions workflow | 🔄 |

---

## 🛠️ Tech Stack

### Backend
```yaml
Framework: FastAPI 0.100+
ML Tracking: MLflow 2.0+
Data Versioning: DVC 2.0+
ML Library: Scikit-learn 1.3+
Database: SQLAlchemy + PostgreSQL/SQLite
Container: Docker 24.0+

Framework: React 18.2+
Build Tool: Vite 4.0+
Styling: Tailwind CSS 3.3+
Charts: Recharts 2.8+
HTTP Client: Axios 1.4+