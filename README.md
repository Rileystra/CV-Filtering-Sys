# CV Filtering System using AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-yellow)
![Vite](https://img.shields.io/badge/Vite-Build_Tool-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Project Type](https://img.shields.io/badge/Project-Recruitment%20System-blue)

A cloud-based CV filtering and recruitment support system designed to streamline candidate application handling, secure document uploads, and recruiter-side screening. The application combines a modern frontend with AWS-based cloud storage and backend API integration to support efficient candidate review and filtering.

---

## Overview

This project was developed to improve the recruitment process by reducing manual effort in handling CV submissions and supporting documents. It provides a structured application workflow where candidates can upload their details and files, while administrators can review applications through a dashboard, filter candidates by relevant criteria, and assess suitability more efficiently.

The system demonstrates practical application of cloud technologies in a real-world business scenario, with a focus on usability, security, and operational efficiency.

---

## Key Features

- Candidate application form for collecting applicant information
- Upload support for CVs, profile images, and PDF documents
- Secure file upload workflow integrated with AWS
- Recruiter/admin dashboard for reviewing applications
- Filtering by job role and application status
- Suitability scoring logic for shortlisting support
- Responsive interface for a better user experience
- API-based communication between frontend and backend services

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- Vite

### Cloud / Backend
- Amazon Web Services (AWS)
- Amazon S3
- REST API integration
- Pre-signed URL upload workflow

### Development Tools
- Git
- GitHub
- VS Code

---

## System Workflow

1. A candidate fills in the online application form.
2. The candidate uploads supporting files such as a CV, image, or PDF.
3. Files are securely uploaded to AWS storage using a pre-signed upload process.
4. Candidate data is submitted through an API to the application backend.
5. The recruiter/admin accesses the dashboard to review all applications.
6. Applications can be filtered by role and status.
7. A suitability score helps identify stronger candidates more quickly.

---

## Architecture Summary

This project follows a simple cloud-integrated web application architecture:

- **Frontend client** handles user interaction and form submission
- **AWS S3** stores uploaded CVs and other documents securely
- **Backend API** processes candidate data and supports dashboard access
- **Admin dashboard** displays submissions and enables filtering/review

### Architecture Flow

```text
Candidate User
   ↓
Web Application Frontend
   ↓
Secure Upload Request
   ↓
AWS S3 Bucket (Document Storage)

Candidate Form Data
   ↓
Backend API
   ↓
Application Processing / Dashboard Data
   ↓
Admin Dashboard
