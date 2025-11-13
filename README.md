<h1 align="center">🐳 Inception</h1>

<p align="center">
  <i>A fully containerized infrastructure built using Docker for secure and modular system architecture.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Inception-blue.svg" />
  <img src="https://img.shields.io/badge/Subject-DevOps-yellowgreen.svg" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg" />
</p>

---

## 📌 Project Overview

**Inception** is a DevOps project from the 42 curriculum that focuses on deploying a secure, containerized infrastructure using **Docker**. The project aims to provide hands-on experience in system administration, container orchestration, and service management by building a multi-service architecture from scratch.

---

## 🧱 Architecture Overview

The infrastructure includes:

- **Nginx**: Reverse proxy with SSL (TLS) support  
- **WordPress**: CMS platform for content delivery  
- **MariaDB**: Relational database management   

All services are:

- Isolated in their own Docker containers  
- Defined using individual Dockerfiles (no `docker-compose` at mandatory level)  
- Connected through a dedicated Docker network  
- Automatically restarted on failure  

---

## 🛠️ Tools & Technologies

- Docker (build, network, volumes)  
- Dockerfiles  
- Bash scripting  
- SSL Certificate generation with OpenSSL  
- System hardening practices  
- Service configuration (WordPress, Nginx, MariaDB)

---
