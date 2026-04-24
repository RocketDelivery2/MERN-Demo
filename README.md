<h1 align="center">MERN Portfolio</h1>

<p align="center">
  A full-stack MERN portfolio app built with React + Chakra UI, powered by an Express API and MongoDB.
</p>

<p align="center">
  <a href="https://mern-demo-49es.onrender.com" target="_blank"><b>Live Demo</b></a>
  ·
  <a href="https://vue-demo-t89m.onrender.com" target="_blank"><b>Vue Demo</b></a>
</p>

---

## Tech Stack

- **Frontend:** React, React Router, Chakra UI
- **State:** Zustand
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (NoSQL)
- **Deployment:** Render

---

## Project Structure (high level)

- `frontend/` — React client (Vite + Chakra UI)
- `/` (root) — Express API + build/start scripts

---

## Prerequisites

- **Node.js** (LTS recommended)
- **MongoDB** (Atlas or local)
- **npm**

---

## Environment Variables

Create a `.env` file in the project root:

```bash
MONGO_URI=your_mongo_uri
PORT=5000
```

> Keep `.env` private (do not commit it).

---

## Install & Run Locally

From the project root:

```bash
npm install
```

Install frontend dependencies:

```bash
cd frontend
npm install
```

Start the app (production-style using the built frontend):

```bash
# from project root
npm run build
npm run start
```

Then open: `http://localhost:5000`

---

## Common Dependency Notes

If you’re setting up from scratch and you see missing-package errors, these are used in the frontend:

```bash
cd frontend
npm i react-router-dom zustand
```

On Windows, you may need `cross-env`:

```bash
npm i -D cross-env
```

---

## Deployment (Render)

Typical build/start flow:

```bash
cd frontend
npm run build

cd ..
npm run build
npm run start
```

If `npm audit` suggests safe fixes:

```bash
npm audit fix
```

---

## About

My name is **Christopher Peterson**. I’m a full-stack software engineer focused on delivering polished UI/UX experiences along with reliable backend systems.

- **Vue demo:** https://vue-demo-t89m.onrender.com  
- **GitHub:** https://github.com/TeamBuilderApp?tab=repositories  
- **LinkedIn:** https://www.linkedin.com/in/christopher-peterson-86728a303/  
- **Email:** cpeterson.software.engineering@gmail.com  
- **Phone:** (517) 297-5674

---

## References / Credits

- Public domain images: https://free-images.com/
- Chakra UI docs: https://chakra-ui.com/docs/get-started/frameworks/vite
- freeCodeCamp.org
