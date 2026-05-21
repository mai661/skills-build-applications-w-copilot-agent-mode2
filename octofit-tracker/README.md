# OctoFit Tracker

A modern, multi-tier fitness tracking application built with React 19, Express, TypeScript, and MongoDB.

## 🏗️ Architecture

- **Frontend**: React 19 with Vite (Port 5173)
- **Backend**: Node.js + Express + TypeScript (Port 8000)
- **Database**: MongoDB with Mongoose (Port 27017)

## 📁 Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
│   ├── src/
│   │   ├── main.jsx
│   │   └── App.jsx
│   ├── package.json
│   ├── vite.config.js
│   └── index.html
└── backend/           # Express + TypeScript server
    ├── src/
    │   └── index.ts
    ├── package.json
    ├── tsconfig.json
    └── .gitignore
```

## 🚀 Quick Start

### Prerequisites
- Node.js v18+
- npm or yarn
- MongoDB running on port 27017

### Installation

**Frontend:**
```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

**Backend:**
```bash
cd octofit-tracker/backend
npm install
npm run dev
```

**MongoDB (Docker):**
```bash
docker run -d -p 27017:27017 mongo:latest
```

## 📝 Available Scripts

### Frontend
- `npm run dev` - Start development server (http://localhost:5173)
- `npm run build` - Build for production
- `npm run preview` - Preview production build

### Backend
- `npm run dev` - Start development server (http://localhost:8000)
- `npm run build` - Compile TypeScript
- `npm start` - Start production server

## 🔌 API Endpoints

- `GET /api/health` - Health check endpoint

## 📦 Dependencies

### Frontend
- react@^19.0.0
- vite@^5.0.8
- @vitejs/plugin-react@^4.2.1

### Backend
- express@^4.18.2
- mongoose@^7.5.0
- typescript@^5.2.2
- cors@^2.8.5
- dotenv@^16.3.1

## 🌳 Branch

All development happens on the `build-octofit-app` branch.

## 📖 Development Guide

1. Create a new feature branch from `build-octofit-app`
2. Make your changes
3. Test locally
4. Commit with clear messages
5. Push and create a Pull Request

Happy coding! 🐙💪
