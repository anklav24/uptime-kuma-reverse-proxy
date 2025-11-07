# Uptime Kuma Deployment with Traefik Reverse Proxy

Docker Compose for deploying [Uptime Kuma](https://github.com/louislam/uptime-kuma) behind a [Traefik](https://doc.traefik.io/traefik/) reverse proxy with automatic HTTPS via Let's Encrypt.

---

## 🌐 Features

- 🕵️‍♂️ Uptime Kuma monitoring system

- 🔐 Automatic HTTPS with Let's Encrypt (HTTP-01 challenge)

- 🛡️ Traefik reverse proxy

- 🔧 Easily configurable via `.env` file

- 📦 Docker Compose based setup

---

## ⚙️ Prerequisites

- Docker and Docker Compose

- A domain with DNS records pointing to your server

- Port 80 and 443 available on your host

---

## 🛠️ Setup Instructions

1. Clone/Download the Repository

2. Configure Environment Variables
   1. Copy `.example.env` to `.env`
   2. Change values in `.env` to yours

3. `docker compose up -d`
