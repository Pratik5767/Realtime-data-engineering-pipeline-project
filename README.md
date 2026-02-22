# 🚀 Real-Time Data Engineering Pipeline

## 📌 Project Overview
This project implements an end-to-end real-time data engineering pipeline using Kafka, Spark, Airflow, Docker, PostgreSQL, and Cassandra. The system is designed to ingest, process, orchestrate, and store streaming data in a scalable and containerized environment.

The architecture demonstrates modern data engineering practices including distributed processing, workflow scheduling, and multi-database storage.

---

## 🏗️ Architecture Overview

Data Flow:

Producer → Kafka → Spark Streaming → PostgreSQL / Cassandra  
                      ↓  
                   Airflow (Orchestration)

- **Kafka** handles real-time data ingestion.
- **Spark Streaming** processes and transforms streaming data.
- **Airflow** orchestrates and schedules workflows.
- **PostgreSQL** stores structured relational data.
- **Cassandra** stores scalable distributed data.
- **Docker Compose** containerizes all services for seamless deployment.

---

## 🛠️ Technologies Used

- Apache Kafka
- Apache Spark (Structured Streaming)
- Apache Airflow
- PostgreSQL
- Cassandra
- Docker & Docker Compose
- Python

---

## ⚙️ Key Features

- Real-time data ingestion using Kafka
- Distributed stream processing with Spark
- Workflow orchestration with Airflow DAGs
- Dual storage strategy (Relational + NoSQL)
- Fully containerized microservices architecture
- Scalable and modular system design

---

## 📂 Project Structure

```
project-root/
│
├── dags/                  # Airflow DAG definitions
├── spark_jobs/            # Spark streaming scripts
├── producer/              # Kafka producer scripts
├── docker-compose.yml     # Container orchestration
├── requirements.txt
└── README.md
```

---

## 🚀 Setup & Execution

### 1️⃣ Clone Repository
```bash
git clone <your-repository-url>
cd <project-folder>
```

### 2️⃣ Start Services
```bash
docker-compose up --build
```

### 3️⃣ Access Services
- Kafka: localhost:9092
- Airflow UI: http://localhost:8080
- PostgreSQL: localhost:5432
- Cassandra: localhost:9042

### 4️⃣ Run Pipeline
- Trigger Airflow DAG
- Start Kafka producer
- Spark streaming job processes incoming data

---

## 📊 System Capabilities

- Handles real-time streaming data
- Supports horizontal scalability
- Ensures workflow reliability with scheduling
- Demonstrates batch + streaming integration
- Implements distributed storage strategy

---

## 📈 Learning Outcomes

- Building real-time streaming architectures
- Integrating Kafka with Spark
- Workflow orchestration using Airflow
- Working with relational and NoSQL databases
- Containerized deployment using Docker Compose

---

## 🔮 Future Enhancements

- Add monitoring using Prometheus & Grafana
- Implement data validation layer
- Add CI/CD pipeline integration
- Deploy to cloud (AWS/GCP/Azure)

---

## 👨‍💻 Author
Pratik Vishwas Salunkhe

---

## ⭐ If you found this project useful
Consider giving it a star ⭐ and connecting with me on LinkedIn!