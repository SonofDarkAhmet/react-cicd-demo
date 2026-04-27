# React CI/CD Demo

A beginner-friendly project demonstrating CI/CD best practices using **GitHub Actions**, **React**, **Vite**, and **SonarCloud**.

## Project Overview

This is a React application that showcases automated testing, code quality analysis, and continuous deployment workflows. The project includes:

- React components with unit tests
- Automated testing with Vitest
- Code quality analysis with SonarCloud
- CI/CD pipelines using GitHub Actions
- Automatic deployment to GitHub Pages

## Technology Stack

- **React** - UI library
- **Vite** - Build tool with fast Hot Module Replacement (HMR)
- **Vitest** - Unit testing framework
- **React Testing Library** - Component testing utilities
- **GitHub Actions** - CI/CD automation
- **SonarCloud** - Code quality and security analysis

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install
```

### Development

```bash
# Start the development server
npm run dev
```

The application will be available at `http://localhost:5173` with HMR enabled.

### Build

```bash
# Build for production
npm run build
```

### Testing

```bash
# Run unit tests
npm run test
```

## Project Structure

```
src/
├── App.jsx           # Main React component
├── App.css           # Component styles
├── App.test.jsx      # Unit tests
├── index.css         # Global styles
├── main.jsx          # Application entry point
└── assets/           # Static assets
```

## CI/CD Pipeline

This project uses GitHub Actions for automated testing and deployment:

- **Test**: Runs unit tests on every push and pull request
- **Code Quality**: Analyzes code with SonarCloud
- **Deploy**: Automatically deploys to GitHub Pages on main branch updates

## SonarCloud Integration

Code quality metrics are tracked through SonarCloud. Configuration is defined in `sonar-project.properties`.

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run test` - Run unit tests
- `npm run preview` - Preview production build locally
