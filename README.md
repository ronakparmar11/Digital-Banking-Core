# BankGuardian

An enterprise-grade Digital Banking Fraud Detection and Risk Monitoring Platform built using Java Spring Boot, PostgreSQL, FastAPI, Next.js, and Docker.

The platform processes banking transactions in real time, performs rule-based and machine learning fraud detection, and provides investigation workflows, analytics dashboards, notifications, and secure user management.

---

## Features

- Secure JWT Authentication
- Role-Based Access Control (RBAC)
- Banking Transaction APIs
- Real-Time Fraud Detection
- Rule-Based Risk Engine
- Machine Learning Risk Scoring
- Fraud Investigation Workflow
- Customer Risk Monitoring
- Audit Logging
- Notification System
- Analytics Dashboard
- Dockerized Deployment

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

```
Frontend (Next.js)
        │
        ▼
Spring Boot REST APIs
        │
 ┌──────┼────────┐
 │      │        │
 ▼      ▼        ▼
PostgreSQL   Kafka   FastAPI ML Service
```

---

## Project Structure

```
BankGuardian
│
├── src
├── frontend
├── ml-service
├── .mvn
│
├── Dockerfile
├── docker-compose.yml
├── pom.xml
├── README.md
└── mvnw
```

---

## Getting Started

Clone the repository

```bash
git clone https://github.com/ronakparmar11/BankGuardian.git
```

Start the application

```bash
docker compose up --build
```

Backend

```
http://localhost:8080
```

Frontend

```
http://localhost:3000
```

ML Service

```
http://localhost:8000
```

---

## Future Improvements

- Multi-Factor Authentication
- Redis Caching
- Prometheus Monitoring
- Grafana Dashboards
- Kubernetes Deployment

---

## Author

Ronak Parmar

LinkedIn:
https://www.linkedin.com/in/ronak-parmar-75b9422ba/

GitHub:
https://github.com/ronakparmar11