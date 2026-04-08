<div align="center">
 
# Velox API
 
**A lightweight REST API built with FastAPI**
 
![Python](https://img.shields.io/badge/🐍_Python-3.11+-3776AB?style=flat-square&labelColor=3776AB&color=FFD43B)
![FastAPI](https://img.shields.io/badge/⚡_FastAPI-0.111-009688?style=flat-square&labelColor=009688&color=00BFA5)
![License](https://img.shields.io/badge/License-MIT-8A2BE2?style=flat-square&labelColor=555&color=8A2BE2)
 
</div>
 
---
 
A minimal REST API for user authentication and resource management. No unnecessary dependencies, no bloat.
 
## Installation
 
```bash
git clone https://github.com/yourname/velox-api.git
cd velox-api
pip install -r requirements.txt
uvicorn app.main:app --reload
```
 
API runs at `http://localhost:8000` · Docs at `/docs`
 
## Endpoints
 
| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/auth/login` | Obtain JWT token |
| `GET` | `/users/me` | Get current user |
| `GET` | `/items/{id}` | Retrieve item |
| `POST` | `/items` | Create item |
 
## Project Structure
 
```
velox-api/
├── app/
│   ├── main.py          # Entry point
│   ├── routers/         # Route definitions
│   ├── models/          # Database models
│   └── schemas/         # Pydantic schemas
└── requirements.txt
```
 
## Contributing
 
Fork → branch → commit → pull request. Issues welcome.
 
---
