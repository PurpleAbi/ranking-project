# 🎬 Movies & Series Reviews — Fullstack Project

A blog-like web app built with **React**, **Spring Boot**, and **MySQL**, where I share my personal reviews of movies and TV series.

---

## 🗂 Project Structure
- `client/` → React frontend
- `server/` → Spring Boot backend (with Flyway + MySQL)

## Running locally
### Backend
1. Make sure you have **Java 17+** and **MySQL** installed.  
2. In `server/src/main/resources/application.properties`, set your local MySQL credentials:
   ```properties
   spring.datasource.username=your_user
   spring.datasource.password=your_password
3. Run the Spring Boot app.

### Frontend
Open the project in VS Code (or your preferred IDE).
In the terminal, make sure you are in the client folder:
1. if you are not then `cd client`
2. `npm install`
3. `npm run dev`
4. Visit the URL printed in your terminal (usually http://localhost:5173).


🧩 Features

Movie and TV series reviews fetched from the backend

Year-based filtering

Clean React UI

Backend built with Java, Spring Boot, and MySQL

Database migrations handled with Flyway


📦 Tech Stack

Frontend: React, JavaScript, CSS

Backend: Java, Spring Boot, Flyway

Database: MySQL
