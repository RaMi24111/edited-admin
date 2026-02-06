# Restaurant Management System - Frontend Only Standalone Demo

This is a **FRONTEND-ONLY** Next.js + TypeScript project. It is fully standalone and does **NOT** require a backend or database to run. All navigation, admin login, and data operations are simulated on the client side.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:3000`

## 🕹️ Simulated Features

This project features a complete frontend-only flow:

- **Landing Page**: Entry point with navigation to Admin Login.
- **Admin Login**: Mock authentication flow (use any credentials).
- **Admin Dashboard**:
    - **Menu Management**: Add, edit, and delete items with mock state.
    - **Staff Management**: Role-based staff lists with simulated CRUD.
    - **Table Details**: Table layout management and QR code generation.
    - **Order History**: Date-based order filtering with mock data.

## 📁 Project Structure

```
frontend-admin/
├── app/              # Standalone pages (dashboard, login, etc.)
├── components/       # UI components and layout
├── public/           # Static assets and images
└── config files      # TypeScript, Tailwind, and Next.js configs
```

## 🎨 Tech Stack

- **Next.js 16** (App Router)
- **TypeScript 5**
- **React 19**
- **Tailwind CSS 4**
- **Framer Motion** (Animations)
- **Lucide React** (Icons)

## 📝 Note

This project is optimized for UI/UX demonstration and does not persist data to a database. Refreshing the browser will reset the mock local state.

