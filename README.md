# Blog Platform Backend (Node.js + Express + MongoDB)

A RESTful backend for a multi-user blogging platform.

## Features
- User registration and login (JWT Authentication)
- Password hashing using bcrypt
- Create, edit, delete blog posts
- Comment system
- Protected routes using middleware
- Pagination for posts

## Tech Stack
Node.js, Express.js, MongoDB, Mongoose, JWT, Bcrypt

## Installation

1. Clone repository
git clone <repo-link>

2. Install dependencies
npm install

3. Create .env file

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key

4. Run server
npm start
