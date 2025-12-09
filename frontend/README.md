# WeBet360 Frontend

User-facing web application for the WeBet360 sports betting platform, built with React and TypeScript.

## 📋 Prerequisites

- **Node.js**: Version 16.x or 18.x
- **npm** or **yarn**: Package manager (Yarn recommended)

## 🚀 Installation

### Using Yarn (Recommended)

```bash
yarn install
```

### Using NPM

```bash
npm install
# or if you encounter peer dependency issues
npm install --legacy-peer-deps
```

## 💻 Development

### Start Development Server

```bash
yarn start
# or
npm start
```

The development server will start on `http://localhost:3000` (or the next available port).

### Build for Production

```bash
yarn build
# or
npm run build
```

This creates an optimized production build in the `build/` directory.

### Windows Build

For Windows systems:

```bash
yarn winBuild
# or
npm run winBuild
```

## 📜 Available Scripts

- `yarn start` - Start development server
- `yarn build` - Build for production
- `yarn winBuild` - Build for production (Windows)
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors automatically
- `yarn prettier` - Format code with Prettier
- `yarn clear-all` - Remove all build artifacts and dependencies
- `yarn re-start` - Clean, reinstall, and start development server
- `yarn re-build` - Clean, reinstall, and build for production

## 🛠 Technology Stack

- **Framework**: React 18.2.0
- **Language**: TypeScript
- **UI Library**: Material-UI (MUI)
- **State Management**: Redux Toolkit
- **Routing**: React Router
- **HTTP Client**: Axios
- **Real-time**: Socket.io Client
- **Internationalization**: i18next
- **Styling**: Emotion, SCSS
- **Form Handling**: React Hook Form, Yup

## 🎨 Features

- Responsive design for all devices
- Multi-language support (i18n)
- Real-time updates via WebSocket
- Modern UI with Material-UI components
- Form validation
- Image lazy loading
- Toast notifications
- Progress indicators

## 📝 Notes

- The application requires the backend API to be running
- Environment variables can be configured in `.env` files
- Source maps are disabled in production builds for security
- The build process optimizes assets and code splitting automatically
