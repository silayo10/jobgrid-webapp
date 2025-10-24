# JobGrid

**JobGrid** is a web app that connects to your email inbox (Gmail, Outlook, Yahoo) and uses AI to extract job-related emails â€” applications, interviews, resumes â€” then organizes them into a searchable, exportable table.

## Features

- OAuth login for Gmail, Outlook, Yahoo
- AI-powered email parsing and classification
- Dashboard with sortable job application table
- Export to CSV or Google Sheets
- Secure token handling and user data storage

## Tech Stack

| Layer       | Tools Used                     |
|-------------|--------------------------------|
| Frontend    | React, Tailwind CSS            |
| Backend     | Node.js + Express OR FastAPI   |
| Database    | Supabase or PostgreSQL         |
| Auth        | OAuth 2.0 (Google, Microsoft)  |
| AI Parsing  | OpenAI API or Copilot API      |
| Export      | SheetJS, Google Sheets API     |
| Hosting     | Vercel frontend, Render backend

## Folder Structure

jobgrid-webapp/
â”œâ”€â”€ client/             # React frontend
â”‚   â”œâ”€â”€ public/
â”‚   â””â”€â”€ src/
â”‚       â”œâ”€â”€ components/
â”‚       â”œâ”€â”€ pages/
â”‚       â”œâ”€â”€ utils/
â”‚       â””â”€â”€ App.jsx
â”œâ”€â”€ server/             # Backend API
â”‚   â”œâ”€â”€ routes/
â”‚   â”œâ”€â”€ controllers/
â”‚   â”œâ”€â”€ services/
â”‚   â””â”€â”€ index.js or main.py
â”œâ”€â”€ docs/               # Architecture, API flows, parsing logic
â”‚   â”œâ”€â”€ oauth-flow.md
â”‚   â”œâ”€â”€ ai-parsing.md
â”‚   â””â”€â”€ export-logic.md
â”œâ”€â”€ .env.example
â”œâ”€â”€ README.md
â””â”€â”€ LICENSE


## Setup Instructions

1. Initialize git: `git init`
2. Populate `.env` from `.env.example` with credentials
3. Install dependencies in `client` and `server`
4. Run frontend and backend locally
