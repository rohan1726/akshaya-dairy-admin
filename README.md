# Akshaya Dairy – Admin Panel

React + Vite admin panel for Akshaya Dairy Management System.

## Run locally

1. **Backend must be running** at <http://localhost:3000> (see backend repo).
2. **Run admin**
   ```bash
   npm install
   npm run dev
   ```
   Opens at <http://localhost:3001>. API calls go to backend via Vite proxy (`/api`).

## Deploy to Vercel

1. Import this repo in Vercel (Root Directory: leave empty).
2. **Environment variable:** `VITE_API_URL` = your backend API URL (no trailing slash), e.g. `https://your-backend.vercel.app`
3. Deploy.

## Default login

After seeding the backend: mobile `9999999999`, password `admin123`.
