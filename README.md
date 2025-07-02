# AI-Powered Job Tracker

An intelligent platform to help users efficiently manage and optimize their job application process. The system uses AI to extract job details, recommend relevant opportunities, match resumes, and track application progress.

## Features

- Job Description Parsing: Automatically extracts role, skills, location, and deadlines using NLP techniques.
- Resume Matching: Compares and scores resumes against job descriptions using semantic similarity models.
- Application Tracker: Visual dashboard for managing job statuses (Saved, Applied, Interview, Offer, Rejected).
- Smart Alerts: Reminds users of approaching deadlines or pending tasks.
- Recommendation Engine: Suggests new roles based on user profile and previous applications.
- Assistant Chatbot: Interactive assistant for answering queries and guiding next steps.

## Tech Stack

- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB (via MongoDB Atlas)
- AI/NLP: Python, spaCy, Transformers (e.g., BERT/SBERT)
- Authentication: Firebase Auth or JWT
- Deployment: Vercel (frontend), Render/Heroku (backend)

## Installation Instructions

### Backend Setup

```bash
cd backend
npm install
npm run dev
