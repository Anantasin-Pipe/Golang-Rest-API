# Event Management REST API

A lightweight RESTful API built with **Go** and **Gin Framework**. This is my first Go project, developed while following a Web Development with Go course on Udemy to practice building backend services.

## 🚀 Features

- User Authentication & Authorization (Signup / Login)
- Password Hashing with `bcrypt`
- Secure JWT-based Authentication (`golang-jwt`)
- Event Management (CRUD operations for events)
- Relational Database structure with Foreign Keys using SQLite

## 🛠️ Tech Stack

- **Language:** Go (Golang)
- **Framework:** [Gin Web Framework](https://github.com/gin-gonic/gin)
- **Database:** SQLite3 (`https://github.com/mattn/go-sqlite3` CGO-free Pure Go driver)
- **Authentication:** JWT (`https://github.com/golang-jwt/jwt`)

## 🏃 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
2. **Install Dependency:**
   ```bash
   go mod download
3. **Run the application:**
   ```bash
   go run .
The server will start locally on http://localhost:8080.
