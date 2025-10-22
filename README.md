# Dr. ViKi DevOps & Security Assignment

This project demonstrates a simple CI/CD pipeline using **GitHub Actions**, **Docker**, and **Railway** deployment.

## 🚀 Features
- Python Flask web app displaying a timestamp
- Dockerized container
- CI/CD using GitHub Actions
- Railway cloud deployment
- Monitoring with UptimeRobot
- Security scan with Trivy

## 🧩 Setup
1. Clone this repo
2. Build locally:
   ```bash
   docker build -t drviki-app .
   docker run -p 8080:8080 drviki-app
   ```
3. Push to GitHub
4. Connect Railway → "Deploy from GitHub Repo"
5. Add `RAILWAY_TOKEN` in GitHub Secrets

## 📸 Screenshots to capture
1. GitHub Actions workflow success
2. Live app on Railway
3. Monitoring dashboard (UptimeRobot)
4. Docker container running
5. Trivy scan report
