# Jeans Project

This repository contains a full-stack e-commerce application for jeans, separated into three parts:

- `backend/` — Node.js + Express API with MongoDB, authentication, product, cart, and order routes.
- `frontend/` — Customer-facing React + Vite storefront.
- `admin/` — Admin dashboard React + Vite app for managing products, orders, and users.

## Getting Started

Each folder is a separate app. Install dependencies and run them independently.

### Backend

```powershell
cd backend
npm install
npm run dev
```

The backend uses:

- `express`
- `mongoose`
- `jsonwebtoken`
- `bcryptjs`
- `cloudinary`
- `multer`
- `cors`

### Frontend

```powershell
cd frontend
npm install
npm run dev
```

### Admin

```powershell
cd admin
npm install
npm run dev
```

## Build

For production builds:

```powershell
cd frontend
npm run build

cd ../admin
npm run build
```

## Notes

- Make sure the backend server is running before using the frontend or admin apps.
- Configure any required environment variables in the backend before starting the API.
- The frontend and admin apps are built with Vite and React.

## Repository Structure

- `admin/` — admin dashboard app
- `backend/` — API server
- `frontend/` — public storefront
