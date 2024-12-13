# CRUD Application with React.js and ASP.NET Core

## Description

A full-stack CRUD (Create, Read, Update, Delete) application with a React.js frontend and ASP.NET Core backend, integrated with a MySQL database. The application allows users to manage records with features such as viewing, adding, editing, and deleting data.

## Features

**Backend (ASP.NET Core)**
- RESTful APIs for:
  - Add new user
  - View user details by ID
  - Update user details
  - Delete user
  - List all users

**MySQL database integration.**

**Frontend (React.js)**
- Form:
  - Add or Edit user details.
  - Fields: ID, Name, Address, State, District, Date of Birth, Language.
- Table:
  - Display all users with:
    - View details.
    - Edit and Delete options.
- Responsive design.


## **Technologies Used**
- Frontend: React.js
- Backend: ASP.NET Core, C#
- Database: MySQL

##   Setup Instructions
**Backend**
- Clone the repository.
- Configure the connection string in appsettings.json for MySQL.
- Run the application from Visual Studio.
  
**Frontend**
- Navigate to the frontend folder.
- Install dependencies: npm install.
- Start the application: npm start.

## Endpoints
- GET /api/users - List all users.
- GET /api/users/{id} - View user details by ID.
- POST /api/users - Add new user.
- PUT /api/users/{id} - Update user.
- DELETE /api/users/{id} - Delete user.

## Drive Link
Please find drive link to screen recording
