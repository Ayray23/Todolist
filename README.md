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
On Vercel, the app uses browser `localStorage` so tasks persist in that browser without relying on a server filesystem. Tasks are device/browser-specific and do not sync across devices. In local development, the Node API stores tasks in `server/tasks.json`.
