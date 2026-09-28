# PocketSmart AI – Smart Budget & Recommendation Assistant

PocketSmart AI is a web-based budget planning and recommendation system that helps users plan spending for **home interiors, parties, and jewelry purchases**. The application uses a Flask backend, HTML/CSS templates, SQLite-based user management, optional Gemini AI integration, budget allocation logic, shopping links, recommendation history, and outfit-image analysis for the jewelry planner.

## Project Phases

1. Phase 1 – Brainstorming and Ideation
2. Phase 2 – Requirement Analysis
3. Phase 3 – Project Design
4. Phase 4 – Project Planning
5. Phase 5 – Project Development
6. Phase 6 – Project Testing
7. Phase 7 – Project Documentation
8. Phase 8 – Project Demonstration

## Overall Source Code

The complete runnable source code is located at:

`Phase-5-Project-Development/PocketSmart-AI-Source/`

Main files include:
- `app.py` – Flask application and routes
- `gemini_utils.py` – Gemini API integration and fallback handling
- `templates/` – UI pages and recommendation result pages
- `static/style.css` – application styling
- `requirements.txt` – Python dependencies
- `.env.example` – environment variable template
- `.gitignore` – protects `.env` and generated files

> Never upload your real `.env` file or Gemini API key to GitHub.

## Run Locally

```bash
python -m venv venv
venv\\Scripts\\activate
pip install -r Phase-5-Project-Development/PocketSmart-AI-Source/requirements.txt
```

Then open the source folder in VS Code and run:

```bash
python app.py
```

Open `http://127.0.0.1:5000` in a browser.
