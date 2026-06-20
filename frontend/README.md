# Study AI App - Mobile Frontend

Mobile application for Study AI App built with React Native and Expo.

## Features

- User authentication
- Study dashboard
- AI tutoring chatbot
- Quiz system
- Flashcard management
- Progress tracking
- Cross-platform support (iOS, Android, Web)

## Prerequisites

- Node.js (v16+)
- npm or yarn
- Expo CLI

## Installation

1. Install dependencies:
```bash
npm install
```

2. Create a `.env` file based on `.env.example`:
```bash
cp .env.example .env
```

3. Update `.env` with your API endpoint:
```
EXPO_PUBLIC_API_URL=http://your-api-url/api
```

## Running the App

### Start Development Server
```bash
npm start
```

### Run on iOS
```bash
npm run ios
```

### Run on Android
```bash
npm run android
```

### Run on Web
```bash
npm run web
```

## Project Structure

```
src/
├── screens/           # Screen components
│   ├── auth/         # Authentication screens
│   └── app/          # Main app screens
├── navigation/       # Navigation configuration
├── redux/            # State management
│   ├── actions/
│   ├── reducers/
│   └── store.js
├── components/       # Reusable components
├── services/         # API services
└── App.js           # Main app component
```

## API Integration

The app uses axios for API calls with automatic token management via Expo SecureStore.

See `src/services/api.js` for configuration.

## State Management

Redux is used for state management with the following slices:
- **auth**: User authentication and profile
- **study**: Study materials, quizzes, flashcards

## Contributing

Feel free to submit pull requests.
