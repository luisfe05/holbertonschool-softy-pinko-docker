# Softy Pinko Docker

## Description
This project builds up a small multi-container web infrastructure with Docker: a Flask back-end API, an Nginx-served static front-end, and an Nginx reverse-proxy/load-balancer in front of both, orchestrated with Docker Compose.

## Tasks

| Task | Description | Directory |
| :--- | :--- | :--- |
| **0. Create Your First Docker Image** | A `Dockerfile` based on `ubuntu:latest` that updates/upgrades APT and echoes `Hello, World!`. | `task0` |
| **1. Back-end** | A Flask API (`api.py`) with a `/api/hello` route, containerized on port 5252. | `task1` |
| **2. Front-end** | Nginx-served static front-end (cloned `softy-pinko-front-end` site) on port 9000; back-end moved into its own `back-end/` folder. | `task2` |

## Author
* **Luis Gonzalez** - Holberton School
