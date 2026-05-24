# Incident — Nginx installed but not running

## Problem

Nginx was successfully installed but requests to localhost failed.

## Symptoms

- nginx is not running
- curl localhost returned connection refused

## Root Cause

Installing a package does not always start the service automatically in container environments.

## Resolution

Started Nginx manually:

sudo service nginx start

## Lessons Learned

Installation and execution are separate processes.
Containers behave differently from full virtual machines.
