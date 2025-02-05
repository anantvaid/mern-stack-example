# Dockerized MERN Stack Application

This project demonstrates how to containerize a MERN (MongoDB, Express.js, React, Node.js) stack application using Docker and Docker Compose. It follows a three-tier architecture, ensuring separation between the frontend, backend, and database.

## 🛠 Project Setup

This project is forked from [MongoDB's demo project](https://github.com/mongodb-developer/mern-stack-example)

## 🚀 How to Use
### 1️⃣ Prerequisites

Ensure you have the following installed:

- Docker
- Docker Compose

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/anantvaid/mern-stack-example
cd mern-stack-example
```

### 3️⃣ Build and Start the Containers

Run the following command to build and start all services:

```bash
docker compose up --build -d
```

This will:<br/>
✅ Start the React frontend <br/>
✅ Start the Node.js backend <br/>
✅ Start the MongoDB database

### 4️⃣ Access the Application

- Frontend (React App): `http://localhost`
- Backend (Express API): `http://localhost:5050`
- MongoDB (Database): Connected internally via Docker network

### 5️⃣ Stop and Remove Containers

To stop all services:

```bash
docker-compose down
```

To remove containers including database volumes:

```bash
docker-compose down -v
```

## 📖 Blog Post

For a detailed explanation of how this project was Dockerized, check out the blog post:<br/>
👉 [How to Dockerize Your MERN Stack: A Developer's Guide](https://techtalkswithanant.hashnode.dev/how-to-dockerize-your-mern-stack-a-developers-guide)
