# Helixora — Smart School Management System

Helixora is a modern full-stack School Management System built using Next.js, Prisma, PostgreSQL, and Supabase.
The project is designed to manage school operations digitally with role-based dashboards for Admins, Teachers, Students, and Parents.

The system includes both:

* Public School Website
* Secure School ERP Dashboard

---

# Features

## Public Website

* Home Page
* About School
* Admissions
* Courses / Classes
* Teachers
* Gallery
* Events & Notices
* Contact Page

---

## Admin Dashboard

* Student Management
* Teacher Management
* Attendance Management
* Results Management
* Notices & Announcements
* Dashboard Analytics
* Role-based Access Control

---

## Teacher Panel

* Upload Student Marks
* Take Attendance
* Manage Homework
* Student Performance Tracking

---

## Student Panel

* View Attendance
* View Results
* Timetable Access
* Homework & Notifications

---

## Parent Panel

* Child Performance Tracking
* Attendance Reports
* Fee Status Monitoring

---

# Tech Stack

## Frontend

* Next.js 16
* React
* TypeScript
* Tailwind CSS

---

## Backend

* Next.js API Routes
* Prisma ORM
* PostgreSQL

---

## Database & Cloud

* Supabase PostgreSQL

---

## Package Manager

* pnpm

---

# Project Structure

```bash
helixora/
│
├── app/
│   ├── api/
│   ├── dashboard/
│   ├── (public)/
│
├── components/
│
├── lib/
│   ├── prisma.ts
│
├── prisma/
│   ├── schema.prisma
│
├── public/
│
├── types/
│
├── hooks/
│
├── .env
│
├── prisma.config.ts
│
└── package.json
```

# Database Models

* User
* Student
* Teacher
* Attendance
* Result

---

# Getting Started

## Clone Repository

```bash
git clone https://github.com/isushilkushwaha/helixora.git
```

## Move Into Project

```bash
cd helixora
```

## Install Dependencies

```bash
pnpm install
```

---

# Environment Variables

Create a `.env` file in the root directory.

```env
DATABASE_URL="YOUR_DATABASE_URL"
```

---

# Prisma Setup

Generate Prisma Client:

```bash
pnpm prisma generate
```

Push Schema to Database:

```bash
pnpm prisma db push
```

---

# Run Development Server

```bash
pnpm dev
```

Open:

```bash
http://localhost:3000
```

---

# API Test Route

Test database connection:

```bash
http://localhost:3000/api/test
```

---

# Current Development Status

* Database setup completed
* Prisma ORM configured
* Supabase PostgreSQL connected
* API routes working
* Authentication module in progress
* Dashboard development in progress

---

# Future Improvements

* AI Attendance Summary
* AI Report Card Comments
* Real-time Notifications
* PDF Export
* Analytics Dashboard
* Fee Payment Integration
* Parent Communication System

---

# Deployment

## Frontend

* Vercel

## Database

* Supabase

---

# Author

Sushil Kushwaha

GitHub:
https://github.com/isushilkushwaha

---

# License

This project is developed for learning, portfolio, and production-level SaaS development purposes.
