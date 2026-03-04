# Student Attendance Analysis

## Overview

**Student Attendance Analysis** is a web-based attendance management and analytics system designed to efficiently track, manage, analyze, and predict student attendance.

The application is built using **HTML, CSS, JavaScript, and Python (PyScript)** and runs entirely in the browser using LocalStorage for data storage.

It provides role-based access for **Admin, Teacher, and Students**, along with visual dashboards and predictive attendance analysis.

---

## Features

### Home Page

* Introduction to the system
* Role-based login selection

### Role-Based Authentication

* Admin Login
* Teacher Login
* Student Login

---

### Teacher Dashboard

* Mark attendance (Present/Absent)
* Select subject and date
* Mark all students as Present or Absent
* Submit attendance records
* View attendance summaries

---

### Admin Panel

* View overall attendance statistics
* Monitor student records
* Analyze performance trends
* Access system-wide analytics

---

### Student Portal

* View personal attendance percentage
* Check subject-wise attendance
* Track attendance history
* View performance insights

---

### Attendance Analytics

* Line charts for attendance trends
* Bar charts for subject comparison
* Doughnut charts for attendance distribution
* Future attendance prediction using Moving Average method

---

## Data Storage

* Uses **Browser LocalStorage**
* JSON-based structured format
* No external database required
* Data persists even after page refresh

---

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Data Visualization

* Chart.js

### Analytics Engine

* Python (PyScript)
* Pandas
* NumPy

### Storage

* Browser LocalStorage

---

## Project Structure

```
Project-root/

│
├── Student_Attendance_Analysis.html   # Main application file
├── style.css                          # Styling file
├── script.js                          # Core JavaScript logic
├── analytics.py                       # Python analytics module
├── assets/                            # Images and icons (if any)
├── screenshots/                       # Project screenshots
└── README.md                          # Project documentation
```

---

## Core Modules

### Authentication Module

* handleLogin()
* logout()
* Role-based dashboard rendering

### Attendance Module

* markAttendance()
* markAllPresent()
* markAllAbsent()
* submitAttendance()

### Analytics Module

* Chart generation
* Data filtering
* Attendance percentage calculation

### Prediction Module (Python)

* AttendanceAnalyzer class
* Moving average calculation
* Future attendance prediction
* JavaScript–Python bridge function

---

## How to Run the Project

1. Clone the repository:

   ```
   git clone <repository-link>
   ```

2. Open the project folder.

3. Open `Student_Attendance_Analysis.html` in a modern web browser.

4. Ensure internet connection for:

   * PyScript CDN
   * Chart.js CDN

No backend server setup is required.

---

## Login Credentials (Sample)

### Teacher

* Username: teacher
* Password: teacher123

### Admin

* Username: admin
* Password: admin123

### Student

* Username: Student ID (e.g., S001)
* Password: student123

---

## Screenshots

Add screenshots such as:

* Login Page

  <img width="840" height="433" alt="image" src="https://github.com/user-attachments/assets/ece631df-3ebe-4266-a098-4453ff4e9473" />

* Teacher Dashboard
* Admin Panel
* Student Dashboard
* Attendance Charts
* Prediction Output

---

## Testing

You can test the system by:

* Logging in with different roles
* Marking attendance for multiple subjects
* Refreshing the browser to verify LocalStorage persistence
* Checking prediction results in analytics section

---

## Project Highlights

* Role-based access control
* Client-side data storage
* Interactive dashboards
* Visual data representation
* Python integration inside browser
* Basic predictive analytics using Moving Average
* Modular and structured code design

---

## Future Enhancements

* Database integration (MySQL/Firebase)
* Export attendance reports (PDF/Excel)
* Email notifications for low attendance
* Advanced ML-based prediction model
* Cloud deployment

---

## Author

Developed as an academic project for demonstrating attendance management and analytics using modern web technologies.

