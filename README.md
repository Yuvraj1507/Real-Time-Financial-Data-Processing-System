# Cloud-Native Banking Application

## 📌 Project Overview
The **Cloud-Native Banking Application** is a scalable, microservices-based financial platform designed for secure real-time transaction processing. It integrates authentication, event-driven architecture, and monitoring to ensure high availability and performance.

## ✨ Features
- 🔐 **Secure Authentication**: OAuth2 & OpenID Connect for user authentication.
- 📊 **Real-Time Data Processing**: Event-driven architecture using Kafka & RabbitMQ.
- 🚀 **Scalable Microservices**: Built with Spring Boot & deployed on Kubernetes.
- 🔄 **High Availability**: Auto-scaling and self-healing via Kubernetes & Docker.
- 📡 **Observability**: Integrated monitoring with Prometheus, Grafana, and Loki.

## 🏗️ Architecture Diagram
![Architecture Diagram](./images/architecture.png)

## 🛠️ Tech Stack
- **Backend**: Java, Spring Boot, Spring Cloud
- **Messaging**: Kafka, RabbitMQ
- **Database**: PostgreSQL, Redis
- **Containerization**: Docker, Kubernetes, Helm
- **Authentication**: OAuth2, OpenID Connect (Keycloak)
- **Monitoring**: Prometheus, Grafana, Loki
- **CI/CD**: GitHub Actions
- **Cloud**: AWS (EKS, S3, RDS)

## 📂 Project Structure
```
📦 cloud-native-banking
├── 📂 backend
│   ├── 📂 auth-service
│   ├── 📂 transaction-service
│   ├── 📂 notification-service
│   └── 📂 api-gateway
├── 📂 frontend
│   ├── 📂 react-ui
├── 📂 deployment
│   ├── 📜 docker-compose.yml
│   ├── 📜 k8s-deployment.yaml
│   ├── 📜 helm-chart/
└── 📜 README.md
```

## 🚀 Installation & Setup
### Prerequisites
- Java 17+, Docker, Kubernetes, Helm, PostgreSQL, Kafka

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/cloud-native-banking.git
   cd cloud-native-banking
   ```
2. Start services with Docker Compose:
   ```bash
   docker-compose up -d
   ```
3. Deploy on Kubernetes:
   ```bash
   kubectl apply -f deployment/k8s-deployment.yaml
   ```
4. Access the UI at `http://localhost:3000`

## 🖥️ API Documentation
| Endpoint               | Method | Description                 |
|------------------------|--------|-----------------------------|
| `/api/auth/login`      | POST   | User login                  |
| `/api/transactions`    | GET    | Get transaction history     |
| `/api/transactions`    | POST   | Create a new transaction    |
| `/api/notifications`   | GET    | Fetch notifications         |

## 📊 Monitoring Dashboard (Grafana)
![Grafana Dashboard](./images/grafana_dashboard.png)

## ☁️ Deployment Guide
- **Local Deployment**: Docker Compose
- **Production Deployment**: Kubernetes (EKS, Helm Charts)

## 🎯 Future Enhancements
- ✅ AI-based fraud detection
- ✅ Multi-region deployment

## 🤝 Contributing
Fork the repo, create a feature branch, and submit a PR.

---
Made with ❤️ by [Dalayi Yuvaraju]

