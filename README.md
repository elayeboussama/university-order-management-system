# University Order Management System

An order-management web application for a university, built with **React + TypeScript (Vite)** and **Supabase** (PostgreSQL) as the backend.

## Tech stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend:** Supabase (PostgreSQL, auth, storage)

## Getting started

### Prerequisites

- Node.js 18+
- A [Supabase](https://supabase.com/) project

### Setup

```bash
npm install
cp .env.example .env   # set VITE_SUPABASE_URL and VITE_SUPABASE_ANON_KEY
npm run dev            # http://localhost:5173
```

### Build

```bash
npm run build
npm run preview
```

## Project structure

```
src/        React + TypeScript application
supabase/   Database schema / Supabase configuration
```
