# Community Service Volunteer Tracking System (CSVTS)

A full-stack volunteer management system built with Java, Spring Boot, and PostgreSQL to help NGOs efficiently manage volunteers, assign tasks, track service hours, and generate insightful reports.

---

## 🚀 Key Features

- **Volunteer Management**: Registration, profile updates, and task tracking
- **Role-Based Access**: Separate dashboards for Administrators and Volunteers
- **Automated Logging**: Tracks volunteer hours and generates engagement reports
- **Smart Filtering & Search**: Quickly find volunteers or tasks
- **Responsive UI**: Built with Thymeleaf, HTML, CSS, and JavaScript

---

## 🛠 Tech Stack

| Layer        | Technologies                               |
|--------------|--------------------------------------------|
| Backend      | Java, Spring Boot, Spring Data JPA         |
| Frontend     | Thymeleaf, HTML, CSS, JavaScript           |
| Database     | PostgreSQL                                 |
| Build        | Maven                                      |
| Version Ctrl | Git & GitHub                               |

---

## ⚙️ Setup & Installation

### Prerequisites
- Java 17+
- Maven
- PostgreSQL (create a database named `csvts`)

### Steps
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/csvts.git
Configure application.properties with your PostgreSQL credentials.

Build and run:

bash
mvn spring-boot:run
Access the app at http://localhost:8080

## 📸 Screenshots (Final Results)
Below are screenshots of the live application, demonstrating the core workflows.

## 🔐 Authentication
Login Page	Registration	Forgot Password
https://images/Screenshot%25202025-10-14%2520190311.png	https://images/Screenshot%25202025-10-14%2520190330.png	https://images/Screenshot%25202025-10-14%2520190715.png
## 🖥️ Admin Dashboard
The admin dashboard provides an overview of system statistics and quick access to management functions.

Dashboard (v1)	Dashboard (v2)	Dashboard (v3)	Dashboard (v4)
https://images/Screenshot%25202025-10-06%2520204644.png	https://images/Screenshot%25202025-10-09%2520140303.png	https://images/Screenshot%25202025-10-09%2520181439.png	https://images/Screenshot%25202025-10-14%2520190401.png
📋 Task Management (Admin)
Admins can create, view, edit, assign, and delete tasks.

Create Task	Task Created	Task List (2 tasks)
https://images/Screenshot%25202025-10-07%2520135243.png	https://images/Screenshot%25202025-10-07%2520135654.png	https://images/Screenshot%25202025-10-07%2520140014.png
Task Assignment	Task Updated	Full Task List
https://images/Screenshot%25202025-10-07%2520140130.png	https://images/Screenshot%25202025-10-07%2520144656.png	https://images/Screenshot%25202025-10-14%2520190437.png
## 👤 Volunteer Dashboard
Volunteers see their assigned tasks, progress, and personal profile.

Dashboard (v1)	Dashboard (v2)	Dashboard (v3)
https://images/Screenshot%25202025-10-07%2520231136.png	https://images/Screenshot%25202025-10-08%2520142111.png	https://images/Screenshot%25202025-10-08%2520183428.png
Dashboard (v4 - Completed)	Task In Progress
https://images/Screenshot%25202025-10-14%2520191159.png	https://images/Screenshot%25202025-10-09%2520181301.png
## 📝 Volunteer Tasks, Profile & Time Logs
Completed Tasks	Edit Profile	Time Logs
https://images/Screenshot%25202025-10-14%2520191220.png	https://images/Screenshot%25202025-10-14%2520191240.png	https://images/Screenshot%25202025-10-14%2520191258.png
## 👥 Volunteer Management (Admin)
Admins can view and manage all registered volunteers.

Volunteers List (v1)	Volunteers List (v2)
https://images/Screenshot%25202025-10-14%2520190507.png	https://images/Screenshot%25202025-10-14%2520113617.png
## ⏱️ Time Tracking & Approvals
Volunteers log hours; admins approve or reject them.

Pending Approvals (with entry)	Pending Approvals (empty)
https://images/Screenshot%25202025-10-14%2520113529.png	https://images/Screenshot%25202025-10-14%2520190653.png
Volunteer Time Logs
https://images/Screenshot%25202025-10-14%2520124830.png
## 📊 Reports & Analytics
Generate reports on volunteer hours and task completion.

Reports Dashboard	Hours Report (4.00 hrs)	Hours Report (11.00 hrs)
https://images/Screenshot%25202025-10-14%2520190550.png	https://images/Screenshot%25202025-10-14%2520113719.png	https://images/Screenshot%25202025-10-14%2520190630.png
Task Completion Report (single)	Task Completion Report (full)
https://images/Screenshot%25202025-10-14%2520113654.png	https://images/Screenshot%25202025-10-14%2520190609.png
## 📌 Project Highlights
Designed & implemented the database schema for efficient volunteer/task tracking

Developed full CRUD functionality with Spring Boot for seamless backend operations

Built a responsive and user-friendly frontend with Thymeleaf and vanilla JavaScript

Applied professional development practices: version control (GitHub), issue tracking, and modular code structure

## 🏆 Outcome
This system allows NGOs to manage volunteers efficiently, save administrative time, and track volunteer engagement with actionable insights.

