# Multilingual Translation API

A lightweight REST API built with FastAPI for translating text into multiple languages in a single request. The application integrates OpenAI and Deep Translator for translation and stores translation records in PostgreSQL using SQLAlchemy.

## Tech Stack

- FastAPI
- Python
- PostgreSQL
- SQLAlchemy
- OpenAI API
- Deep Translator

## Features

- Translate text into multiple languages in one request
- RESTful API built with FastAPI
- CRUD operations for translation records
- PostgreSQL-backed persistent storage

## Run Locally

```bash
git clone <repository-url>
cd translator_app

python -m venv .venv
source .venv/bin/activate      # Linux/macOS
# or
.venv\Scripts\activate         # Windows

pip install -r requirements.txt

uvicorn app.main:app --reload
```

Open:

```
http://127.0.0.1:8000/index
```