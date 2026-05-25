# Sprint 4 — Docker Structure Confusion

## Problem
Multiple containers (dev-server, home-server) caused confusion in system design.

## Cause
Lack of clear role separation between containers.

## Resolution
Designate `home-server` as the main server and remove unused containers.

## Lesson
Each container should have a clear responsibility.


## Sprint 4 Complete — Single Server Setup

### What exists now
- Ubuntu container (home-server)
- SSH access (port 2222)
- Nginx web server (port 8080)

### Key learning
- Port mapping
- Container as a server
- Internal vs external networking

### Current state
A single container acting as a mini cloud server.
