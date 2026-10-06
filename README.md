A capstone project that uses a Python Flask backend to analyze a CV against a target job description.

## Features

- CV upload
- Job-description input
- Python-based skill matching
- Match score
- Skills found
- Skill gaps
- Recommended keywords
- Personalized recommendation
- Responsive web interface

## Project structure

```text
smart-cv-analyzer-python/
├── app.py
├── requirements.txt
├── README.md
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## Run locally

Install Python 3.10+.

```bash
pip install -r requirements.txt
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## AI extension

The current version demonstrates the complete Python/Flask workflow with a lightweight skill-matching engine. For the final AI version, the `analyze_text()` function in `app.py` can be connected to an NLP/LLM model to provide:

- Semantic CV/job similarity
- Better skill extraction
- Experience analysis
- AI-generated recommendations
- ATS keyword analysis

This makes Python the main backend and AI analysis layer.

## Important deployment note

GitHub Pages cannot run a Python Flask server. Use GitHub for the source repository and deploy the Flask application to a Python-compatible host such as Render, Railway, or another Flask-compatible service.

For the assignment, submit the public GitHub repository as the GitHub link and use the deployed Flask URL as the published-project link.
