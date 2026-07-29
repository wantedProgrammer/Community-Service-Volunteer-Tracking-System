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

| Login Page | Registration | Forgot Password |
|------------|--------------|-----------------|
| ![Login](https://raw.githubusercontent.com/wantedProgrammer/Community-Service-Volunteer-Tracking-System/main/csvts/images/Screenshot%202025-10-06%20184443.png) | ![Register](https://raw.githubusercontent.com/wantedProgrammer/Community-Service-Volunteer-Tracking-System/main/csvts/images/Screenshot%202025-10-06%20195423.png) | ![Forgot Password](https://raw.githubusercontent.com/wantedProgrammer/Community-Service-Volunteer-Tracking-System/main/csvts/images/Screenshot%202025-10-14%20190715.png) |

### 🖥️ Admin Dashboard
The admin dashboard provides an overview of system statistics and quick access to management functions.

| Dashboard (v1) | Dashboard (v2) | Dashboard (v3) | Dashboard (v4) |
|----------------|----------------|----------------|----------------|
| ![Admin v1](csvts/images/Screenshot%202025-10-06%20204644.png) | ![Admin v2](csvts/images/Screenshot%202025-10-09%20140303.png) | ![Admin v3](csvts/images/Screenshot%202025-10-09%20181439.png) | ![Admin v4](csvts/images/Screenshot%202025-10-14%20190401.png) |

### 📋 Task Management (Admin)
Admins can create, view, edit, assign, and delete tasks.

| Create Task | Task Created | Task List (2 tasks) |
|-------------|--------------|---------------------|
| ![Create Task](csvts/images/Screenshot%202025-10-07%20135243.png) | ![Task Created](csvts/images/Screenshot%202025-10-07%20135654.png) | ![Task List](csvts/images/Screenshot%202025-10-07%20140014.png) |

### 👤 Volunteer Dashboard
Volunteers see their assigned tasks, progress, and personal profile.

| Dashboard (v1) | Dashboard (v2) | Dashboard (v3) |
|----------------|----------------|----------------|
| ![Vol Dashboard 1](csvts/images/Screenshot%202025-10-07%20231136.png) | ![Vol Dashboard 2](csvts/images/Screenshot%202025-10-08%20142111.png) | ![Vol Dashboard 3](csvts/images/Screenshot%202025-10-08%20183428.png) |

| Dashboard (v4 - Completed) | Task In Progress |
|----------------------------|------------------|
| ![Vol Dashboard 4](csvts/images/Screenshot%202025-10-14%20191159.png) | ![In Progress](csvts/images/Screenshot%202025-10-09%20181301.png) |

### 📝 Volunteer Tasks, Profile & Time Logs

| Completed Tasks | Edit Profile | Time Logs |
|-----------------|--------------|-----------|
| ![Completed Tasks](csvts/images/Screenshot%202025-10-14%20191220.png) | ![Profile](csvts/images/Screenshot%202025-10-14%20191240.png) | ![Time Logs](csvts/images/Screenshot%202025-10-14%20191258.png) |

### 👥 Volunteer Management (Admin)
Admins can view and manage all registered volunteers.

| Volunteers List (v1) | Volunteers List (v2) |
|----------------------|----------------------|
| ![Volunteers 1](csvts/images/Screenshot%202025-10-14%20190507.png) | ![Volunteers 2](csvts/images/Screenshot%202025-10-14%20113617.png) |

### ⏱️ Time Tracking & Approvals
Volunteers log hours; admins approve or reject them.

| Pending Approvals (with entry) | Pending Approvals (empty) |
|-------------------------------|---------------------------|
| ![Pending](https://raw.githubusercontent.com/wantedProgrammer/Community-Service-Volunteer-Tracking-System/main/csvts/images/Screenshot%202025-10-14%20113529.png) | ![Empty Pending](https://raw.githubusercontent.com/wantedProgrammer/Community-Service-Volunteer-Tracking-System/main/csvts/images/Screenshot%202025-10-14%20190653.png) |

| Volunteer Time Logs |
|---------------------|
| ![Time Logs](https://raw.githubusercontent.com/wantedProgrammer/Community-Service-Volunteer-Tracking-System/main/csvts/images/Screenshot%202025-10-14%20124830.png) |

### 📊 Reports & Analytics
Generate reports on volunteer hours and task completion.

| Reports Dashboard | Hours Report (4.00 hrs) | Hours Report (11.00 hrs) |
|-------------------|--------------------------|---------------------------|
| ![Reports](csvts/images/Screenshot%202025-10-14%20190550.png) | ![Hours 4](csvts/images/Screenshot%202025-10-14%20113719.png) | ![Hours 11](csvts/images/Screenshot%202025-10-14%20190630.png) |

| Task Completion Report (single) | Task Completion Report (full) |
|---------------------------------|-------------------------------|
| ![Completion Single](csvts/images/Screenshot%202025-10-14%20113654.png) | ![Completion Full](csvts/images/Screenshot%202025-10-14%20190609.png) |

## 📌 Project Highlights
Designed & implemented the database schema for efficient volunteer/task tracking

Developed full CRUD functionality with Spring Boot for seamless backend operations

Built a responsive and user-friendly frontend with Thymeleaf and vanilla JavaScript

Applied professional development practices: version control (GitHub), issue tracking, and modular code structure

## 🏆 Outcome
This system allows NGOs to manage volunteers efficiently, save administrative time, and track volunteer engagement with actionable insights.

