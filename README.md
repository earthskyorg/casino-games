# WeBet360 - Sports Betting Platform

A comprehensive sports betting platform built with modern web technologies, featuring a robust backend API, user-facing frontend, and administrative dashboard.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Development](#development)
- [Technology Stack](#technology-stack)
- [Environment Variables](#environment-variables)
- [Scripts](#scripts)
- [License](#license)

## 🎯 Overview

WeBet360 is a full-stack sports betting platform that provides users with a seamless betting experience. The platform consists of three main components:

- **Backend**: RESTful API server built with Node.js, Express, and TypeScript
- **Frontend**: User-facing web application built with React and TypeScript
- **Admin**: Administrative dashboard for platform management

## ✨ Features

- **Sports Betting**: Comprehensive sports betting functionality with real-time odds
- **User Management**: Complete user authentication and profile management
- **Payment Integration**: Support for multiple payment methods including cryptocurrency
- **Real-time Updates**: WebSocket integration for live updates and notifications
- **Admin Dashboard**: Comprehensive administrative tools for platform management
- **Multi-language Support**: Internationalization support for multiple languages
- **Responsive Design**: Mobile-first responsive design for all devices
- **Security**: Rate limiting, helmet security, and comprehensive authentication

## 📁 Project Structure

```
betting/
├── backend/          # Backend API server (Node.js/Express/TypeScript)
├── frontend/         # User-facing web application (React/TypeScript)
├── admin/            # Administrative dashboard (React/TypeScript)
├── upload/           # File uploads directory
└── webet-db-backup/  # Database backup files
```

## 🔧 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: Version 16.18.1 or higher (16.x or 18.x recommended)
- **npm**: Comes with Node.js, or
- **yarn**: Package manager (recommended)
- **MongoDB**: Database server
- **Git**: Version control system

## 🚀 Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd betting
```

### 2. Install dependencies

Install dependencies for each component:

#### Backend
```bash
cd backend
yarn install
# or
npm install
```

#### Frontend
```bash
cd frontend
yarn install
# or
npm install --legacy-peer-deps
```

#### Admin
```bash
cd admin
yarn install
# or
npm install --legacy-peer-deps
```

### 3. Environment Configuration

Copy the example environment file and configure your variables:

```bash
cd backend
cp example.env .env
```

Edit `.env` with your configuration (database connection, API keys, etc.).

## 💻 Development

### Backend Development

```bash
cd backend

# Development mode with hot reload
yarn dev
# or
npm run dev

# Build for production
yarn build
# or
npm run build

# Start production server
yarn start
# or
npm start
```

### Frontend Development

```bash
cd frontend

# Start development server
yarn start
# or
npm start

# Build for production
yarn build
# or
npm run build
```

### Admin Development

```bash
cd admin

# Start development server
yarn start
# or
npm start

# Build for production
yarn build
# or
npm run build
```

## 🛠 Technology Stack

### Backend
- **Runtime**: Node.js 16.18.1+
- **Framework**: Express.js
- **Language**: TypeScript
- **Database**: MongoDB (Mongoose ODM)
- **Real-time**: Socket.io
- **Security**: Helmet, express-rate-limit, bcrypt
- **Validation**: Joi
- **Documentation**: Swagger

### Frontend & Admin
- **Framework**: React 18.2.0
- **Language**: TypeScript
- **UI Library**: Material-UI (MUI)
- **State Management**: Redux Toolkit
- **Routing**: React Router
- **HTTP Client**: Axios
- **Real-time**: Socket.io Client
- **Internationalization**: i18next
- **Styling**: Emotion, SCSS

## 🔐 Environment Variables

The backend requires environment variables to be configured. See `backend/example.env` for a complete list of required variables. Key variables include:

- Database connection strings
- JWT secrets
- API keys for third-party services
- Payment gateway configurations
- Email service credentials
- Socket.io settings

## 📜 Scripts

### Backend Scripts
- `yarn dev` - Start development server with hot reload
- `yarn build` - Build TypeScript to JavaScript
- `yarn start` - Start production server
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors

### Frontend/Admin Scripts
- `yarn start` - Start development server
- `yarn build` - Build for production
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors
- `yarn prettier` - Format code with Prettier

## 📄 License

ISC

---

For more information about each component, refer to their respective README files:
- [Backend README](./backend/README.md)
- [Frontend README](./frontend/README.md)
- [Admin README](./admin/README.md)
