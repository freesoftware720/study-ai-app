# Contributing to Study AI App

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a feature branch: `git checkout -b feature/your-feature`
4. Make your changes
5. Commit: `git commit -m 'Add feature'`
6. Push: `git push origin feature/your-feature`
7. Open a Pull Request

## Development Setup

### Backend
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

### Frontend
```bash
cd frontend
npm install
cp .env.example .env
npm start
```

### Database
```bash
docker-compose up mongodb
```

## Code Standards

- Use ESLint for linting
- Follow existing code style
- Write meaningful commit messages
- Add comments for complex logic
- Test your changes before submitting PR

## Commit Message Format

`[type]: [description]`

Types: feat, fix, docs, style, refactor, test, chore

Example: `feat: add user authentication endpoints`
