# AI Solution Reviewer – Full Stack

This is the full-stack project split into two apps:

- `ai-solution-reviewer-backend/` – Django REST API
- `ai-solution-reviewer-frontend/` – React frontend

## 🐳 Run with Docker Compose

### 1. Clone and Setup

```bash
git clone https://github.com/your-org/ai-solution-reviewer.git
cd ai-solution-reviewer
cp ai-solution-reviewer-backend/.env.example ai-solution-reviewer-backend/.env
```

### 2. Start the App

```bash
docker-compose up --build
```

- Frontend: [http://localhost:3000](http://localhost:3000)
- Backend API: [http://localhost:8000](http://localhost:8000)

### 3. Admin Login

- **Username**: `admin`
- **Password**: `admin`

## 🔐 Notes

- AI assessments use OpenAI GPT via API key set in `.env`
- JWT Authentication via `/api/token/`
- Media files (PDFs, docs) stored in `media/` in backend container

Enjoy!