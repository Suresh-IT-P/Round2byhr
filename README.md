# QuizCloud 🚀

A premium fullstack quiz application built for classroom environments.

## ✨ Features
- **Modern UI**: Dark mode with glassmorphism and smooth animations.
- **Teacher Dashboard**: Create quizzes with unique codes and track student results in real-time.
- **Student Portal**: Secure landing and quiz-taking experience with integrated timers and progress tracking.
- **Persistent Storage**: All data stored locally in a SQLite database.

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6)
- **Backend**: Node.js, Express.js
- **Database**: SQLite (better-sqlite3)

## 🚀 Getting Started

### Prerequisites
- Node.js installed

### Installation & Setup
1. Open this folder in your terminal.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
4. Open your browser and go to `http://localhost:3000`.

### Workflow
1. **Teacher**: Go to `http://localhost:3000/admin.html` to create a new quiz. Note the **Quiz Code** (e.g., `GK101`).
2. **Student**: Go to `http://localhost:3000` and enter the Quiz Code.
3. **Review**: After students submit, the teacher can view scores in the Admin Dashboard.
