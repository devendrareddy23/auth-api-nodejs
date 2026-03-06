# Auth API (Node.js + MongoDB Atlas)

Production-style authentication backend built with Node.js, Express, MongoDB Atlas, JWT, and bcrypt.

## Features
- User registration
- Password hashing with bcrypt
- User login
- JWT token generation
- Protected profile route
- MongoDB Atlas integration

## Tech Stack
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- bcryptjs
- jsonwebtoken
- dotenv

## API Endpoints

### Register
POST `/api/auth/register`

### Login
POST `/api/auth/login`

### Profile
GET `/api/auth/profile`

Requires:
`Authorization: Bearer <token>`

## Run locally

```bash
npm install
npm run dev
