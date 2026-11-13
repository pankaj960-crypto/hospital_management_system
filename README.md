# 🏥 Hospital Management System

### A Full-Stack Web Application | Python | Flask | PostgreSQL | Docker

A comprehensive web-based management application developed using Python and Flask. The system provides centralized administrative management, structured data handling, user authentication, and efficient management of application operations through an integrated Admin Dashboard.

🌐 **Live Demo:** https://hospital-management-system-s6i3.onrender.com/

---

## 📌 Project Overview

The Hospital Management System is designed to simplify and organize management operations through a centralized web-based platform.

The application includes an Admin Dashboard that allows administrators to manage tokens, add and manage student records, handle job applications, and control different application operations from a single interface.

The backend is developed using Python and Flask, with PostgreSQL for database management. Docker is used for application containerization, making deployment and environment management easier.

The primary goal is to reduce manual administrative work, improve data organization, and provide a structured platform for managing application activities.

---

## 🎯 Project Objectives

- Centralize administrative operations.
- Simplify student and user management.
- Manage and monitor application tokens.
- Organize and process job applications.
- Provide secure authentication and access control.
- Maintain structured data using PostgreSQL.
- Develop a maintainable and deployment-ready backend application.

---

## ✨ Key Features

### 👨‍💼 1. Admin Dashboard

A centralized dashboard that provides administrators with control over the application's major operations.

- Centralized administrative interface.
- Manage different application modules.
- Monitor and manage application records.
- Access administrative functionality.
- Control authorized management operations.

### 🔑 2. Token Management

- Manage application tokens.
- Handle token-related administrative operations.
- Maintain organized token information.
- Support application access management.

### 🎓 3. Student Management

- Add new student records.
- Manage student information.
- View and update student details.
- Maintain organized student records.

### 💼 4. Job Application Management

- Handle job application records.
- View and manage submitted applications.
- Organize application information.
- Support administrative application processing.

### 🔐 5. Authentication & Authorization

- User authentication.
- Secure access to application resources.
- Role-Based Access Control (RBAC), where implemented.
- Protected administrative functionality.
- Token-based authentication, where implemented.

### 🗄️ 6. Database Management

- PostgreSQL database integration.
- Structured data storage.
- Create, Read, Update, and Delete (CRUD) operations.
- Efficient data retrieval and management.

### 🔌 7. Backend & REST API

- Flask-based backend architecture.
- REST API development.
- Request and response handling.
- Backend business logic.
- Database integration.

### 🐳 8. Docker Support

- Application containerization.
- Consistent application environment.
- Simplified deployment workflow.
- Improved portability across environments.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend Programming |
| Flask | Backend Web Framework |
| PostgreSQL | Relational Database |
| REST APIs | Backend Communication |
| HTML5 | Web Page Structure |
| CSS3 | Styling |
| JavaScript | Frontend Interactivity |
| JWT / Sessions | Authentication (as implemented) |
| Docker | Containerization |
| Git & GitHub | Version Control |
| Render | Cloud Deployment |

---

## 🏗️ Application Architecture

The application follows a structured backend architecture.

**Application Workflow:**

1. **User Interface:** Users interact with the web application.
2. **Authentication:** User credentials and access permissions are validated.
3. **Flask Backend:** Processes incoming requests and executes business logic.
4. **Admin Module:** Handles administrative operations, token management, student records, and job applications.
5. **Database Layer:** PostgreSQL stores and retrieves application data.
6. **Deployment:** Docker supports containerization, and Render hosts the application.

---

## 📂 Project Modules

| Module | Description |
|---|---|
| Admin Dashboard | Centralized administrative control |
| Token Management | Token-related administrative operations |
| Student Management | Add and manage student records |
| Job Applications | Handle and manage applications |
| Authentication | User authentication and access |
| Database | Structured data management |
| Backend APIs | Application logic and data operations |

---

## ⚙️ Installation & Setup

Follow these instructions to run the project locally.

### Prerequisites

- Python 3.x
- PostgreSQL
- Git
- Docker (optional)

### 1. Clone the Repository

```bash
git clone https://github.com/pankaj960-crypto/hospital_management_system.git
```

```bash
cd hospital_management_system
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and configure the required environment variables.

Example:

```env
DATABASE_URL=your_postgresql_connection_string
SECRET_KEY=your_secret_key
```

Use the actual environment variable names required by the application.

### 5. Run the Application

If `app.py` is the application entry point:

```bash
python app.py
```

Open the local application URL configured by Flask in your browser.

---

## 🐳 Docker Setup

Build the Docker image:

```bash
docker build -t hospital-management-system .
```

Run the container:

```bash
docker run --env-file .env -p 5000:5000 hospital-management-system
```

Ensure the container port matches the application's configured port and PostgreSQL is accessible.

---

## 🚀 Live Deployment

The application is deployed using Render.

**Live Application:**

https://hospital-management-system-s6i3.onrender.com/

---

## 💡 Technical Skills Demonstrated

Through this project, I gained practical experience in:

- Python backend development.
- Flask application development.
- PostgreSQL database integration.
- REST API development and integration.
- Authentication and authorization.
- CRUD operations.
- Admin dashboard development.
- Data management and database operations.
- Docker containerization.
- Git and GitHub version control.
- Cloud application deployment.
- Debugging and troubleshooting real-world application issues.

---

## 🔮 Future Enhancements

- Advanced analytics and reporting dashboard.
- Improved application monitoring.
- Enhanced role-based permissions.
- Automated notifications.
- Additional administrative modules.
- Performance and security improvements.

---

## 👨‍💻 Developer

**Pankaj Kumar**

Python Backend Developer | Full-Stack Developer

- GitHub: https://github.com/pankaj960-crypto
- Project: Hospital Management System

---

⭐ If you find this project interesting, feel free to explore the repository and the live application.

**Developed with Python, Flask, PostgreSQL, and Docker.**
