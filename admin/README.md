# WeBet360 Admin Dashboard

Administrative dashboard for managing the WeBet360 sports betting platform, built with React and TypeScript.

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

## 📜 Available Scripts

- `yarn start` - Start development server
- `yarn build` - Build for production
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
- **Charts**: ApexCharts
- **Styling**: Emotion, Styled Components, SCSS
- **Form Handling**: React Hook Form, Yup

## 🎨 Features

- Comprehensive admin dashboard
- User management
- Platform configuration
- Analytics and reporting
- Real-time monitoring
- Data visualization with charts
- File management
- Multi-language support

## 📝 Notes

- The admin dashboard requires the backend API to be running
- Admin authentication is required to access the dashboard
- Environment variables can be configured in `.env` files
- The build process optimizes assets and code splitting automatically
