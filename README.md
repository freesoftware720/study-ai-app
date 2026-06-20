# Study AI App

A full-stack mobile application that leverages AI to help students study effectively.

## Features

- 📱 Mobile-first design (React Native/Expo)
- 🤖 AI-powered tutoring chatbot
- 📚 Study material organization
- 🧠 Smart flashcard system with spaced repetition
- 📊 Progress analytics and tracking
- 🎯 AI-generated quizzes
- 👤 User authentication & profiles

## Tech Stack

### Frontend
- **React Native** with Expo
- **Redux** for state management
- **React Navigation** for routing
- **Axios** for API calls

### Backend
- **Node.js** with Express
- **MongoDB** for database
- **JWT** for authentication
- **OpenAI API** for AI features
- **Mongoose** for ODM

### DevOps
- Docker for containerization
- Environment-based configuration

## Project Structure

```
study-ai-app/
├── frontend/                 # React Native mobile app
│   ├── src/
│   │   ├── screens/
│   │   ├── components/
│   │   ├── navigation/
│   │   ├── redux/
│   │   └── services/
│   ├── app.json
│   └── package.json
├── backend/                  # Node.js/Express API
│   ├── src/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── services/
│   │   └── config/
│   ├── .env.example
│   └── package.json
├── docker-compose.yml
└── README.md
```

## Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn
- MongoDB (local or Atlas)
- Expo CLI (for frontend development)

### Installation

1. Clone the repository
2. Setup Backend (see `backend/README.md`)
3. Setup Frontend (see `frontend/README.md`)

## Environment Variables

See `.env.example` files in backend and frontend directories.

## Contributing

Feel free to submit pull requests and open issues!

## License

MIT
