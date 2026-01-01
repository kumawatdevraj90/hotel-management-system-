# Hotel-management-system

A modern web application for creating and managing builder projects. This full-stack application includes a React-based frontend and a Node.js backend.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Configuration](#configuration)
- [Contributing](#contributing)

## ✨ Features

- **Project Management**: Create, view, and manage builder projects
- **Admin Dashboard**: Comprehensive admin panel for project oversight
- **Payment Integration**: Integrated payment processing
- **Responsive Design**: Mobile-friendly interface with Tailwind CSS
- **UI Components**: Rich component library with shadcn/ui
- **Modern Frontend**: Built with React and TypeScript
- **RESTful API**: Backend API with Express.js

## 🛠️ Tech Stack

### Frontend
- **React** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - High-quality React components
- **ESLint** - Code quality
- **pnpm** - Package manager

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **Render** - Deployment platform

## 📁 Project Structure

```
buildpro-website/
├── Frontend/                 # React frontend application
│   ├── src/
│   │   ├── components/       # React components
│   │   │   ├── HomeCard.tsx
│   │   │   ├── ProjectCard.tsx
│   │   │   └── ui/          # shadcn UI components
│   │   ├── pages/           # Page components
│   │   │   ├── Admin.tsx
│   │   │   ├── Builder.tsx
│   │   │   ├── HomeDetail.tsx
│   │   │   ├── Index.tsx
│   │   │   ├── NotFound.tsx
│   │   │   ├── Payment.tsx
│   │   │   ├── ProjectDetails.tsx
│   │   │   └── projects.tsx
│   │   ├── hooks/           # Custom React hooks
│   │   ├── lib/             # Utility functions
│   │   ├── main.tsx         # Entry point
│   │   └── App.tsx          # Root component
│   ├── package.json
│   ├── vite.config.ts
│   ├── tsconfig.json
│   └── tailwind.config.ts
├── backend/                  # Node.js backend
│   ├── server.js            # Main server file
│   └── package.json
└── render.yaml              # Deployment configuration

```

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or pnpm package manager

### Backend Setup

```bash
cd backend
npm install
# or
pnpm install
```

### Frontend Setup

```bash
cd Frontend
npm install
# or
pnpm install
```

## 🚀 Running the Application

### Development Mode

#### Backend
```bash
cd backend
npm start
# or
npm run dev
```

#### Frontend
```bash
cd Frontend
npm run dev
```

The frontend will typically run on `http://localhost:5173`

### Production Build

#### Frontend
```bash
cd Frontend
npm run build
```

This creates an optimized build in the `dist` folder.

## ⚙️ Configuration

### Frontend Configuration
- **Vite Config**: [vite.config.ts](Frontend/vite.config.ts)
- **Tailwind CSS**: [tailwind.config.ts](Frontend/tailwind.config.ts)
- **TypeScript**: [tsconfig.json](Frontend/tsconfig.json)
- **ESLint**: [eslint.config.js](Frontend/eslint.config.js)

### Backend Configuration
- **Server**: [server.js](backend/server.js)
- **Dependencies**: [package.json](backend/package.json)

### Deployment
The project uses Render for deployment. Configuration is defined in [render.yaml](render.yaml).

## 📝 Pages

- **Home (Index)**: Landing page with project overview
- **Builder**: Main builder interface for creating projects
- **Projects**: List of all projects
- **Project Details**: Detailed view of a specific project
- **Home Detail**: Detailed home information page
- **Admin**: Administrative dashboard
- **Payment**: Payment processing page
- **Not Found**: 404 error page

## 🧩 Components

### Core Components
- `HomeCard`: Component for displaying home information
- `ProjectCard`: Component for displaying project information

### UI Components
The project includes a comprehensive set of shadcn/ui components including:
- Button, Input, Card, Dialog, Sidebar
- Accordion, Tabs, Toggle, Dropdown Menu
- Form controls, Tables, Alerts, and more

## 🤝 Contributing

1. Create a new branch for your feature
2. Commit your changes with clear messages
3. Push to your branch
4. Create a Pull Request

## 📄 License

This project is part of a college project.

---

**Happy Building! 🏗️**
