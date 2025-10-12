# 🍽️ Online Food Ordering System – DevOps Project

This project is a complete, production-ready online food ordering platform built using  Express.js, Node.js with a static frontend (HTML/CSS/JS). It supports user and admin features like browsing menus, placing orders, and managing listings. What sets this project apart is its end-to-end DevOps integration—the app is fully Dockerized, uses GitHub Actions for continuous integration and deployment (CI/CD), and is hosted on a live AWS EC2 instance using Docker Compose, simulating a real-world deployment pipeline used by tech companies.


---

## ✨ Features

- 👥 User Registration and Login  
- 🍕 Browse & Search Food Items  
- 🛒 Add to Cart and Place Orders  
- 🛠 Admin Panel for Managing Orders & Menu  
- 📦 MongoDB for Data Storage  
- 🌐 REST APIs with Node.js & Express  
- 💻 Simple and Responsive Frontend  

---

## 🧰 Tech Stack

| Layer      | Technology                            |
|------------|----------------------------------------|
| Frontend   | HTML, CSS, JavaScript                  |
| Backend    | Node.js, Express.js                    |
| Database   | MongoDB (Dockerized)                   |
| Container  | Docker, Docker Compose                 |
| DevOps     | GitHub Actions, Docker Hub, AWS EC2    |

---

## ⚙️ CI/CD Pipeline

- ✅ Code pushed to `main` triggers **GitHub Actions**
- 🐳 Docker image is built and pushed to **Docker Hub**
- ☁️ SSH into AWS EC2 to pull latest image and run with **Docker Compose**
- 🔁 Fully automated deployment

---

## ⚙️ CI/CD Workflow

### 🔄 GitHub Actions:
- On every push to `main`, GitHub Actions:
  - 🛠 Builds Docker image
  - 📦 Pushes it to Docker Hub
  - 🔐 SSHs into AWS EC2 instance
  - ⬇️ Pulls the latest image and restarts containers using Docker Compose

### 🐳 Docker Compose:
- Manages both the Node.js backend and MongoDB as services
- Ensures smooth multi-container deployment

### ☁️ AWS EC2:
- Acts as the production server
- Hosts the application behind Docker

---

## 🧠 Learning & Purpose

This project was developed to demonstrate practical **DevOps implementation** in a real-world application. It combines:

- 🌐 Web development skills (frontend + backend)
- 🔁 DevOps automation (CI/CD)
- ☁️ Cloud deployment (AWS)
- 🐳 Docker containerization

---

