# FUTURE_FS_02 - Full-Stack Mini CRM

A full-stack Mini CRM built with React, Node.js, Express, and MySQL. It features lead management, a Kanban board, analytics, AI insights (using Anthropic's Claude), and admin authentication.

## Tech Stack
* **Frontend**: React (Vite), Tailwind CSS, Lucide React, Recharts, @hello-pangea/dnd (for drag-and-drop Kanban)
* **Backend**: Node.js, Express, MySQL, bcryptjs, jsonwebtoken (JWT for authentication)

## Project Structure
* `/client` - React frontend
* `/server` - Node.js & Express backend

## Getting Started

### Prerequisites
* Node.js
* MySQL Server (running locally)

### Database Setup
1. Create a MySQL database named `crm_db` (or as configured in your `.env`).
2. The server will automatically initialize the necessary tables when started.

### Backend Setup
1. Navigate to the `server` directory:
   ```bash
   cd server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure your environment variables in `server/.env`:
   ```env
   PORT=5000
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=your_mysql_password
   DB_NAME=crm_db
   JWT_SECRET=supersecretjwtkey_replace_me_in_production
   ```
4. Start the server:
   ```bash
   node server.js
   ```

### Frontend Setup
1. Open a new terminal and navigate to the `client` directory:
   ```bash
   cd client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure your AI API key in `client/.env.local`:
   ```env
   VITE_ANTHROPIC_API_KEY=your_anthropic_api_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

### Access the Application
* The frontend app runs at `http://localhost:5173` (or the port shown by Vite).
* The backend API runs on `http://localhost:5000`.
