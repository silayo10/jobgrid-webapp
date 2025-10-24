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
├── client/                    # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── utils/
│       └── App.jsx
├── server/                    # Backend API
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   └── index.js
├── docs/                      # Architecture, API flows, parsing logic
│   ├── oauth-flow.md
│   ├── ai-parsing.md
│   ├── export-logic.md
│   └── contributing.md
├── .env.example
├── .gitignore
├── README.md
└── LICENSE


## Setup Instructions

1. Initialize git: `git init`
2. Populate `.env` from `.env.example` with credentials
3. Install dependencies in `client` and `server`
4. Run frontend and backend locally

