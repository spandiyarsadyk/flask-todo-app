# Flask ToDo App

Pet project for practicing backend and DevOps skills.

## Tech stack
- Python 3
- Flask
- PostgreSQL
- SQLAlchemy
- Gunicorn
- Nginx
- systemd
- Linux (Ubuntu)

## Features
- Create, update and delete tasks
- Data stored in PostgreSQL
- Environment variables via .env
- Production-ready setup with Gunicorn and Nginx

## Architecture
Client → Nginx → Gunicorn → Flask → PostgreSQL

## Deployment
- Application runs as systemd service
- Reverse proxy via Nginx
- Database: PostgreSQL

## What I practiced
- Python virtual environments (venv)
- Flask application structure
- PostgreSQL integration
- systemd services
- Nginx reverse proxy
- Git and GitHub workflow

## How to run locally
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```
