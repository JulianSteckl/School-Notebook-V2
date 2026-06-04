# School Notebook V2

A comprehensive student study companion featuring notes, homework tracking, quizzes, grades management, and AI-powered study tools.

## Overview

School Notebook V2 is a full-featured web application built with React for high school students. It combines productivity tools with AI assistance to help students manage their academic workload.

## Features

- **Dashboard**: Customizable home screen with multiple layout variants
- **Homework Tracking**: Add, track, and manage assignments with due dates and time estimates
- **Notes**: Organized note-taking by subject with support for rich formatting
- **Quizzes & Flashcards**: Practice mode with spaced repetition
- **Grades Management**: Track grades by subject with GPA calculation
- **Schedule**: Bell schedule tracking and class management
- **AI Study Tools**: AI-powered note drafting, quiz generation, and tutoring assistance
- **Cloud Sync**: Firebase integration for cross-device synchronization
- **Mobile App**: Responsive design with dedicated mobile layout

## Tech Stack

- **Frontend**: React 18.3, Babel
- **Styling**: CSS-in-JS with design tokens
- **Backend**: Firebase (Auth & Realtime Database)
- **AI Integration**: Claude API support
- **Storage**: LocalStorage + Firebase Realtime DB
- **PDF Support**: PDF.js for document viewing

## Project Structure

```
/
├── index.html                 # Main entry point
├── interactions.jsx           # Command palette, modals, helpers
├── dashboard.jsx              # Dashboard variants and layouts
├── homework.jsx               # Homework management
├── shell.jsx                  # App shell and routing
├── data.jsx                   # Mock data and shared utilities
├── store.jsx                  # State management
├── styles.css                 # Global styles
├── mobile.jsx                 # Mobile layout
├── onboarding.jsx             # User onboarding flow
├── manifest.json              # PWA manifest
└── [Design files]             # HTML design explorations
```

## Getting Started

### Installation

1. Clone the repository
2. Open `index.html` in a modern web browser
3. Complete the onboarding flow to set up your subjects

### Configuration

#### Firebase Setup

The app uses Firebase for authentication and data sync:

```javascript
firebase.initializeApp({
  apiKey: "YOUR_API_KEY",
  authDomain: "your-project.firebaseapp.com",
  databaseURL: "https://your-project.firebaseio.com",
  projectId: "your-project",
  // ... other config
});
```

#### Claude AI Integration

To enable AI features, add your Claude API key in the app settings:
- Open the app
- Click "✦ Connect AI" in the top bar
- Paste your API key from console.anthropic.com

### Development

The project uses vanilla JavaScript with React and Babel for JSX support. All development happens directly in HTML/JSX files without a build step.

To modify:
1. Edit `.jsx` or `.html` files directly
2. Refresh the browser to see changes
3. Use browser DevTools for debugging

## Features in Detail

### Dashboard Variants

- **Combined**: All-in-one view with full information density
- **Focus**: Priority-focused minimal view
- **Timeline**: Week-at-a-glance calendar view

### Homework Management

- Create, edit, and delete assignments
- Track due dates and time estimates
- Mark assignments as complete
- Attach documents (PDFs, images)
- AI-powered homework help and tutoring

### Notes

- Organize by subject
- Rich formatting support (headings, lists, quotes, code blocks)
- AI note generation from topic descriptions
- Tag-based organization
- Export to various formats

### Study Tools

- **Flashcards**: Create custom decks and practice
- **Quizzes**: Multiple choice and review modes
- **AI Study Helper**: Explain concepts, generate flashcards, create quizzes

### Grades

- Track grades by subject
- Automatic GPA calculation
- Grade distribution visualization
- Historical tracking

## Keyboard Shortcuts

- `Cmd/Ctrl + K`: Open command palette
- `Cmd/Ctrl + N`: Quick add homework
- `Enter`: In modals, submit forms
- `Esc`: Close modals and overlays

## Data & Privacy

- All data is stored in your browser's localStorage
- Optional cloud sync via Firebase (requires sign-in)
- API keys are stored only in localStorage
- No data is sent anywhere except to Anthropic (for AI) and Firebase (for sync)

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- iOS Safari 14+

## License

Created by Julian Steckl

## Acknowledgments

- Design inspiration from modern study tools
- Firebase for reliable backend
- Anthropic Claude for AI features
- PDF.js for document handling
