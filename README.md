# place. — Smart Placement Portal

Responsive frontend placement portal based on the supplied reference screenshots.

## Run
1. Extract the ZIP and open this folder in VS Code.
2. Open `index.html` with Live Server.
3. Register separate student accounts using unique email addresses.

## Demo admin
Email: `admin@placement.com`  
Password: `Admin@123`

## Included screens and features
- Login and student registration
- Multi-account support with account-specific profile, saved jobs and applications
- Dashboard with placement statistics and profile completion
- Browse jobs with keyword, location and job-type filters and package sorting
- Job details, apply action and duplicate-application prevention
- Application status filters and history
- Saved jobs
- Eligibility checker using CGPA, branch and skills
- Student profile and resume filename selection
- Admin overview, add/delete listings and update student application statuses
- Responsive layout for smaller screens

## Data and security note
This is a frontend-only demonstration. Account information is stored in this browser's `localStorage`; it is not shared across devices or browsers. Passwords are not securely hashed, and the admin demo credentials are visible in frontend code. Do not use real passwords or sensitive personal data. A production portal requires a backend, database, password hashing, server-side validation, authorization and secure sessions. Resume selection stores only the filename; it does not upload a file to a server.
