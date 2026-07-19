# FinStart 💰

FinStart is an AI-powered financial literacy platform designed to help beginners learn investing through interactive lessons, risk assessment, AI guidance, and paper trading.

## Features

- 📚 Interactive financial learning modules
- 🤖 AI Finance Buddy
- 📊 Personalized risk assessment
- 📈 Paper trading with virtual portfolio
- 🛡️ Scam awareness and detection
- 🔐 Secure JWT authentication

## Tech Stack

### Backend
- FastAPI
- Python
- SQLAlchemy
- PostgreSQL
- JWT Authentication

### Frontend
- React.js
- Tailwind CSS

### AI
- Google Gemini API

## Project Structure

```
FinStart/
│
├── backend/
│   ├── app/
│   │   ├── ai/
│   │   ├── crud/
│   │   ├── models/
│   │   ├── routers/
│   │   ├── schemas/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── main.py
│   │   ├── database.py
│   │   ├── config.py
│   │   └── dependencies.py
│   ├── requirements.txt
│   └── .env.example
│
├── frontend/
│
└── README.md
```

## Team

| Role | Responsibility |
|------|----------------|
| Backend | FastAPI APIs, Authentication, Database |
| Frontend | React UI |
| AI | Gemini integration & AI features |

## Getting Started

### Clone the repository

```bash
git clone <repository-url>
```

### Backend Setup

```bash
cd backend

python -m venv myenv

# Windows
myenv\Scripts\Activate.ps1

pip install -r requirements.txt
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Branches

- `main` – Stable production-ready code
- `backend` – Backend development
- `frontend` – Frontend development
- `ai` – AI development

## License

This project is developed for a hackathon.