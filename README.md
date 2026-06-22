# todo_fastapi_project
A FastAPI-based Todo Management REST API with MySQL database, JWT authentication, and user-specific CRUD operations.
A Todo Management REST API built using FastAPI, SQLModel, and MySQL.

## Features

- User Registration
- User Login
- JWT Authentication
- Password Hashing
- Create Todo
- View Todo
- Update Todo
- Delete Todo
- User-based authorization

## Technologies Used

- Python
- FastAPI
- SQLModel
- MySQL
- JWT
- Uvicorn

## Setup

Clone the repository

Install dependencies:

pip install -r requirements.txt

Create .env file:

DB_USERNAME=root
DB_PASSWORD=your_password

Run server:

uvicorn main:app --reload

Open:

http://127.0.0.1:8000/docs

## API Flow

Signup → Login → Get Token → Use Protected APIs
