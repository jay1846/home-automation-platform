# Sprint 4 — Docker Structure Confusion

## Problem
Multiple containers (dev-server, home-server) caused confusion in system design.

## Cause
Lack of clear role separation between containers.

## Resolution
Designate `home-server` as the main server and remove unused containers.

## Lesson
Each container should have a clear responsibility.
