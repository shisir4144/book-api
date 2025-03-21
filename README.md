# Book Management API

## Overview

This is a simple Express.js API for managing books and user authentication.
## Features

User Registration & Login (with JWT authentication)

CRUD operations for books

## Installation

Clone the repository:

git clone your-repo-url
cd your-project-folder

Install dependencies:

npm install

Create a .env file and add:

JWT_SECRET=your-secret-key
MONGO_URI=your-mongodb-uri

Start the server:

npm run dev


## API Endpoints

### Authentication

POST /api/auth/register – Register a new user

POST /api/auth/login – Login and receive a JWT token

### Books

POST /api/books – Add a new book

GET /api/books – Get all books

GET /api/books/:id – Get a single book by ID

PUT /api/books/:id – Update book details

DELETE /api/books/:id – Delete a book

## Usage

Use tools like Postman or cURL to test the API endpoints.
