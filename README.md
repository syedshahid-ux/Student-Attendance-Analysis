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
 <img width="756" height="430" alt="image" src="https://github.com/user-attachments/assets/6aced4d1-a910-4f63-b74d-83a103624932" />


* Admin Panel
  Admin Dashboard
<img width="814" height="431" alt="image" src="https://github.com/user-attachments/assets/ab896e2a-5be4-46a2-a4fe-d7aab9a7f568" />

*Admin Can Check student attendance status 
<img width="732" height="426" alt="image" src="https://github.com/user-attachments/assets/fb15d8ae-c4ba-4741-a763-d70ffd361cf1" />

*Admin can Manage students
<img width="725" height="430" alt="image" src="https://github.com/user-attachments/assets/94e542d5-533f-44af-8d82-1c1d9541f9df" />

*Admmin can edit student attendance
<img width="749" height="422" alt="image" src="https://github.com/user-attachments/assets/30e091da-a793-4c11-929a-b995308ea17f" />

* Student Dashboard
  <img width="717" height="431" alt="image" src="https://github.com/user-attachments/assets/d9cfff75-09ad-42d2-bb9c-48b868fb98f3" />
  
* Attendance Charts
  7-Day Attendance Trend
  <img width="298" height="135" alt="image" src="https://github.com/user-attachments/assets/ca99e089-ea9d-4f8d-baab-d902dee6df42" />

*Class Distribution
<img width="298" height="135" alt="image" src="https://github.com/user-attachments/assets/e85a23f9-935a-4e03-b851-488fc5655aaa" />

*Subject Performance
<img width="298" height="135" alt="image" src="https://github.com/user-attachments/assets/e557103e-fa44-41d6-af14-bf69c885375c" />
  
* Prediction Output
  
  <img width="798" height="425" alt="image" src="https://github.com/user-attachments/assets/39d5a16e-845f-4e6b-9525-3f69d3cb8d69" />


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

Developed as an internship project for demonstrating attendance management and analytics using modern web technologies.

