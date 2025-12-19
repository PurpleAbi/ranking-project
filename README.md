# 🎬 Movies & Series Reviews — Fullstack Project

My personal movies and series reviews website.

Built with Java, React, Spring Boot, Flyway and MySQL.

---

## Features

- Fetch reviews from the backend
- Year-based filtering
- Clean React UI
- Database migrations handled by Flyway

## BASE DEPENDENCIES

- Frontend:
   - 📦 Node 
   - 📦 NPM
- Backend:
   - 📦 Java JDK (v. >= 17.0.0, <= 21.0.0)
   - 📦 MySQL 

## APIs

The [Open Movie Database API](https://www.omdbapi.com/) is used for retrieving movies & series data.

## INSTALLATION & CONFIGURATION

### Project Structure
- 🗂 client/ → React frontend
- 🗂 server/ → Spring Boot backend (with Flyway + MySQL)

### Instructions
1. Make sure you have all dependencies installed
2. Clone this git repository and navigate to the project repository

#### Backend
1. Navigate to the server directory
2. Create an API KEY for the external API here : <https://www.omdbapi.com/apikey.aspx> (FREE option)\
   2.1. Check your email and retrieve the key
3. Set the `OMDBAPI_KEY` environment variable to the value of your key
4. Database Setup:\
   4.1 Ensure MySQL is running\
   4.2 The default credentials in the `application.properties` file are set to 'root' and 'password'. To use your own credentials set these environment variables: `MYSQL_USERNAME` & `MYSQL_PASSWORD` with your own\
   4.3 Create a new empty database named `ranking_db`
5. Execute the Maven build script: `.\mvnw spring-boot:run` for Windows or `./mvnw spring-boot:run` for *NIXES.

#### Frontend
1. Navigate to the client folder
2. Execute `npm install`
3. Execute `npm run dev`
4. Visit the URL printed in your terminal
