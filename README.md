 Skill Gap Analysis Agent

An AI-powered web application that analyzes a user's resume, identifies skill gaps for a target job role, and provides personalized learning recommendations using Google Gemini AI.

---

 Project Overview

The Skill Gap Analysis Agent helps students, job seekers, and professionals understand the difference between their current skills and the skills required for their desired career. Users upload their resume, and the application uses Google Gemini AI to analyze the resume, identify missing skills, and generate a personalized learning roadmap.

---

 Features

-  Resume Upload and Analysis
-  AI-Powered Skill Extraction
-  Skill Gap Analysis
-  Career Readiness Assessment
-  Personalized Learning Recommendations
-  Fast and Responsive User Interface
-  Cloud Deployment

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
- JSON

 Deployment

- Docker
- Google Cloud Run

---

 Project Architecture

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
Node.js + Express.js
   │
Google Gemini API
   │
AI Skill Analysis
   │
JSON Response
   │
React Dashboard
```

---

 Workflow

1. User opens the application.
2. User uploads their resume.
3. User enters the target job role.
4. React frontend sends the data to the backend using Fetch API.
5. Express.js receives the request.
6. Node.js processes the resume.
7. Backend sends the resume to Google Gemini AI.
8. Gemini analyzes the resume and identifies:
   - Existing Skills
   - Missing Skills
   - Skill Match
   - Learning Recommendations
9. Backend returns the analysis.
10. Frontend displays the complete skill gap report.

---

 Project Structure

```
Skill-Gap-Analysis-Agent/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
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
├── Dockerfile
├── README.md
└── package.json
```

---

 Installation

Clone the Repository

```bash
git clone https://github.com/your-username/Skill-Gap-Analysis-Agent.git
```

 Install Frontend Dependencies

```bash
cd frontend
npm install
npm run dev
```

Install Backend Dependencies

```bash
cd backend
npm install
npm start
```

---

Environment Variables

Create a `.env` file in the backend directory and add:

```env
GEMINI_API_KEY=your_google_gemini_api_key
```

---

 Deployment

The application is deployed using:

- Google Cloud Run
- Docker

---

 Technologies Used

| Category | Technology |
|----------|------------|
| Frontend | React.js |
| Language | TypeScript |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| Animation | Motion |
| Icons | Lucide React |
| Backend | Node.js |
| Framework | Express.js |
| AI | Google Gemini API |
| API | REST API |
| Data Transfer | Fetch API |
| Environment | dotenv |
| Package Manager | npm |
| Deployment | Google Cloud Run |
| Containerization | Docker |

---

 Use Cases

- Students preparing for placements
- Freshers seeking jobs
- Career guidance platforms
- Resume evaluation
- Employee upskilling
- Skill assessment

---

 Future Enhancements

- ATS Resume Score
- Interview Question Generator
- Job Recommendation System
- Course Recommendation Integration
- Progress Tracking Dashboard
- Multi-language Support
- User Authentication

---
