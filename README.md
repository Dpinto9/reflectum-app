# Reflectum – Notion-Style Workspace

A full-stack Notion-inspired workspace built with Next.js and React, styled with Tailwind CSS, and powered by modern tools like Clerk, Convex, Edge Store, and BlockNote.

This project focuses on real-time collaboration, rich text editing, and a clean, responsive user experience.

## Landing page

<img width="2553" height="1289" alt="landing page" src="https://github.com/user-attachments/assets/86b3f23e-a188-4c33-8cdc-921252a90df8" />

## Editor

<img width="2547" height="1302" alt="document page" src="https://github.com/user-attachments/assets/25cd63cf-afec-4f3e-8cf8-de915f177ba9" />


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
