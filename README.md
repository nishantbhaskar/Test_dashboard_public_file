# Student Portal

The **Student Portal** is a web and mobile application designed for students to create and take custom tests by uploading images of questions. It includes features like question scanning using AI, digital test creation, group testing, scoring, and ranking.

---

## **Features**
- Upload images to generate questions with options using AI.
- Take custom tests individually or in groups.
- View scores and ranks in group tests.
- Default tests using saved database questions or previous years' questions.
- Detailed explanations for correct answers.

---

## **Project Structure**
```plaintext
/student-portal
├── backend/                # Backend logic using Flask
│   ├── app/                # Core backend logic
│   ├── tests/              # Backend unit tests
│   ├── requirements.txt    # Python dependencies
│   ├── app.py              # Main entry point for the backend
│   └── README.md           # Documentation for the backend
├── frontend/               # Frontend application (React/Angular/Vue)
│   ├── src/                # Source files for the frontend
│   ├── public/             # Public assets
│   ├── package.json        # Frontend dependencies
│   └── README.md           # Documentation for the frontend
├── README.md               # Main project documentation
├── .gitignore              # Files ignored by Git
└── tests/                  # End-to-end or integration tests


code base in different private repo 
