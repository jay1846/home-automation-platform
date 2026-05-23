# Home Automation Platform

## Overview

A self-hosted cloud platform for personal automation, monitoring, and infrastructure experimentation.

The goal of this project is to build a production-like environment at home while learning Linux, Docker, monitoring, observability, and DevOps practices.

---

## Objectives
- Build and manage a Linux server

- Containerize services using Docker

- Create a monitoring stack

- Configure alert systems

- Practice incident handling

- Document the complete process

---

## Planned Architecture

User Devices

↓

Reverse Proxy

↓

Services

- Nextcloud

- Dashboard

- APIs

↓

Monitoring

- Prometheus

- Grafana

- Loki

↓

Alerting

- Telegram

---

## Tech Stack

- Ubuntu Server

- Docker

- Nginx

- Prometheus

- Grafana

- Loki

- Nextcloud

---

## Project Status

Current Sprint:

Sprint 0 — Project initialization

Progress:

[ ] Linux setup

[ ] Docker environment

[ ] Dashboard

[ ] Monitoring

[ ] Logging

[ ] Alerting

[ ] Automation

## Sprint 1 - Docker Server Setup

- Created Ubuntu container as home server
- Installed SSH server inside container
- Created non-root user (jay)
- Enabled basic server tooling

### Architecture

Mac → Docker → Ubuntu Server Container
