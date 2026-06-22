# Askloom Kanban

A real-time collaborative Kanban project management platform built with Next.js, Supabase, and PostgreSQL. The application enables teams to organize tasks, track project progress, and collaborate efficiently through interactive Kanban boards.

## Features

* Real-time collaborative Kanban boards
* User authentication and authorization using Supabase Auth
* Drag-and-drop task management
* Workspace and board management
* Task labels and status tracking
* Responsive user interface
* Dark and Light theme support
* Optimistic state management using Zustand
* Real-time synchronization across users

## Tech Stack

### Frontend

* Next.js 15
* TypeScript
* Tailwind CSS
* Framer Motion
* shadcn/ui

### Backend & Database

* Supabase
* PostgreSQL

### State Management & Validation

* Zustand
* React Hook Form
* Zod

### Authentication

* Supabase Auth

## Project Structure

```text
app/            → Application routes and pages
components/     → Reusable UI components
lib/            → Utilities, validation, and Supabase clients
store/          → Zustand state management
supabase/       → Database schema and SQL scripts
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Askloom-Kanban-Platform.git
cd Askloom-Kanban-Platform
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Supabase

Create a Supabase project and execute the SQL script located in:

```text
supabase/schema.sql
```

### 4. Configure Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

### 5. Run the Application

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

## Deployment

Deploy using Vercel and configure the same environment variables.

Add the following Supabase redirect URLs:

```text
http://localhost:3000/auth/callback
https://your-domain.com/auth/callback
```

## Key Functionalities

* Create and manage workspaces
* Create boards and columns
* Drag and drop tasks between columns
* Real-time updates across users
* Secure authentication and authorization
* Analytics and productivity tracking

## Future Enhancements

* Team collaboration and mentions
* File attachments
* Calendar integration
* AI-powered task prioritization
* Advanced reporting and analytics

## Author

**Priya Dharshini**
