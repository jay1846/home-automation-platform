# Day 02 — Docker-based Linux Server Setup

## Goal

Create a Linux server environment using Docker and enable remote access through SSH.

## Tasks Completed

- Created Ubuntu container
- Installed OpenSSH server
- Created non-root user
- Configured SSH service
- Connected from host machine via SSH

## Architecture

Mac Host
    ↓
Docker Engine
    ↓
Ubuntu Container
    ↓
SSH Server

## Result

SSH connection from local machine to container succeeded.

## Lessons Learned

- Docker containers can simulate server environments.
- SSH enables secure remote administration.
- Port mapping connects host ports to container ports.
