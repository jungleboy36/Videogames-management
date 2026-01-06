# 🎮 Videogames Management

A full-stack videogame management system built with microservices architecture.

This project demonstrates how to build and structure a scalable app using modern tools:
- Angular frontend
- Spring Boot backend services
- API gateway and service registry

---

## 🧩 Architecture Overview

### 🖥 Frontend: `jeux_angular`
An Angular application that provides:
- Game list view
- Add / edit / delete videogames
- User interactions with backend APIs

### 🔧 Backend Services
- **`jeux_springboot-main`** – main videogame service (CRUD operations)
- **`users_microservice`** – handles user accounts and possibly authentication
- **`service-registry`** – service discovery (e.g., Eureka)
- **`api-gateway`** – routes frontend requests to the correct backend service

This setup follows a microservices pattern.

---

## 🚀 Key Functionalities

- 🎯 View videogame list
- ✏️ Add and edit videogame entries
- 🗑️ Delete videogame entries
- 🔐 User service (for accounts)
- 📡 Gateway routing to backend APIs

> ⚠️ This project may require multiple services running and specific configs.  
> Runtime environment may not work out of the box — kept for *code reference and architecture understanding*.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Angular (TypeScript, HTML, CSS) |
| Backend | Spring Boot (Java) |
| API Routing | API Gateway (Spring Cloud / Zuul / similar) |
| Discovery | Service registry |

---

## 📌 Status

Archived educational project showing:
- Microservices architecture
- REST API design
- Angular frontend integration

Not guaranteed to run as-is due to outdated configs and missing environment setup.

---

## 📚 What this shows about you

This is NOT just a CRUD UI — it demonstrates:
- Architecting a distributed system
- Working with frontend + backend + services
- Understanding of RESTful APIs
