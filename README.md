# 🏕️ Scout Grombalia — Intelligent BI System

> A full-stack Business Intelligence & AI platform designed to help the Scout Grombalia center make smarter decisions, save time and energy, and focus on what truly matters: **coaching and guiding their groups** — instead of manually calculating budgets and collecting member information on paper.

---

## 📌 Overview

The **Scout Grombalia Intelligent BI System** is a capstone project developed by students of the **CCCA4 program at ESPRIT**, combining Data Engineering, Business Intelligence, Machine Learning, and MLOps into a single production-ready platform.

The system transforms raw scout center operational data into actionable insights — automating reporting, forecasting membership trends, detecting anomalies, and providing field managers with an intuitive web interface.

---

## 🚀 Key Features

- 📊 **Interactive Power BI Dashboards** — real-time KPIs on membership, activities, budgets, and attendance
- 🔄 **Automated ETL Pipelines** — data ingestion and transformation via Talend
- 🧠 **Machine Learning Models** — membership & participation forecasting + anomaly detection
- 📈 **Time Series Forecasting** — predict enrollment and activity trends over time
- ⚙️ **MLOps Orchestration** — Apache Airflow schedules and automates ML pipelines
- 🧪 **MLflow** — experiment tracking, model versioning, and model registry
- 📡 **Grafana** — live model performance and system monitoring dashboards
- 🌐 **Full-Stack Web Application** — Angular frontend + Flask REST API backend

---

## 🏗️ Architecture

```
Raw Data Sources
      │
      ▼
 Talend ETL Pipelines
      │
      ▼
 Star-Schema Data Warehouse
      │
      ├──► Power BI Dashboards
      │
      └──► ML & Forecasting Models
                │
                ├──► MLflow (tracking & registry)
                ├──► Grafana (monitoring)
                └──► Airflow (orchestration)
                          │
                          ▼
               Angular + Flask Web App
                 (Scout Center Managers)
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| ETL | Talend |
| Data Warehouse | Star Schema (SQL) |
| Dashboards | Power BI |
| ML / Forecasting | Python, Scikit-learn, SARIMA |
| MLOps Orchestration | Apache Airflow |
| Experiment Tracking | MLflow |
| Monitoring | Grafana |
| Backend API | Flask (Python) |
| Frontend | Angular (TypeScript) |

---

## 👥 Team

| Name | Role |
|---|---|
| Youssef | BI & Data Science Lead |
| Anis Saidi | Developer |
| Med Amin Brahmi | Developer |
| Iheb Kh | Developer |
| Amira Youssef | Developer |

---

## 🎓 Supervision

Developed under the guidance of:

- **Manel Khamassi** — Project Supervisor
- **Lilia GOSSA** — Project Supervisor

---

## 🏫 Academic Context

**Institution:** ESPRIT — École Supérieure Privée d'Ingénierie et de Technologies
**Program:** CCCA4 — Business Intelligence & Data Science
**Project Type:** Capstone / PI-CDIO Project
**Year:** 2025–2026

---

## 📄 License

This project was developed for academic purposes at ESPRIT. All rights reserved by the project team.
