# UCT Student Hub — Phase 9

A static, installable student-planning PWA. No build process, database or environment variables are required.

## Phase 9 additions
- **My Day agenda** combining classes, assessment deadlines, tasks, generated study-plan blocks and reminders
- Seven-day date strip and a chronological daily timeline
- Quick capture for adding a task or reminder without leaving the agenda
- Reminder centre with date, time, course and daily/weekly recurrence
- In-app notification checks while the PWA is open
- Agenda and reminders included in search, JSON backups, CSV export and semester archives
- Automatic migration from Phase 8 browser data

## Retained from previous phases
- Compact seven-column mobile calendar and `.ics` export
- Dashboard, editable timetable and assessment tracker
- Focus timer, study log, marks and budget
- Tasks, attendance, goals, habits, resources and exam-prep hub
- Semester manager and archive workflow

## Deploy
Replace these four files in the root of the existing GitHub repository:
- `index.html`
- `manifest.json`
- `service-worker.js`
- `README.md`

Commit the changes. Vercel should redeploy automatically. Refresh the deployed app twice so the Phase 9 service worker replaces the old cache.

## Reminder limitation
This static PWA can check scheduled reminders while the app is open. Reliable closed-app/background push notifications require a server or push-notification service, which is planned for the later cloud phase.
