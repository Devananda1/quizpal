# QuizPal 

An AI-powered placement interview preparation platform with adaptive difficulty, AI-generated questions, and progress tracking.

##  Features

-  **AI-Generated Questions** — Generates placement questions using the Claude API.
-  **Adaptive Difficulty** — Difficulty increases after 3 consecutive correct answers and decreases after 2 consecutive incorrect answers.
-  **Progress Dashboard** — Track performance with charts, topic-wise accuracy, and session history.
-  **45-Second Timer** — Each question has a time limit to simulate interview pressure.
-  **JWT Authentication** — Secure registration, login, and persistent sessions.
-  **Multiple Topics** — Practice DSA, CS Fundamentals, Aptitude, and Core CS (OOP).

##  Technologies Used

- **Frontend:** React, Vite
- **Backend:** Python, Flask
- **Database:** SQLite
- **AI:** Claude API
- **Authentication:** JWT
- **Languages:** JavaScript, Python

##  Project Structure

```text
quizpal/
├── backend/
│   ├── routes/
│   │   ├── auth.py
│   │   ├── quiz.py
│   │   ├── dashboard.py
│   │   └── admin.py
│   ├── app.py
│   ├── database.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   └── pages/
│   └── vite.config.js
│
├── .gitignore
└── README.md