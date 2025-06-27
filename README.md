# Smart Resume Analyzer & Job Matcher

A web application that parses resumes and recommends suitable job roles based on skills and experience using NLP and simple rule-based matching.

## Features
- Upload resume (PDF)
- Extract key info (skills, experience, education)
- Match with suitable job roles
- Display skill gaps and suggestions

## Tech Stack
- Python (Flask)
- React (Frontend)
- PyPDF2, spaCy (NLP)
- Docker (optional for deployment)

## Setup Instructions

### Backend (Flask)
1. Navigate to backend directory: `cd backend`
2. Create virtual environment: `python3 -m venv venv && source venv/bin/activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the server: `python app.py`

### Frontend (React)
1. Navigate to frontend: `cd frontend`
2. Install dependencies: `npm install`
3. Start frontend server: `npm start`

## Future Enhancements
- Use GPT/OpenAI API for smarter analysis
- Database integration
- User login and dashboard
