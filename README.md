# Mern_Mini_EMS

> A minimal MERN Employee Management System (Vite + React frontend, Express/Mongoose backend). Designed for learning and small demos; deployable to Vercel.

## Features
- Create, read, update and delete employee records
- Simple React + Vite frontend with Tailwind styling
- Express backend using Mongoose for MongoDB
- Deploy-ready with Vercel configuration

## Tech Stack
- Frontend: React, Vite, Tailwind CSS
- Backend: Node.js, Express, Mongoose
- Database: MongoDB (Atlas or local)

## Project Structure

- backend/ — Express API, Mongoose models, Vercel config
  - server.js — Express app and DB connection
  - APIs/EmployeeAPI.js — CRUD routes for employees
  - models/EmployeeModel.js — Mongoose schema for employees
  - .env — environment variables for DB and port
- frontend/ — Vite + React app
  - src/ — React components and app entry
  - .env — `VITE_URL` points to the backend base URL

## Prerequisites
- Node.js
- MongoDB (Atlas connection string or local instance)

## API Endpoints

Base path: `/employee-api`

- GET `/employee-api/employee` — list all employees
- POST `/employee-api/employee` — create a new employee (JSON body)
- PUT `/employee-api/employee/:id` — update employee by ID
- DELETE `/employee-api/employee/:id` — delete employee by ID
