# FUTURE_FS_02 – Client Lead Management System (Mini CRM)

A full-stack Mini CRM application built with **React, Node.js, Express, and MySQL** to streamline client lead management. The system provides lead tracking, Kanban-based workflow management, analytics dashboards, AI-powered insights, and secure admin authentication.

## Features

* Lead Management (Create, Read, Update, Delete)
* Lead Status Tracking (New, Contacted, Converted)
* Drag-and-Drop Kanban Board
* Analytics Dashboard with Visual Reports
* AI-Powered Lead Insights using Claude AI
* Secure Admin Authentication with JWT
* Notes and Follow-Up Management
* Responsive User Interface

## Tech Stack

### Frontend

* React (Vite)
* Tailwind CSS
* Lucide React
* Recharts
* @hello-pangea/dnd

### Backend

* Node.js
* Express.js
* MySQL
* bcryptjs
* JSON Web Token (JWT)

## Project Structure

text
FUTURE_FS_02/
├── client/     # React Frontend
├── server/     # Node.js & Express Backend
└── README.md


## Installation & Setup

### Prerequisites

* Node.js
* MySQL Server

### Database Configuration

Create a MySQL database:
sql
CREATE DATABASE crm_db;

### Backend Setup
bash
cd server
npm install


Create a `.env` file inside the server directory:

env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=crm_db
JWT_SECRET=your_secret_key


Run the backend server:

bash
node server.js

### Frontend Setup

bash
cd client
npm install
npm run dev


## Application Access

* Frontend: http://localhost:5173
* Backend API: http://localhost:5000

## Screenshots

Add screenshots of:

* Dashboard
* Lead Management Page
* Kanban Board
* Analytics Page
* Login Page

## Skills Demonstrated

* Full-Stack Web Development
* REST API Development
* Database Design & Management
* Authentication & Authorization
* State Management
* Data Visualization
* AI Integration
* CRUD Operations

## Internship Task Information

**Internship:** Future Interns – Full Stack Web Development

**Task 02:** Client Lead Management System (Mini CRM)

Repository Name: FUTURE_FS_02

## Author

Aryan Sharma
SRM Institute of Science and Technology
B.Tech CSE
