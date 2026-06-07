Distributed Home Automation Platform

Overview

A self-hosted distributed system for home automation and environmental monitoring.

This project is designed as a learning-focused production-like system, combining:

* Linux server administration
* Docker-based service deployment
* MQTT-based distributed communication
* Observability (monitoring & logging)
* Basic edge computing concepts
* DevOps practices

The goal is not just to build services, but to understand how distributed systems are structured, deployed, and maintained in real-world environments.

⸻

Core Objectives

* Build and operate a Linux-based home server environment
* Understand containerization using Docker
* Design a simple distributed system using MQTT (Pub/Sub model)
* Collect and process sensor data from multiple edge nodes
* Implement monitoring and logging infrastructure
* Practice system debugging and incident handling
* Document system architecture and decisions

⸻

System Architecture

High-Level Design

Edge Devices (Simulated / ESP32 later)
        ↓
    MQTT Broker
        ↓
  Backend Services
        ↓
 Database + Processing Layer
        ↓
 Observability Stack
 (Grafana / Prometheus / Logs)

⸻

Components

Edge Layer

* Sensor nodes (initially simulated, later ESP32)
* Publishes environmental data (temperature, humidity, etc.)

Messaging Layer

* MQTT Broker (Mosquitto)
* Decouples sensors from backend systems

Backend Layer

* Data ingestion service (Python)
* Processes and stores sensor data

Data Layer

* PostgreSQL or SQLite (initial phase)

Observability Layer

* Grafana dashboards
* Prometheus metrics
* Logging system (Loki optional)

⸻

Tech Stack

* Ubuntu Server (or Docker environment on Mac)
* Docker & Docker Compose
* MQTT (Mosquitto)
* Python (FastAPI or simple scripts)
* PostgreSQL / SQLite
* Grafana / Prometheus (later phase)

⸻

Project Status

Sprint 0 — Foundation

* Project initialization
* Architecture design refinement
* Docker environment setup

⸻

Sprint 1 — Messaging Layer (MQTT Core)

* Set up MQTT broker using Docker
* Create simple sensor data simulator
* Test publish/subscribe flow

⸻

Sprint 2 — Backend Ingestion

* Python subscriber service
* Store incoming data
* Basic logging

⸻

Sprint 3 — Data Storage

* Database integration
* Data schema design

⸻

Sprint 4 — Observability

* Grafana dashboard
* Metrics visualization

⸻

Sprint 5 — Edge Upgrade

* ESP32 integration
* Real sensor data ingestion

⸻

Sprint 6 — System Expansion

* Multi-node simulation
* Failure handling tests
* Alert system

⸻

Key Learning Outcomes

By completing this project, I aim to understand:

* How distributed systems communicate (Pub/Sub model)
* How containerized services interact
* How real-world IoT systems are structured
* How monitoring and observability are implemented
* How production-like systems are operated and debugged

⸻

Philosophy

This project prioritizes:

Understanding system design over feature complexity
Iterative learning over perfect architecture
Hands-on experimentation over theoretical study