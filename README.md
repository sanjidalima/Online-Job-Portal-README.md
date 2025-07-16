# Online-Job-Portal-README.md

# Online Job Portal  
*A Web-Based Application for Modern Recruitment*

The **Online Job Portal** is a fully functional web application developed using PHP and MySQL. It enables seamless interaction between employers and job seekers by offering a platform for job postings, applications, and candidate management.

---

## Team Members
- Sanjida Khanom  
- Priya Das  
- Maymuna  

---

## Live Demo  
**URL:** *(To be added after deployment)*

---

## Tech Stack

| Technology   | Purpose                              |
|--------------|---------------------------------------|
| HTML5, CSS3  | Frontend structure and styling        |
| Bootstrap    | Responsive design and UI components   |
| JavaScript   | Client-side interactivity             |
| PHP          | Server-side scripting and logic       |
| MySQL        | Database management                   |
| XAMPP        | Local development environment         |

---

## Core Features

### Admin Panel
- Admin authentication
- Employer and job seeker account management
- Job category and company profile management
- Full control over job listings
- View and moderate applications

### Employer Panel
- Company profile management
- Job creation, editing, and listing control
- View applicant profiles and application status
- Basic message system for communication

### Job Seeker Panel
- User registration and profile setup
- Search and filter job postings
- Apply for jobs directly from portal
- Track application status
- View and manage personal documents

---

## Modules Breakdown

### Admin Module
| Feature              | Description                                      |
|----------------------|--------------------------------------------------|
| Login                | Secure admin authentication                     |
| Manage Users         | Add/edit/delete employers and job seekers       |
| Job Category         | Manage job types and categories                 |
| Monitor Jobs         | View posted jobs and remove inappropriate ones  |
| Application Overview | Review applicant data across postings           |

### Employer Module
| Feature           | Description                                      |
|-------------------|--------------------------------------------------|
| Authentication    | Login/logout functionality                       |
| Job Management    | Create, update, delete jobs                      |
| Application View  | Access applicants’ details per job listing       |
| Company Profile   | Update company description and contact info      |

### Job Seeker Module
| Feature            | Description                                      |
|--------------------|--------------------------------------------------|
| Registration/Login | Create an account or access existing profile     |
| Job Search         | Search and filter available job listings         |
| Apply for Jobs     | Submit application with CV/cover letter          |
| Application Status | Track the progress of job applications           |
| Profile Management | Update personal and professional details         |

---

## Database Structure (Simplified)

- **users** — (id, username, email, password, role)  
- **jobs** — (id, title, description, company_id, location)  
- **applications** — (id, job_id, user_id, status)  
- **companies** — (id, name, description, contact)  
- **categories** — (id, name, description)  

---

## Installation Instructions

### Prerequisites
- Install **XAMPP**
- A code editor like **VS Code**, **Sublime Text**, or **Notepad++**

### Steps
1. Download or clone the project repository  
2. Extract and move the `jobportal` folder to `C:/xampp/htdocs/`  
3. Start **Apache** and **MySQL** via XAMPP Control Panel  
4. Open **phpMyAdmin** at `http://localhost/phpmyadmin`  
5. Create a new database named `db_jobportal`  
6. Import `db_jobportal.sql` from the SQL file directory  
7. Run the application via browser: `http://localhost/jobportal`

---

## Sample Login Credentials

| Role     | Username         | Password  |
|----------|------------------|-----------|
| Admin    | admin            | admin     |

> Use the interface to register new employers or job seekers as needed.

---

## Key Accomplishments
- Responsive design using Bootstrap  
- Efficient database-driven search and filter system  
- Secure user authentication and session handling  
- Real-time job application tracking  
- Modular design following MVC pattern  

---

## Challenges Faced
- Ensuring database scalability with optimized queries  
- Implementing secure session management and file uploads  
- Maintaining responsiveness across all screen sizes  
- Preventing unauthorized access via role-based validation  

---

## Future Enhancements
- AI-based job and candidate matching  
- Integration of video interviews  
- Real-time messaging/chat module  
- Resume parsing for faster application filtering  
- Mobile application for Android  
- Admin analytics dashboard with advanced filters  

---

## License
This project is open-source and available under the **MIT License**.

> Contributions, improvements, and feedback are welcome.
