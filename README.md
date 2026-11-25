# Clear Vision Clinic - Full-Stack Appointment Booking System

## Live Website: https://clear-vision-frontend.vercel.app/
 
## About the Project

Clear Vision Clinic is a full-stack web application designed to make booking eye - care appointments more convenient.

The idea behind this project came from my own experience of having to visit an optometrist in person to arrange an appointment. I wanted to create a platform where patients could browse available doctors, choose their preferred doctor, view appointment slots, and book appointments online from the comfort of their homes.

The application also provides an administrative interface for managing doctors, services, and patient appointments.

## Key Features

- User Authentication: Patient registration, login, email verification, and password management.
- Password Security: Used bcrypt to hash user passwords before storing them in the database
- JWT Authentoication: Implemented JSON Web Tokens to authenticate users and protect restricted backend routes
- Protected Routes: Created authentication middleware to verify tokens stored in HTTP cookies before granting access to protected endpoints
- Doctor Management: Browse doctors and view the profiles
- Appointment Booking: Select a preferred doctor, view available dates and time slots, and book appointments online.
- Appointment Management: Patients can view and manage their appointments
- Admin Dashboard: Administrators can manage doctors, services, and appointments
- Profile Management: Users can view and update their profile information

## Technologies Used

### Frontend

- React.js
- JavaScript
- HTML
- CSS

### Backend

- Node.js
- JSON Web Token (JWT)
- bcrypt

### Database

- TiDB Cloud (MySQL - compatible database)
- MySQL

### Deployment

- Frontend: Vercel
- Backend: Render
- Database: TiDB Cloud

### Important Note About the Live Website

The frontend is hosted on Vercel, while the backend is hosted on Render using its free service.

The backend may become inactive after a period ofinactivity. When accessing the website, please allow a little time for the backend to wake up and respond to the first request.

If the website does not respond immediately, please wait a moment and try again.

What I Learned

### Through this project, I gained practical experience in:

- Building a full-stack web application using React.js and Node.js
- Developing REST API endpoints using Express.js
- Connecting a frontend application to a backend API
- Working with a MySQL-compatible database
- Implementing JWT authentication and protected backed routes
- Securing user passwords using bcrypt hashing
- Managing user authentication and authorization
- Deploying a full-stack application using Vercel, Render, and TiDB Cloud

### Running the Project Locally

## 1. Clone the Repository

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Sthera30/clear-vision-clini-fullstack-app.git
cd clear-vision-clini-fullstack-app
```

### 2️⃣ Set Up the Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder using the `.env.example` file as a template. Add your own environment variables and credentials.

Start the backend:

```bash
npm start
```

### 3️⃣ Set Up the Frontend

Open a second terminal from the project root:

```bash
cd frontend
npm install
npm run dev
```

The frontend will run using the Vite development server.

