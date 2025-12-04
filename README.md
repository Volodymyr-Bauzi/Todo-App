# Todo App

A modern, feature-rich todo application built with React and TypeScript. This application allows users to manage their daily tasks with an intuitive interface, featuring real-time updates, filtering options, and persistent storage.

## 🚀 Live Preview

[View Live Demo](https://volodymyr-bauzi.github.io/Todo-App/)

## 🎨 Design Reference

This project follows the classic TodoMVC design pattern with modern enhancements, providing a clean and minimalist user interface for efficient task management.

## 🛠️ Technologies Used

### Core Technologies
- **React 18.3.1** - A JavaScript library for building user interfaces
- **TypeScript 5.2.2** - Typed superset of JavaScript for better code quality
- **Vite 5.3.1** - Next-generation frontend build tool for faster development

### Styling & UI
- **Bulma 1.0.1** - Modern CSS framework for responsive design
- **SCSS/Sass 1.77.8** - CSS preprocessor for enhanced styling capabilities
- **Font Awesome 6.5.2** - Icon library for beautiful UI elements

### Routing & Navigation
- **React Router DOM 6.25.1** - Declarative routing for React applications

### Additional Libraries
- **classnames 2.5.1** - Utility for conditionally joining classNames
- **react-transition-group 4.4.5** - Animation library for React components

### Development Tools
- **ESLint** - Code linting and quality assurance
- **Prettier** - Code formatting
- **Stylelint** - CSS/SCSS linting
- **Cypress 13.13.0** - End-to-end testing framework

## 📋 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (version 18.3.1)
- **npm** (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Volodymyr-Bauzi/Todo-App.git
   cd Todo-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or 
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   # or 
   yarn start
   ```

4. **Open your browser**
   
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

### Building for Production

To create a production-ready build:

```bash
npm run build
# or 
yarn build
```

The optimized files will be generated in the `dist` folder.

### Deployment

Deploy your application to GitHub Pages:

```bash
npm run deploy
# or 
yarn deploy
```

## ✨ Features

### Core Functionality
- ✅ **Add Todos** - Create new tasks with a simple input field
- ✅ **Delete Todos** - Remove individual tasks or clear all completed tasks at once
- ✅ **Edit Todos** - Double-click on any task to edit its title
- ✅ **Toggle Completion** - Mark tasks as complete or incomplete with a single click
- ✅ **Toggle All** - Complete or uncomplete all tasks simultaneously

### Filtering & Organization
- 🔍 **Smart Filters** - View all tasks, only active tasks, or only completed tasks
- 📊 **Active Counter** - See how many tasks remain to be completed
- 🗑️ **Bulk Actions** - Clear all completed todos with one click

### User Experience
- 💾 **Persistent Storage** - Tasks are saved and persist across sessions
- ⚡ **Real-time Updates** - Instant feedback on all actions
- 🎨 **Smooth Animations** - Polished transitions for better UX
- ⚠️ **Error Handling** - Clear error messages with auto-dismiss notifications
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices

### Technical Features
- 🔄 **Custom Hooks** - Modular code organization with reusable hooks
- 🎯 **TypeScript** - Type-safe code for fewer runtime errors
- 🧪 **Testing Ready** - Configured with Cypress for E2E testing
- 📝 **Code Quality** - ESLint, Prettier, and Stylelint for consistent code style

## 📁 Project Structure

```
Todo-App/
├── src/
│   ├── api/              # API integration and data fetching
│   ├── components/       # React components
│   ├── hooks/            # Custom React hooks
│   ├── styles/           # SCSS stylesheets
│   ├── types/            # TypeScript type definitions
│   ├── utils/            # Utility functions
│   ├── App.tsx           # Main application component
│   └── index.tsx         # Application entry point
├── public/               # Static assets
├── dist/                 # Production build output
└── package.json          # Project dependencies and scripts

```

## 🧑‍💻 Available Scripts

- `npm start` - Start development server with live reload
- `npm run build` - Build for production
- `npm run lint` - Run all linters (JS, CSS, formatting)
- `npm run format` - Format code with Prettier
- `npm run lint-js` - Lint JavaScript/TypeScript files
- `npm run lint-css` - Lint SCSS files
- `npm run style-format` - Auto-fix SCSS formatting issues
- `npm run deploy` - Deploy to GitHub Pages

⭐ If you found this project helpful, please give it a star!
