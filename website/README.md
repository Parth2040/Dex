# Dex Website

Dex is a student productivity web app built with React, TypeScript, Vite, Zustand, and Tailwind CSS.

## Main modules

- Dashboard with metrics and notifications
- Tasks manager with urgency workflow
- Notes workspace (AI Summarizer, Flashcards, Quiz Maker, Live Notes)
- Focus timer and study tracking
- Dex AI planner/chat/analytics/timetable tools
- College hub (calendar, timetable, courses, exams)
- Resource shelf, collaborative hub, feedback hub, and settings
- Auth flow with local mock accounts

## Tech stack

- React 19 + TypeScript
- Vite 8
- Zustand
- Tailwind CSS
- Framer Motion
- Lucide icons

## Getting started

```bash
cd website
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Available scripts

- `npm run dev` — start local development server
- `npm run build` — run TypeScript build and production bundle
- `npm run lint` — run ESLint
- `npm run preview` — preview production build locally

## Mock login account

For quick testing, use:

- Email: `student@dex.app`
- Password: `DexPass123`

## Project structure

```text
website/
├─ src/
│  ├─ components/     # UI and feature modules
│  ├─ store/          # Zustand stores
│  ├─ lib/            # shared helpers and local storage utilities
│  └─ assets/         # static app assets
├─ public/            # public static files
└─ package.json
```
