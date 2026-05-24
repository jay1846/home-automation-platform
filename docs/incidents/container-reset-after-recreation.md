# Incident — Configuration lost after container recreation

## Problem

After recreating the Ubuntu container, previously installed software was missing.

## Root Cause

Containers are ephemeral. Changes inside a container do not automatically persist after recreation.

## Resolution

Reinstalled and reconfigured required services.

## Lessons Learned

Containers should ideally be configured through Dockerfiles and reproducible setup steps.
