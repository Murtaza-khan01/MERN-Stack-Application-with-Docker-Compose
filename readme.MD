# MERN Stack with Docker Compose

A **containerized MERN stack application** orchestrated using **Docker Compose**, demonstrating real-world DevOps practices for multi-container applications.

---

## 🚀 What This Project Shows

* Containerization of **Frontend (React)** and **Backend (Node.js / Express)**
* MongoDB running as a separate service
* Multi-container orchestration using **Docker Compose**
* Service-to-service communication via Docker networking
* Persistent database storage using Docker volumes

---

## 🧱 Architecture

```
React (5173) → Node.js API (5050) → MongoDB (27017)
```

Each service runs in its own container and communicates over a shared Docker network.

---

## 📁 Project Structure

```
MERN-docker-compose/
│── docker-compose.yaml
│── README.md
└── mern/
    ├── backend/
    │   ├── Dockerfile
    │   └── server.js
    └── frontend/
        ├── Dockerfile
        └── src/
```

---

## 🐳 Docker Compose Overview

**Services:**

* **frontend** – React app
* **backend** – Node.js / Express API
* **mongodb** – Database with persistent volume

**Key Features:**

* Single command to run the full stack
* Automatic networking between services
* Environment-based configuration
* Clean separation of concerns

---

## ▶️ How to Run

### Prerequisites

* Docker
* Docker Compose

### Start Services

```bash
docker-compose up -d
```

### Stop Services

```bash
docker-compose down
```

---

## 🌐 Access

* Frontend: [http://localhost:5173](http://localhost:5173)
* Backend API: [http://localhost:5050](http://localhost:5050)
* MongoDB: localhost:27017

---

## ✅ Why Docker Compose?

* Simplifies multi-container setups
* Ensures consistent environments
* Handles networking & dependencies automatically
* Improves development and testing workflow

---

## 🛠 Tech Stack

* Docker & Docker Compose
* React
* Node.js / Express
* MongoDB

---

## 🎯 Key Takeaway

This project demonstrates how **modern applications are built, containerized, and orchestrated** in a clean and scalable way — a strong foundation before moving to Kubernetes.

---

✨ *One command. Full MERN stack.*
