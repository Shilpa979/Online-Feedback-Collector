# Online Feedback Collector with Admin Dashboard

## Internship Project

### Project Overview
The Online Feedback Collector with Admin Dashboard is a full-stack web application developed as part of my internship. The project focuses on collecting user feedback through an online form, storing it in a database, and presenting meaningful insights through an admin dashboard.

This project simulates a real-world feedback system used in colleges, organizations, and product review platforms.

---

## Objectives of the Project
- To design a user-friendly feedback collection system
- To understand frontend–backend integration
- To implement server-side logic using Flask
- To perform database operations using SQLite
- To display summarized data for administrative use

---

## Key Features
- Feedback form with validation
- Stores feedback securely in SQLite database
- Admin dashboard to view all feedback
- Displays total feedback count
- Calculates average rating
- Star-based rating display
- Clean and responsive UI using Bootstrap
- Easy navigation between pages

---

## Technologies & Tools Used
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python (Flask Framework)
- **Database:** SQLite
- **Development Tool:** Visual Studio Code
- **Version Control:** Git (optional)

---

## System Architecture
User submits feedback through the frontend form →  
Flask backend processes POST request →  
Data is stored in SQLite database →  
Admin dashboard retrieves and displays data dynamically.

---

## Project Folder Structure

OnlineFeedbackCollector/
│
├── app.py # Flask backend logic
├── database.db # SQLite database
├── requirements.txt # Python dependencies
│
├── static/
│ ├── css/style.css # Styling
│ └── js/script.js # JavaScript (optional)
│
├── templates/
│ ├── layout.html # Base template
│ ├── index.html # Feedback form
│ └── admin.html # Admin dashboard
│
└── README.md # Project documentation

## How to Run the Project

### Step 1: Create Virtual Environment
### Step 2: Activate Virtual Environment
### Step 3: Install Dependencies
### Step 4: Run the Application

### Step 5: Open in Browser
- Feedback Form:  
  http://127.0.0.1:5000/
- Admin Dashboard:  
  http://127.0.0.1:5000/admin-dashboard

---

## Database Design
**Table Name:** feedback

| Field Name       | Data Type |
|-----------------|----------|
| id              | Integer (Primary Key) |
| name            | Text |
| email           | Text |
| rating          | Integer |
| comments        | Text |
| date_submitted  | Text |

---

## Learning Outcomes
- Hands-on experience with Flask framework
- Understanding of MVC architecture
- Knowledge of form handling and POST requests
- Practical database management using SQLite
- Improved frontend design using Bootstrap
- Experience building real-world web applications

---

## Future Enhancements
- Admin login authentication
- Data visualization using charts (Pie/Bar)
- Export feedback data to CSV
- Email notification system
- Deployment on cloud platforms like Render or PythonAnywhere

---

## Internship Significance
This project helped me gain practical experience in full-stack development and understand how real-world applications handle user input, data storage, and administrative analysis.

---

## Author
**Shilpa Swapnil Thorat**  
B.Tech – Computer Science and Engineering  
Marathwada Institute of Technology  

---

## Conclusion
The Online Feedback Collector is a practical and scalable application demonstrating complete web development workflow. It is suitable for academic use as well as real-world feedback management systems.
