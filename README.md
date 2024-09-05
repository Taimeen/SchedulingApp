

---

# Dynamic User Availability and Event Scheduling System

## Project Overview

The Dynamic User Availability and Event Scheduling System is a full-stack web application that allows users to set their availability dynamically and enables admins to schedule sessions. Built with the MERN stack, it features a React frontend, an Express backend, and a MongoDB database. The application supports one-on-one and multi-participant sessions with a user-friendly interface.

## Features

- **User Availability Capture:** Users can log in, set availability for specific days or the entire week, and manage their availability slots.
- **Admin Scheduling Interface:** Admins can view user availability, schedule sessions, and handle one-on-one or multi-participant sessions.
- **Session Management:** View and manage scheduled sessions, including options to reschedule or cancel.
- **Intuitive UI/UX:** Modern and responsive design using React, Vite, and Bootstrap.

## Technology Stack

- **Frontend:** React, Vite, Bootstrap
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Deployment:** Netlify (Frontend), Render (Backend)

## Setup Instructions

### Frontend

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo/frontend
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Build the Application:**

   ```bash
   npm run build
   ```

4. **Start the Development Server:**

   ```bash
   npm run dev
   ```

   The frontend will be available at `http://localhost:3000`.

### Backend

1. **Navigate to the Backend Directory:**

   ```bash
   cd your-repo/backend
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**

   Create a `.env` file in the `backend` directory with the following content:

   ```plaintext
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. **Start the Development Server:**

   ```bash
   npm run dev
   ```

   The backend will be available at `http://localhost:5000`.

