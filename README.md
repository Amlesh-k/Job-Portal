# JOB PORTAL MANAGEMENT

## Overview

 Backend server built with Node.js, Express, and MongoDB  
- Provides APIs for user authentication, job postings, applications, and company management  
- Supports multiple user roles: students and recruiters  
- Enables job searching, applications, and profile management

## Features
  
User registration, login, and profile update with role-based access (student, recruiter)  
- Job posting and retrieval for recruiters and applicants  
- Application submission and status updates for jobs  
- Company registration and detailed company profiles  
- Middleware for authentication and file uploads using Multer  
- Cloudinary integration for media storage  
- MongoDB connection with schema models

- ## API Endpoints
-  **User routes:** `/api/users` — register, login, logout, update profile  
- **Job routes:** `/api/jobs` — post jobs, get all jobs, get recruiter jobs  
- **Application routes:** `/api/applications` — apply for jobs, get applied jobs, update application status  
- **Company routes:** `/api/companies` — register company, get details, update company

- 
