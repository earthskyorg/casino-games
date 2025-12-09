# WeBet360 Backend API

Backend API server for the WeBet360 sports betting platform, built with Node.js, Express, and TypeScript.

## 📋 Prerequisites

- **Node.js**: Version 16.18.1 or higher (16.x or 18.x recommended)
- **MongoDB**: Database server
- **npm** or **yarn**: Package manager

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

## 🔧 Configuration

1. Copy the example environment file:
   ```bash
   cp example.env .env
   ```

2. Configure your environment variables in `.env`:
   - Database connection strings
   - JWT secrets
   - API keys
   - Payment gateway configurations
   - Email service credentials

## 💻 Development

### Start Development Server

```bash
yarn dev
# or
npm run dev
```

The development server runs with hot reload using `nodemon` and `ts-node`.

### Build for Production

```bash
yarn build
# or
npm run build
```

This compiles TypeScript to JavaScript in the `dist/` directory.

### Start Production Server

```bash
yarn start
# or
npm start
```

## 📜 Available Scripts

- `yarn dev` - Start development server with hot reload
- `yarn build` - Build TypeScript to JavaScript
- `yarn start` - Start production server
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors automatically
- `yarn initial` - Run initialization script (development)
- `yarn clean` - Remove build directory

### Additional Worker Scripts

- `yarn matchs1`, `yarn matchs2`, `yarn matchs3` - Match processing workers
- `yarn odds1`, `yarn odds2`, `yarn odds3` - Odds processing workers
- `yarn ends1`, `yarn ends2`, `yarn ends3` - Match ending workers
- `yarn image` - Image processing worker
- `yarn results` - Results processing worker

## 🛠 Technology Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Language**: TypeScript
- **Database**: MongoDB (Mongoose)
- **Real-time**: Socket.io
- **Security**: Helmet, express-rate-limit
- **Validation**: Joi
- **Documentation**: Swagger

## 📡 API Documentation

API documentation is available via Swagger UI when the server is running. Access it at:
```
http://localhost:<PORT>/api-docs
```

## 🔐 Security Features

- Rate limiting
- Helmet security headers
- CORS configuration
- Request validation
- Authentication middleware
- Session management

## 📝 Notes

- Ensure MongoDB is running before starting the server
- The server supports cluster mode for production (set `CLUSTER` environment variable)
- Access logs are written to `log/access.log`
- File uploads are stored in the configured upload directory
