# campus-shield

campus safety app: report incidents, keep emergency contacts and raise siren alerts.

## features

- student sign up / sign in and profile with emergency contacts
- incident reports
- siren alerts
- admin view of reports

## stack

react 18 + vite · recoil · tailwind css · express · mongodb (mongoose) · zod · jwt

## run locally

needs node 20.6+.

```bash
npm install && cp backend/.env.example backend/.env && node --env-file=backend/.env backend/index.js
cd frontend && npm install && npm run dev
```

## env

copy `backend/.env.example` to `backend/.env` and set `MONGODB_URI`.
