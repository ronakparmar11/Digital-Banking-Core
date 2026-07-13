# Digital Banking Core

An enterprise-grade Digital Banking Fraud Detection and Risk Monitoring Platform built using **Java, Spring Boot, PostgreSQL, FastAPI, Next.js, Kafka, and Docker**.

This platform simulates how modern financial institutions process banking transactions, perform hybrid fraud detection, manage fraud investigations, and monitor customer risk in real time.

---

## Features

- JWT Authentication & Authorization
- Role-Based Access Control (RBAC)
- Banking Transaction Management
- Rule-Based Fraud Detection
- Machine Learning Risk Scoring
- Customer Risk Monitoring
- Fraud Investigation Workflow
- Audit Logging
- Real-Time Notifications
- Analytics Dashboard
- Dockerized Deployment
- RESTful APIs

---

## Tech Stack

### Backend

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Flyway

### Machine Learning

- Python
- FastAPI
- Scikit-Learn

### Frontend

- Next.js
- TypeScript
- Tailwind CSS

### Infrastructure

- Docker
- Docker Compose
- Kafka / Redpanda

---

## Architecture

```text
                    Next.js Frontend
                           │
                           ▼
                Spring Boot REST API
                           │
      ┌────────────────────┼────────────────────┐
      ▼                    ▼                    ▼
 PostgreSQL           Kafka / Redpanda     FastAPI ML Service
```

---

## Project Structure

```text
Digital-Banking-Core
│
├── src/
├── frontend/
├── ml-service/
├── .mvn/
├── Dockerfile
├── docker-compose.yml
├── pom.xml
├── README.md
├── mvnw
└── mvnw.cmd
```

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/ronakparmar11/Digital-Banking-Core.git
```

### Run using Docker

```bash
docker compose up --build
```

### Services

| Service | URL |
|----------|-----|
| Backend API | http://localhost:8080 |
| Frontend | http://localhost:3000 |
| ML Service | http://localhost:8000 |

---

## Future Enhancements

- Multi-Factor Authentication
- Redis Caching
- Kubernetes Deployment
- Prometheus Monitoring
- Grafana Dashboards
- Distributed Tracing

---

## Author

**Ronak Parmar**

LinkedIn: https://www.linkedin.com/in/ronak-parmar-75b9422ba/

GitHub: https://github.com/ronakparmar11