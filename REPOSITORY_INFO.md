# School Notebook V2 - Repository Information

**Repository:** JulianSteckl/School-Notebook-V2  
**Repository ID:** 1259488501

## Overview
This is the outline and structure for a student productivity application called "School Notebook V2" - a comprehensive digital notebook designed to help high school students manage their coursework, including homework, quizzes, notes, schedules, and grades.

## Key Features
- **Dashboard Variants**: Multiple dashboard layouts (combined, focus, timeline)
- **Homework Management**: Task tracking with due dates, subject assignment, and urgency flags
- **Quiz Tracking**: Upcoming quizzes, practice modes, and confidence tracking
- **Notes System**: Subject-organized notes with markdown rendering and AI assistance
- **Flashcard Decks**: Study card creation and organization
- **Schedule Management**: Class schedules with real-time status indicators
- **Grade Tracking**: GPA calculations and subject grade monitoring
- **AI Integration**: AI tutoring, note enhancement, quiz generation
- **Design System**: Multiple theme variants and customization options

## File Structure

### Core Application Files
- **interactions.jsx** - Command palette (Cmd+K), quick-add modal, AI helpers, Pomodoro timer
- **homework.jsx** - Homework management, document viewer, AI homework helper
- **data.jsx** - Mock data and shared utilities (subjects, homework, notes, schedules)
- **design-canvas.jsx** - Design system wrapper with pan/zoom viewport
- **shell.jsx** - Main app shell and layout components
- **dashboard.jsx** - Dashboard variants and widgets

### Design & Exploration Files
- **Step Layout Explorations.html** - Design exploration for grades page variants (A, B, C, D, E, F)
- **Welcome Explorations.html** - Design exploration for welcome/onboarding screens
- **Homepage Concepts.html** - Homework page design concepts (B, E, F, G variants)
- **index.html** - Main entry point

### Configuration & Utilities
- **manifest.json** - PWA manifest configuration
- **download** - Build/download configuration

## Technology Stack
- **Frontend**: React 18.3.1, Babel (JSX)
- **Styling**: CSS variables, custom design system
- **Database**: Firebase (Realtime Database, Authentication)
- **PDF Handling**: PDF.js for document rendering
- **Design System**: Custom component library with tweaks panel
- **AI Integration**: Claude API integration (via window.claude)

## Design System Features
- Multiple color schemes (warm paper, dark slate)
- Typographic system with serif, sans, and monospace fonts
- Token-based color palette with semantic naming
- Density settings (compact, default, roomy)
- Customizable accent colors and display fonts

## Key Components

### Dashboard Variants
1. **Combined** - All-in-one view with homework, schedule, and streaks
2. **Focus** - Today-focused layout emphasizing current priorities
3. **Timeline** - Week-based view with calendar overview

### Homework System
- Card-based layout with subject indicators
- Document upload and viewing (PDF, images)
- AI homework helper with contextual assistance
- Quick add modal for task capture

### Notes Organization
- Subject-based note hierarchy
- Markdown rendering with callouts support
- AI-powered note enhancement
- Searchable note content

### Quiz System
- Upcoming quiz tracking
- Confidence scoring
- Quiz practice modes (MCQ)
- AI-generated quiz creation

## UI/UX Features
- Command palette for quick navigation (Cmd+K)
- Quick-add modal for capturing tasks
- Pomodoro timer integration
- API key management modal
- Subject management interface
- Real-time schedule status tracking
- Toast notifications

## Data Structure
The application tracks:
- **Subjects** - Classes with grades, teachers, rooms
- **Homework** - Tasks with due dates, subjects, urgency
- **Notes** - Subject-organized with blocks (paragraphs, headings, lists)
- **Quizzes** - Upcoming tests with dates and confidence
- **Schedule** - Class periods with times and locations
- **Flashcard Decks** - Study cards organized by subject

## Customization Options
- **Display Font**: Serif, Editorial, or Sans
- **Layout Density**: Compact, Default, or Roomy
- **Subject View**: Cards or List
- **Accent Color**: Multiple preset colors with custom selection
- **Dashboard Variant**: Combined, Focus, or Timeline views
- **Header Widget**: Stats, Schedule, Focus, or Off

## API Integrations
- **Firebase**: User authentication, real-time database, cloud storage
- **Claude AI**: Natural language processing, content generation, tutoring
- **Google Fonts**: Typography system
- **PDF.js**: PDF rendering and display

## Status
This is a comprehensive design and development outline for a student productivity app with multiple features, design variants, and AI integration capabilities.

---

**Note**: This repository outline includes design explorations, component documentation, and feature specifications for the School Notebook V2 application.
