# React + TypeScript + Vite Dev Container Template

A production-ready development environment for React applications using TypeScript and Vite, fully configured to run in a VS Code dev container.

## Features

- ⚡️ **Vite** - Fast build tool and dev server
- ⚛️ **React 18** - Modern React with hooks
- 🔷 **TypeScript** - Type safety and better DX
- 🐳 **Dev Container** - Consistent development environment
- 🎨 **ESLint + Prettier** - Code quality and formatting
- 🔧 **VS Code Extensions** - Pre-configured essential extensions

## Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## Getting Started

### Using This Template

1. Click "Use this template" button on GitHub
2. Clone your new repository
3. Open the folder in VS Code
4. When prompted, click "Reopen in Container"
5. Wait for the container to build and dependencies to install
6. Start developing!

### Manual Setup

1. Clone the repository
2. Open in VS Code
3. Press `F1` and select "Dev Containers: Reopen in Container"
4. The container will build and install dependencies automatically

## Available Scripts
```bash
npm run dev          # Start development server (http://localhost:5173)
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
npm run lint:fix     # Fix ESLint issues
```

## Development

The dev server runs on port 5173 and is automatically forwarded by the dev container.

Changes to files in `src/` will trigger hot module replacement (HMR).

## Project Structure

```
.
├── .devcontainer/       # Dev container configuration
├── .vscode/             # VS Code settings and extensions
├── public/              # Static assets
├── src/                 # Application source code
│   ├── assets/          # Images, fonts, etc.
│   ├── App.tsx          # Main App component
│   └── main.tsx         # Application entry point
├── index.html           # HTML entry point
├── package.json         # Dependencies and scripts
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite configuration
```

## Included VS Code Extensions

- ESLint
- Prettier
- Tailwind CSS IntelliSense
- ES7+ React/Redux/React-Native snippets
- TypeScript
- Path Intellisense
- Auto Rename Tag
- Error Lens

## Customization

### Adding Dependencies

```bash
npm install <package-name>
```

### Modifying Dev Container

Edit `.devcontainer/devcontainer.json` to:
- Add more VS Code extensions
- Change Node.js version
- Add additional features
- Modify port forwarding
