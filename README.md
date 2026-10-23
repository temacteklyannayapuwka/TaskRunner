# TaskRunner

TaskRunner is a Python service for submitting background tasks, running them with retries, and viewing execution history.

## Current features

- FastAPI HTTP service
- Health endpoint at `GET /health`

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
uvicorn app.main:app --reload
```

Check the service with:

```bash
curl http://127.0.0.1:8000/health
```
