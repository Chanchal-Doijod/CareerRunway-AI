# CareerRunway AI 🚀

CareerRunway AI is a full-stack AI-powered career preparation platform designed to help job seekers optimize their resumes, identify skill gaps, and prepare for interviews with personalized AI-generated insights.

The platform analyzes a candidate's resume against a target job description and provides actionable feedback, interview preparation resources, and ATS-optimized resume generation.

---

## Features

### Resume & Job Description Analysis

* Upload resume and target job description.
* Extract and analyze resume content.
* Compare candidate skills with job requirements.
* Calculate job match score.

### Skill Gap Detection

* Identify missing or weak skills.
* Categorize skill gaps based on importance.
* Provide actionable recommendations.

### AI-Powered Interview Preparation

* Generate technical interview questions.
* Generate behavioral interview questions.
* Provide answer guidance and interviewer intent.

### Personalized Preparation Plan

* Create a structured day-wise interview preparation roadmap.
* Focus on skill improvement and interview readiness.

### ATS-Optimized Resume Generation

* Generate an ATS-friendly resume tailored to a target role.
* Export resumes as downloadable PDF documents.

### Secure Authentication

* User Registration & Login.
* JWT Authentication.
* Protected Routes.
* Token Blacklisting for secure logout.

---

## Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Axios
* Context API
* Custom Hooks

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

### Authentication & Security

* JWT Authentication
* Cookie-Based Sessions
* Token Blacklisting

### AI Integration

* Google Gemini API

### File Handling

* Multer
* PDF Parsing

### PDF Generation

* Puppeteer

---

## System Architecture

```text
User Uploads Resume + Job Description
                │
                ▼
          Express Backend
                │
                ▼
        Resume Text Extraction
                │
                ▼
        Gemini AI Processing
                │
     ┌──────────┼──────────┐
     ▼          ▼          ▼
 Match Score  Skill Gaps  Interview Questions
     │
     ▼
 Preparation Plan
     │
     ▼
 ATS Resume Generation
     │
     ▼
 Downloadable PDF
```

---

## Key Learning Outcomes

* Building production-style MERN applications.
* Implementing secure authentication using JWT.
* Integrating Generative AI into full-stack applications.
* Resume parsing and structured document analysis.
* Generating AI-powered interview reports.
* Creating downloadable PDFs using Puppeteer.
* Managing application-wide state using React Context and Custom Hooks.
* Designing scalable frontend architecture using feature-based folder structures.

---

## Project Structure

```text
CareerRunway-AI
│
├── Frontend
│   ├── src
│   ├── components
│   ├── pages
│   ├── hooks
│   ├── context
│   └── services
│
├── Backend
│   ├── src
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── middleware
│   ├── services
│   └── config
│
└── README.md
```

---

## Future Enhancements

* Company-specific interview preparation.
* Mock interview simulation.
* AI-powered career recommendations.
* Interview performance analytics.
* Multi-role career roadmap generation.
* Cloud deployment and CI/CD automation.

---

## Author

**Chanchal Doijod**

CareerRunway AI – AI-Powered Career Preparation Platform.
