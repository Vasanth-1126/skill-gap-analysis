 Skill Gap Analysis Agent

Project Overview
The Skill Gap Analysis Agent is an AI-powered web application that analyzes a user's resume, identifies existing skills, compares them with the required skills for a target job role, and provides personalized learning recommendations using Google Gemini AI.

---

 Features
- Resume Upload
- AI-Based Skill Analysis
- Skill Gap Identification
- Personalized Learning Recommendations
- Career Readiness Score
- Responsive User Interface
- Fast AI Processing

---

 Tech Stack

 Frontend
- React.js
- TypeScript
- Vite
- Tailwind CSS
- Motion
- Lucide React

 Backend
- Node.js
- Express.js
- Google Gemini API
- dotenv
- npm

 Communication
- REST API
- Fetch API

Deployment
- Docker
- Google Cloud Run

---

 Project Structure

```
Skill-Gap-Analysis-Agent/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── components/
│   ├── App.tsx
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   ├── server.js
│   └── package.json
│
├── README.md
└── Dockerfile
```

---

 Workflow

1. User opens the application.
2. User uploads a resume.
3. Frontend sends the data to the backend using REST API.
4. Backend processes the request.
5. Google Gemini AI analyzes the resume.
6. AI identifies existing and missing skills.
7. Backend returns the analysis.
8. Frontend displays the results.

---

 Architecture

```
User
   │
   ▼
React Frontend
   │
Fetch API
   │
REST API
   │
Express.js
   │
Node.js
   │
Google Gemini AI
   │
Analysis Result
   │
React Dashboard
```

---


 Use Cases

- Students
- Freshers
- Job Seekers
- Career Guidance
- Placement Preparation
- Employee Upskilling




- ATS Resume Score
- Interview Question Generator
- Job Recommendation System
- Course Recommendation
- Progress Tracking
- Multi-language Support

