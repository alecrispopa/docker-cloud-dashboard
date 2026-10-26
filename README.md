# Cloud Dashboard - Docker Compose Architecture

A complete showcase project demonstrating multi-container orchestration using **Docker Compose**, **Nginx**, and **PostgreSQL**.

---

## 🏗️ Stack Architecture

- **Web Server:** Nginx (Alpine Linux) mapped to host port `8080`.
- **Database:** PostgreSQL 15 (Alpine Linux) with persistent storage via named volumes.
- **Volumes:** `date_postgres` dedicated to database data persistence.
- **Networking:** Isolated default bridge network provisioned automatically by Docker Compose.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/alecrispopa/portofoliu-docker.git](https://github.com/alecrispopa/portofoliu-docker.git)
cd portofoliu-docker