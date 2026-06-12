# Node.js + MongoDB Docker Signup App

A simple full-stack backend project using Node.js, MongoDB, and Docker.  
This project demonstrates REST API development, Docker containerization, and MongoDB integration.

---

## Features

- Add new user (Signup form)
- Fetch all users
- MongoDB database integration
- Dockerized backend + database setup
- REST API architecture

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Docker
- HTML/CSS (frontend)

---

## 📂 Project Structure

nodeapp/
├── server.js
├── index.html
├── Dockerfile
├── docker-compose.yml
├── package.json
├── package-lock.json


---

##  How to Run This Project

## Prerequisites

- Docker
- Docker Compose
- Git

### 1 Clone repository
```bash
git clone https://github.com/Ksingh-pranjal/node-docker-mongo-app.git
cd node-docker-mongo-app
```

### 2 Start with Docker
```bash
docker-compose up --build
```

### 3 Open in browser
http://localhost:3030

---

## API Routes

| Method | Route     | Description   |
| ------ | --------- | ------------- |
| GET    | /getUsers | Get all users |
| POST   | /addUser  | Add new user  |

---

## What I Learned
Docker containerization
Node.js backend development
MongoDB CRUD operations
REST API design
Docker Compose orchestration