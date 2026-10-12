# Raspberry Pi Homelab

A modular, Docker-based home server infrastructure.

This repository manages services using a Infrastructure as Code (IaC) principles

## Services

- Pihole
- Wireguard

## Quick Start

### 1. Prerequisites:

- Docker 

### 2. Clone the repo:

```bash
git clone https://github.com/101KiddChang010/rspi-homelab.git
```

### 3. Fill out confidential local configurations
Create an `.env` based on [.env.example](./.env.example) and fill in the required configurations

### 4. Deploy Docker Containerss

Run the services in the background

```bash
docker compose up -d
```