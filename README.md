# Reflectum – Notion-Style Workspace

A full-stack Notion-inspired workspace built with Next.js and React, styled with Tailwind CSS, and powered by modern tools like Clerk, Convex, Edge Store, and BlockNote.

This project focuses on real-time collaboration, rich text editing, and a clean, responsive user experience.

## Landing page

![Screenshot 1]()

## Editor

![Screenshot 2]()

## Features

- User authentication and session management with Clerk
- Real-time data handling and backend logic powered by Convex
- Image upload and storage integration via Edge Store
- Rich text note creation and editing using the BlockNote editor
- Support for nested notes and hierarchical page structures
- Options to archive, restore, or permanently remove notes
- Public note publishing and shareable pages
- Resizable and collapsible sidebar navigation
- Fully responsive interface with light and dark themes built using Tailwind CSS and shadcn/ui

## Getting Started

### Clone the repo

```bash
git clone https://github.com/Dpinto9/reflectum-app.git
```

### Install dependencies

```bash
npm install
```

### Setup .env file

```env
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Start Convex

```bash
npx convex dev
```

### Start the app

```bash
npm run dev
```

### Credit

Created by following along with [AntonioErdeljac/notion-clone-tutorial](https://github.com/AntonioErdeljac/notion-clone-tutorial).
