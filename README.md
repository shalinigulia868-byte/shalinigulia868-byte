# 🤖 AI Job Portal

An AI-powered full-stack job portal that connects candidates and recruiters through a modern web platform with intelligent skill matching.

## 🌐 Live Demo

[View Live Application](https://ai-job-portal-amber.vercel.app/)

## 📌 Overview

AI Job Portal is a full-stack web application designed to simplify the job search and recruitment process.

The platform provides separate experiences for candidates and recruiters. Candidates can explore jobs, apply for suitable opportunities, and view skill-match information, while recruiters can create and manage job listings and review applications.

The application uses a skill-matching system to compare a candidate's skills with the skills required for a job and identify matching and missing skills.

## ✨ Features

### 👨‍💻 Candidate

- User registration and login
- Browse available job opportunities
- View detailed job information
- Apply for jobs
- View skill-match results
- Identify matching and missing skills
- Track applications

### 🧑‍💼 Recruiter

- Recruiter authentication
- Create job postings
- Manage job listings
- View candidate applications
- Review candidate information

### 🔐 Authentication & Security

- JWT-based authentication
- Role-based access control
- Protected routes
- Separate candidate and recruiter workflows

### 🤖 Skill Matching

The application compares the candidate's skills with the skills required by a job.

The matching system:

1. Normalizes skills for comparison
2. Identifies matching skills
3. Identifies missing skills
4. Calculates a match percentage
5. Displays the result to the candidate

## 🛠️ Tech Stack

### Frontend

- React.js
- JavaScript
- Tailwind CSS
- Vite

### Backend

- Node.js
- Express.js
- MongoDB
- REST APIs
- JWT Authentication

### Tools & Deployment

- Git
- GitHub
- Vercel
- Render

## 🏗️ Project Structure

```text
ai-job-portal/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── package.json
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
