# EduTrack – Student Management System

## About the Project
EduTrack is a web-based Student Management System developed using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). It is designed to simplify student information management and provide an organized platform for handling academic records and administrative activities.

## Features
- Student registration and login
- User-friendly dashboard
- Add, update, view, and delete student records
- Manage student information
- Organized data storage
- Responsive user interface
- Backend API integration
- MongoDB database connectivity

## Technologies Used

**Frontend:**
- React.js
- HTML
- CSS
- JavaScript

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB

## Project Structure

```text
EduTrack/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── package.json
└── README.md
```

*Note: The structure above is illustrative. Adjust it to match your actual project.*

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project

```bash
cd EduTrack
```

### 3. Install Backend Dependencies

```bash
cd backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 5. Start the Backend Server

```bash
npm start
```

### 6. Install Frontend Dependencies

Open another terminal:

```bash
cd frontend
npm install
```

### 7. Start the Frontend

```bash
npm start
```

## How to Run

After starting both servers, open your browser and visit the frontend URL shown in the terminal (commonly `http://localhost:3000`).

## Project Objective

The main objective of EduTrack is to make student information management easier, faster, and more organized through a centralized digital platform.

## Future Enhancements
- Attendance tracking
- Examination and result management
- Student performance reports
- Notifications and announcements
- Role-based access control

## Author

Developed as an academic project to demonstrate full-stack web development using the MERN technology stack.
