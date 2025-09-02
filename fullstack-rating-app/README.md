# FullStack Rating App

This is a full-stack web application built with:

- **Backend**: NestJS + TypeORM + MySQL + JWT (Role-based Access)
- **Frontend**: React + Vite + React Router + Axios
- **Database**: MySQL

## Features
- User roles: **Admin, Normal User, Store Owner**
- Admin can manage users, stores, and see dashboard stats
- Normal user can register/login, search stores, submit/modify ratings
- Store owner can view ratings of their store and average rating
- Validations on fields (name, email, address, password)

## Run locally

### Database
```bash
mysql -u root -p < database/schema.sql
mysql -u root -p < database/seed.sql
```

### Backend
```bash
cd backend
cp .env.example .env
npm install
npm run start:dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```
