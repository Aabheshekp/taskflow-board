# Taskflow Board

A locally hosted kanban board with task creation, descriptions, priority, due dates, three workflow lanes, move controls, delete confirmation, SQLite persistence, and a health endpoint.

## Requirements

Node.js 18+ and npm.

## Run

```sh
npm install
npm start
```

Open http://localhost:3000. Data is stored in `taskflow.sqlite3` (ignored by Git). This starter is intended for local use; add authentication, CSRF protection, and deployment hardening before exposing it to the public internet.

### Category

Web development | JavaScript, Express, SQLite, HTML/CSS
