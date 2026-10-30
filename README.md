<div align="center">

# place. — Smart Placement Portal

### A centralized platform to discover placement opportunities and manage the student placement journey.

![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Functionality-F7DF1E?logo=javascript&logoColor=black)
![Project](https://img.shields.io/badge/Project-Academic%20Demo-6254df)

</div>

---

## About the Project

**Smart Placement Portal** is a responsive frontend web application developed to simplify the campus placement process. It provides students with one workspace to explore job opportunities, check eligibility, save roles, submit applications, and monitor application progress.

The portal also includes an administrator area for managing sample job listings and updating application statuses. Multiple students can register and use separate accounts, with each account maintaining its own profile, saved jobs, and application history in the browser.

## Problem Statement

Students often use different sources to find placement opportunities and track applications. Managing academic details, job requirements, saved opportunities, and application progress separately can become difficult. This project demonstrates how these activities can be organized in one platform.

## Key Features

### Student Module
- Student registration, login, and logout.
- Separate accounts and individual student profiles.
- Dashboard with placement statistics and profile completion.
- Browse job and internship opportunities.
- Search by job role, company, location, and skills.
- Filter by location and job type; sort by package.
- View job details and requirements.
- Apply for jobs with duplicate-application prevention.
- Track statuses: Applied, Shortlisted, Interview, Selected, and Rejected.
- Save jobs to a personal shortlist.
- Check eligibility using CGPA, branch, and technical skills.
- Update personal, academic, and professional details.
- Select a resume file for the local demonstration.

### Administrator Module
- View the administrator overview.
- Add and delete sample job listings.
- View student application activity.
- Update application statuses.

### General
- Responsive interface for desktop and mobile.
- Separate student activity for each account in the same browser.
- Browser-based persistence using `localStorage`.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling, layout, and responsive design |
| JavaScript | Application logic, validation, and dynamic rendering |
| Browser localStorage | Demo account, profile, job, and application persistence |
| Git & GitHub | Version control and project hosting |

## Application Modules

| Module | Description |
|---|---|
| Authentication | Student registration, login, and logout |
| Dashboard | Placement statistics, featured opportunities, profile strength |
| Browse Jobs | Search, filter, sort, and view listings |
| Applications | Submit applications and monitor progress |
| Saved Jobs | Personal shortlist of opportunities |
| Eligibility Checker | Compare CGPA, branch, and skills with job requirements |
| Student Profile | Maintain personal, academic, and professional details |
| Admin | Manage sample listings and application statuses |

## Screenshots

Create a `screenshots` folder in the repository, add screenshots of your running application using the filenames below, and commit them to GitHub.

| Login | Student Dashboard |
|---|---|
| ![Login](screenshots/login.png) | ![Dashboard](screenshots/dashboard.png) |

| Browse Jobs | My Applications |
|---|---|
| ![Browse Jobs](screenshots/browse-jobs.png) | ![Applications](screenshots/applications.png) |

| Saved Jobs | Eligibility Checker |
|---|---|
| ![Saved Jobs](screenshots/saved-jobs.png) | ![Eligibility](screenshots/eligibility.png) |

| Student Profile | Admin Dashboard |
|---|---|
| ![Profile](screenshots/profile.png) | ![Admin](screenshots/admin.png) |

## Getting Started

### Prerequisites
- A modern web browser.
- Visual Studio Code (recommended).
- Live Server extension for Visual Studio Code (recommended).

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Maneesha-chimmiri/smart-placement-portal.git
   ```

2. Open the project folder:

   ```bash
   cd smart-placement-portal
   ```

3. Open the folder in Visual Studio Code.
4. Open `index.html` using **Live Server**.
5. Register a student account and explore the portal.

You can also open `index.html` directly in a browser. Live Server is recommended during development.

## Project Structure

```text
smart-placement-portal/
├── index.html       # Application layout and page structure
├── style.css        # Styling and responsive design
├── script.js        # Application logic and localStorage handling
├── README.md        # Project documentation
└── screenshots/     # Application screenshots
```

## Multi-Account Data Handling

- Each registered student receives a unique account ID.
- The active login session is stored separately in browser storage.
- Profile details, saved jobs, and applications are associated with the logged-in student's account.
- Logging out and signing in with another account displays that account's own information.
- Job listings are shared across accounts in the same browser.

## Learning Outcomes

- Building responsive interfaces using HTML and CSS.
- Using JavaScript for form handling, validation, and dynamic updates.
- Working with arrays, objects, functions, and event listeners.
- Managing browser data using `localStorage`.
- Implementing account-specific data handling in a frontend demonstration.
- Organizing a multi-module web application.
- Using Git and GitHub for version control.

## Limitations

This is a **frontend academic demonstration**. It does not currently use a backend server or database. Data is stored in browser `localStorage`, so it is limited to that browser and device. Passwords are not securely hashed, and the administrator demo is not protected by server-side authorization. Resume selection stores the filename locally; it does not upload the document.

Do not use real passwords or sensitive personal information in this demo.

## Future Enhancements

- Develop a backend using Node.js and Express.
- Integrate MongoDB for centralized data storage.
- Implement secure authentication and password hashing.
- Add role-based authorization for students and administrators.
- Enable secure resume uploads and downloads.
- Add recruiter/company accounts and job posting workflows.
- Provide notifications for application status changes.
- Deploy the application for access across devices.

## Author

**Manisha Chimmiri**  
B.Tech — Computer Science and Engineering

GitHub: [Maneesha-chimmiri](https://github.com/Maneesha-chimmiri)

---

<div align="center">

**Smart Placement Portal — Bringing placement activities into one workspace.**

</div>
