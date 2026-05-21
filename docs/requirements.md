# ITI E-Learning Platform - Requirements

## Project Goal
Build a complete E-Learning system for ITI students (Web + Mobile).

## Target Users
- Students (ITI trainees)
- Admin (Teacher / Your Father)

## Platforms
- Web App (Primary - Desktop + Mobile browsers)
- Mobile App (Android first, later iOS)

## Core Features (MVP)

### User Management
- Student Registration (Name, Email/Phone, Trade, Password)
- Login / Logout
- Admin Login

### Course & Learning
- Browse Courses/Trades
- Course Details + Modules + Lessons
- Lesson content: Text, Images, PDF notes, YouTube videos
- Mark lesson as Complete
- Simple MCQ Quiz per module
- Progress Tracking & Continue Learning

### Dashboard
- Student: My Courses, Progress, Recommended lessons
- Admin: Manage courses, students, content

### Extra (Phase 2)
- Offline access (for mobile)
- Push notifications for new lessons / deadlines
- Certificate generation

## Trades/Courses (Please list them here)
1. Electrician
2. Fitter
3. COPA (Computer Operator & Programming Assistant)
4. ... (add all you want)

## Tech Stack (Industry Standard)

**Frontend Web:**
- HTML + CSS + JavaScript + Tailwind CSS (Phase 1)
- Later: React.js

**Mobile App:**
- React Native (one codebase for Android + iOS)
- Or Flutter (we can decide later)

**Backend (Common for both Web & Mobile):**
- Node.js + Express
- PostgreSQL Database
- REST APIs + JWT Authentication

**Other Tools:**
- Git + GitHub
- Vercel / Render (for deployment)

## Design Goal
- Clean, simple UI
- Mobile-first design
- Easy navigation for students