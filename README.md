# NDURANCE AI

This repository contains the NDURANCE AI application split into a Python backend and a Next.js frontend.

## Structure

- `backend/` — FastAPI backend service, Python dependencies, and database files.
- `frontend/` — Next.js frontend application, TypeScript, and client-side code.
- `Dockerfile` — Builds the backend service container using `backend/requirements.txt`.
- `docker-compose.yml` — Compose setup for local containerized development.
- `.gitignore` — Repository ignore rules for both backend and frontend.

## Quick start

### Backend

```bash
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python run.py
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Docker (optional)

```bash
docker-compose up --build
```

## Notes

- Backend configuration is loaded from `backend/.env`.
- Frontend configuration is loaded from `frontend/.env.local`.
- The root `Dockerfile` targets `backend/`.

Aravindhan understanding in this project .

first i created in simple ui and low latency Ml code project . then 
i started work on frontend Design  with spidy theme for attarctive and easy accessible & understandable  .
after a discussion i implement the Docker file for both side acces in windows and linux also . 
this is a main scope i done this in my project .. 

Frontend Base is my 2st version i built for ndurance Gait project. 
beginning i was just implemented the only the python backend work it can python files,
after i work on frontend design to frame the project 
as a complete framework to analyse the through the frontend and work on backend base . 
