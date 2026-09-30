# Daymark — To-do list

A responsive React + Tailwind task manager backed by a Node.js/Express API.

## Requirements
- Node.js 18+

## Run locally
```bash
npm install
npm run dev
```
Vite serves the app at http://localhost:5173 and proxies `/api` requests to the Express API at http://localhost:4000.

## Production build
```bash
npm run build
npm start
```
The API stores tasks in `server/tasks.json`. For deployment, use a persistent disk/volume for that file; ephemeral server filesystems can lose data on redeploy. This starter is intended for a single-server deployment, not multi-instance scaling.
