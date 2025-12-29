# Full-Stack Task Management Application

A responsive task management web app with user authentication, CRUD tasks, and a clean dashboard UI.

## MVP (v1) Goals

### User-facing features
- Users can **register** and **log in**
- Users can **create, view, edit, and delete** their own tasks
- Tasks support:
  - `title` 
  - `description` 
  - `status` = `todo | doing | done`
  - `due_date` 
- A simple dashboard:
  - Task list with filters (by status)
  - Basic counts (Todo / Doing / Done)

### Non-goals for v1 
- Teams, sharing, roles
- Comments, attachments
- Real-time updates
- Notifications

## Tech Stack

- **Frontend:** React (JavaScript), React Router, fetch/axios
- **Backend:** FastAPI (Python), JWT auth
- **Database:** PostgreSQL
- **Dev/Deploy:** Docker + Docker Compose (local), GitHub Actions (CI)
