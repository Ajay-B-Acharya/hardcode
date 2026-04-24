# Hardcode

Hardcode is an AI-assisted hardware workflow app for taking a project idea from ideation to components, design, and Wokwi simulation.

## What it includes

- Ideation chat for turning a prompt into a project plan
- Components workflow for generating sketch and diagram files
- Design workspace for editing and reviewing the circuit setup
- Wokwi proof lab for local simulation, evidence, and file inspection
- Firebase-backed authentication and session handling

## Project layout

- `backend/` contains the Express API, auth, AI services, and Wokwi integration
- `frontend/` contains the React app and workspace UI

## Development

Backend:

```bash
cd backend
npm install
npm run dev
```

Frontend:

```bash
cd frontend
npm install
npm run dev
```

## Build

```bash
cd frontend
npm run build
```

## Notes

- The main branch UI is preserved in the workspace pages.
- Local auth and backend fixes remain included in this branch snapshot.
