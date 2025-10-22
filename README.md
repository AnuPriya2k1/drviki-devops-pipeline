# Dr. ViKi DevOps & Security Assignment

## Project Overview
This project demonstrates a complete **DevOps pipeline** for a web application, including containerization, deployment, monitoring, and basic security considerations. The application is deployed using **Railway** and monitored with **UptimeRobot**.

---

## Tools & Technologies Used
- **Docker:** Containerizing the application for consistent environments.  
- **Railway:** Cloud deployment platform for hosting the app.  
- **Git & GitHub:** Version control and source code management.  
- **UptimeRobot:** Monitoring the application uptime.  
- **Trivy / GitHub Dependabot (conceptual):** Security scanning of Docker images and dependencies.

---

## Project Structure
├── app/ # Application code (Python/Flask)
├── Dockerfile # Docker configuration
├── docker-compose.yml # Docker Compose setup
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## Setup & Deployment

### Clone the Repository
```bash
git clone https://github.com/AnuPriya2k1/drviki-devops-pipeline.git
cd drviki-devops-pipeline

Build Docker Image
docker build -t drviki-app .

### Deployment

Deployed on Railway for free-tier cloud hosting.

Public URL is available after deployment.


#### Monitoring

Monitored via UptimeRobot to track uptime and receive alerts.


### Challenges & Learnings

Docker build issues: Resolved dependency and configuration errors in the Dockerfile.

Connectivity issues: DNS resolution problems while cloning the repo.

Monitoring setup: Configured UptimeRobot correctly to ensure accurate uptime checks.

Learned about cost optimization, security best practices, and efficient containerization.


##### Future Improvements

Automate security scans using Trivy or GitHub Actions.

Implement a full CI/CD pipeline for automated deployments.

Optimize Docker images for smaller size and faster builds.












'


