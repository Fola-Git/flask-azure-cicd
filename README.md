# 🌐 Flask App Deployment with Azure and GitHub Actions

This project demonstrates a simple, colorful Python Flask web application deployed to **Azure App Service** using **GitHub Actions for CI/CD**.

## 📌 Project Overview

This repository contains:
- A **Flask** app (`app.py`)
- A simple, **colorful HTML page** with Flask templating
- A `.github/workflows` directory containing the **GitHub Actions workflow** for deploying to Azure Web App

---

## ⚙️ Tech Stack

- Python 3.13
- Flask
- HTML/CSS
- Azure App Service
- GitHub Actions (CI/CD)

---

## 🛠 How It Works

1. Push code to GitHub → GitHub Actions triggers
2. Workflow builds and deploys Flask app to Azure Web App
3. Application auto-updates on each push to `master` branch

---

## 📂 File Structure

```bash
.
├── app.py
├── requirements.txt
├── templates
│   └── index.html
├── static
│   └── styles.css
└── .github
    └── workflows
        └── python-app.yml
