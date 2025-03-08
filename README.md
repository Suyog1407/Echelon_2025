# AI-Powered Skill Clustering & Personalized Learning Paths

This project provides an intelligent learning platform that creates personalized learning paths based on user skills, interests, and career goals.

## Features

- User skill assessment and profiling
- LinkedIn profile integration
- Course recommendations using ML/NLP
- Adaptive learning paths
- Industry trends analysis
- Real-time personalization with chatbot
- Gamification elements

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Set up environment variables:
Create a `.env` file with:
```
LINKEDIN_API_KEY=your_key
LINKEDIN_API_SECRET=your_secret
MONGODB_URI=your_mongodb_uri
```

3. Run the application:
```bash
# Start backend
uvicorn app.main:app --reload

# Open frontend
Open index.html in your browser
```

## Project Structure

```
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
└── ml_models/
    ├── course_recommender.py
    ├── skill_clustering.py
    └── trend_analyzer.py
```

## API Documentation

The API documentation is available at `/docs` when running the server. 