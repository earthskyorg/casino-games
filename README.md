# ShinyBet - Sports Betting & Casino Platform

A comprehensive online sports betting and casino platform built with React and Node.js, featuring casino games, sports betting, live casino, user management, and comprehensive administrative tools.

## 👋 Cᴏɴᴛᴀᴄᴛ ᴍᴇ Oɴ ʜᴇʀᴇ ##

Telegram: https://t.me/opensea712

<div style={{display : flex ; justify-content : space-evenly}}> 
    <a href="https://t.me/opensea712" target="_blank"><img alt="Telegram"
        src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
    <a href="https://discordapp.com/users/343286332446998530" target="_blank"><img alt="Discord"
        src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>
</div>

## 🎯 Overview

ShinyBet is a full-stack sports betting and casino platform that provides users with a seamless gaming and betting experience. The platform consists of three main components working together to deliver a complete solution:

- **Backend**: RESTful API server built with Node.js, Express, and TypeScript
- **Frontend**: User-facing web application built with React and TypeScript
- **Admin**: Comprehensive administrative dashboard for platform management

## 🎰 Features

### Casino Games

- **Slots** - Extensive collection of slot machine games from top providers
- **Blackjack** - Classic card game with multiple variants
- **Roulette** - European and American roulette variants
- **Baccarat** - Traditional baccarat games
- **Poker** - Various poker game formats
- **Video Poker** - Electronic poker games
- **Live Casino** - Real-time casino games with live dealers
- **Game Shows** - Interactive game show experiences
- **Table Games** - Classic table game collection
- **Fast Games** - Quick-play gaming options
- **Crash Games** - High-energy crash gaming
- **Dice Games** - Various dice-based games
- **Andar Bahar** - Traditional Indian card game
- **Dragon Tiger** - Fast-paced card game
- **Virtual Games** - Simulated sports and racing games
- **Original Games** - Exclusive platform games
- **Top Games** - Curated selection of popular games
- **Jackpot Games** - Progressive jackpot opportunities
- **Tournaments** - Competitive gaming tournaments
- **Leaderboard** - Player rankings and achievements

### Sports Betting

- **Live Betting** - Real-time sports betting opportunities
- **Sports Markets** - Comprehensive sports betting markets
- **Match Details** - Detailed match information and statistics
- **Favorites** - Save and track favorite teams and matches
- **My Bets** - Track and manage your betting history
- **Sports History** - Complete betting history and analytics

### User Features

- **Wallet Management** - Comprehensive wallet and balance management
- **Account Settings** - Complete user profile and account management
- **Notifications** - Real-time notifications and alerts
- **Referral Program** - User referral and rewards system
- **Support System** - Integrated customer support with tickets
- **Live Chat** - Real-time chat functionality
- **Promotions** - Access to bonuses and promotional offers
- **Journey** - User progression and gamification
- **Blog** - Platform news and updates
- **FAQ** - Frequently asked questions

### Administrative Features

- **Dashboard** - Comprehensive analytics and overview
- **User Management** - Complete user administration and monitoring
- **Client & Agent Management** - Multi-tier user system management
- **Casino Management** - Game provider and game list management
- **Sports Management** - Sports leagues, matches, and betting management
- **Payment Management** - Currency, balance, and payment history management
- **Marketing Tools** - Email/SMS campaigns, popups, and marketing history
- **Chat Management** - Chat room moderation and user management
- **Ticket System** - Customer support ticket management
- **Bonus Management** - Common bonuses, event bonuses, and tier systems
- **Missions & Gamification** - Badges, levels, points, stores, and minigames
- **Settings** - Banners, notifications, spin wheels, blogs, and platform configuration
- **Segmentation** - User segmentation and targeting
- **Original Games** - Custom game management

## 🛠️ Tech Stack

### Backend

- **Runtime**: Node.js 16.18.1+
- **Framework**: Express.js 4.18.1
- **Language**: TypeScript 4.7.2
- **Database**: MongoDB 6.3.5 (Mongoose ODM)
- **Real-time**: Socket.io 4.5.1
- **Security**: 
  - Helmet 5.1.0
  - express-rate-limit 6.4.0
  - bcrypt-nodejs 0.0.3
- **Validation**: Joi 17.6.0
- **Documentation**: Swagger (swagger-jsdoc, swagger-ui-express)
- **Payment Integration**: 
  - CoinPayments 2.2.0
  - Web3 1.7.3 (Ethereum/Solana support)
- **Email**: SendGrid 7.7.0, Nodemailer 6.7.5
- **SMS**: Twilio 5.3.0
- **File Upload**: Multer 1.4.5
- **Logging**: Morgan 1.10.0, rotating-file-stream 3.0.4

### Frontend & Admin

- **Framework**: React 18.2.0
- **Language**: TypeScript 5.2.2
- **UI Library**: Material-UI (MUI) 5.14.7
- **State Management**: Redux Toolkit 2.2.3
- **Routing**: React Router DOM 6.15.0
- **HTTP Client**: Axios 1.5.0
- **Real-time**: Socket.io Client 4.7.5
- **Internationalization**: 
  - i18next 23.4.6
  - react-i18next 13.2.1
- **Styling**: 
  - Emotion (React/Styled) 11.11.0
  - SCSS 1.77.2
  - Styled Components 6.1.16 (Admin)
- **Form Handling**: 
  - React Hook Form 7.45.4
  - Yup 1.2.0
- **Charts**: ApexCharts 4.5.0 (Admin)
- **Date Handling**: 
  - dayjs 1.11.11
  - date-fns 2.30.0
  - moment 2.30.1
- **Build Tool**: Create React App 5.0.1

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: Version 16.18.1 or higher (16.x or 18.x recommended)
- **MongoDB**: Database server (local or remote)
- **npm** or **yarn**: Package manager (Yarn recommended)
- **Git**: Version control system

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd betting
   ```

2. **Install Backend Dependencies**

   ```bash
   cd backend
   yarn install
   # or
   npm install
   ```

3. **Install Frontend Dependencies**

   ```bash
   cd ../frontend
   yarn install
   # or
   npm install --legacy-peer-deps
   ```

4. **Install Admin Dependencies**

   ```bash
   cd ../admin
   yarn install
   # or
   npm install --legacy-peer-deps
   ```

5. **Environment Configuration**

   ```bash
   cd ../backend
   cp example.env .env
   ```

   Edit `.env` with your configuration:
   - Database connection strings
   - JWT secrets
   - API keys for third-party services
   - Payment gateway configurations
   - Email service credentials
   - Socket.io settings

6. **Start the Development Servers**

   **Backend:**
   ```bash
   cd backend
   yarn dev
   # or
   npm run dev
   ```

   **Frontend:**
   ```bash
   cd frontend
   yarn start
   # or
   npm start
   ```

   **Admin:**
   ```bash
   cd admin
   yarn start
   # or
   npm start
   ```

7. **Open your browser**

   - Frontend: Navigate to [http://localhost:3000](http://localhost:3000)
   - Admin: Navigate to [http://localhost:3001](http://localhost:3001) (or next available port)
   - Backend API: Available at the configured port (default varies)
   - API Documentation: Available at `http://localhost:<PORT>/api-docs`

## 📜 Available Scripts

### Backend Scripts

- `yarn dev` - Start development server with hot reload
- `yarn build` - Build TypeScript to JavaScript
- `yarn start` - Start production server
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors automatically
- `yarn initial` - Run initialization script (development)
- `yarn clean` - Remove build directory

**Worker Scripts:**
- `yarn matchs1`, `yarn matchs2`, `yarn matchs3` - Match processing workers
- `yarn odds1`, `yarn odds2`, `yarn odds3` - Odds processing workers
- `yarn ends1`, `yarn ends2`, `yarn ends3` - Match ending workers
- `yarn image` - Image processing worker
- `yarn results` - Results processing worker

### Frontend Scripts

- `yarn start` - Start development server
- `yarn build` - Build for production
- `yarn winBuild` - Build for production (Windows)
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors automatically
- `yarn prettier` - Format code with Prettier
- `yarn clear-all` - Remove all build artifacts and dependencies
- `yarn re-start` - Clean, reinstall, and start development server
- `yarn re-build` - Clean, reinstall, and build for production

### Admin Scripts

- `yarn start` - Start development server
- `yarn build` - Build for production
- `yarn lint` - Run ESLint
- `yarn lint:fix` - Fix ESLint errors automatically
- `yarn prettier` - Format code with Prettier
- `yarn clear-all` - Remove all build artifacts and dependencies
- `yarn re-start` - Clean, reinstall, and start development server
- `yarn re-build` - Clean, reinstall, and build for production

## 🏗️ Project Structure

```
betting/
├── backend/                 # Backend API server
│   ├── src/
│   │   ├── controllers/    # Route controllers
│   │   ├── models/         # Database models
│   │   ├── routes1/        # API routes group 1
│   │   ├── routes2/        # API routes group 2
│   │   ├── routes3/        # API routes group 3
│   │   ├── middlewares/    # Express middlewares
│   │   ├── socket/         # Socket.io handlers
│   │   ├── utils/          # Utility functions
│   │   └── index.ts        # Application entry point
│   ├── dist/               # Compiled JavaScript
│   ├── log/                # Application logs
│   ├── example.env         # Environment variables template
│   └── package.json
│
├── frontend/               # User-facing web application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── sections/       # Page sections
│   │   ├── layouts/        # Layout components
│   │   ├── routes/         # Routing configuration
│   │   ├── store/          # Redux store
│   │   ├── hooks/          # Custom React hooks
│   │   ├── utils/          # Utility functions
│   │   ├── assets/         # Static assets
│   │   └── App.tsx         # Main application component
│   ├── public/             # Public assets
│   └── package.json
│
├── admin/                  # Administrative dashboard
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── sections/       # Page sections
│   │   ├── layouts/        # Layout components
│   │   ├── routes/         # Routing configuration
│   │   ├── store/          # Redux store
│   │   ├── hooks/          # Custom React hooks
│   │   ├── utils/          # Utility functions
│   │   ├── assets/         # Static assets
│   │   └── App.tsx         # Main application component
│   ├── public/             # Public assets
│   └── package.json
│
├── upload/                 # File uploads directory
├── webet-db-backup/        # Database backup files
└── README.md
```

## 🎨 Customization

### Environment Variables

Create environment-specific configuration files:

**Backend** (`.env`):
```env
# Database
MONGODB_URI=your_mongodb_connection_string

# JWT
JWT_SECRET=your_jwt_secret

# API Keys
SENDGRID_API_KEY=your_sendgrid_key
TWILIO_ACCOUNT_SID=your_twilio_sid

# Payment Gateways
COINPAYMENTS_PUBLIC_KEY=your_public_key
COINPAYMENTS_PRIVATE_KEY=your_private_key

# Server
PORT=5000
NODE_ENV=development
```

**Frontend/Admin** (`.env`):
```env
REACT_APP_API_URL=http://localhost:5000
REACT_APP_ENVIRONMENT=development
REACT_APP_SOCKET_URL=http://localhost:5000
```

### Styling

- **Material-UI**: Pre-built components with customizable themes
- **Emotion**: CSS-in-JS for component-specific styling
- **SCSS**: Global styles and utilities
- **Custom Themes**: Extensible color schemes and design tokens

### Internationalization

The platform supports multiple languages through i18next. Language files are located in:
- Frontend: `frontend/src/locales/`
- Admin: `admin/src/locales/`

## 🔧 Configuration

### MongoDB

Ensure MongoDB is running before starting the backend server. The connection string should be configured in the `.env` file.

### Socket.io

Real-time features use Socket.io for bidirectional communication. Configure the Socket.io URL in frontend/admin environment variables.

### Payment Gateways

The platform supports multiple payment methods:
- Cryptocurrency payments (CoinPayments)
- Traditional payment methods
- Web3 integration (Ethereum, Solana)

Configure payment gateway credentials in the backend `.env` file.

### Security Features

- **Rate Limiting**: Prevents abuse and DDoS attacks
- **Helmet**: Security headers for Express
- **CORS**: Configurable cross-origin resource sharing
- **Authentication**: JWT-based authentication
- **Validation**: Request validation with Joi
- **Session Management**: Secure session handling

## 🚀 Deployment

### Build for Production

**Backend:**
```bash
cd backend
yarn build
yarn start
```

**Frontend:**
```bash
cd frontend
yarn build
```

**Admin:**
```bash
cd admin
yarn build
```

### Deployment Options

The built applications can be deployed to various platforms:

- **Backend**: 
  - Traditional VPS/Cloud servers (AWS EC2, DigitalOcean, etc.)
  - Container platforms (Docker, Kubernetes)
  - Serverless platforms (AWS Lambda, Vercel Functions)

- **Frontend/Admin**:
  - **Netlify**: Drag and drop the `build` folder
  - **Vercel**: Connect your GitHub repository
  - **AWS S3 + CloudFront**: Static hosting with CDN
  - **Traditional hosting**: Upload files via FTP/SFTP

### Production Considerations

- Set `NODE_ENV=production` in backend environment
- Configure proper CORS origins
- Set up SSL/TLS certificates
- Configure database backups
- Set up monitoring and logging
- Configure rate limiting appropriately
- Enable cluster mode for backend (set `CLUSTER=true`)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Style

- Follow TypeScript best practices
- Use ESLint and Prettier for code formatting
- Write meaningful commit messages
- Add comments for complex logic
- Follow the existing code structure

## 📝 License

ISC

## 🆘 Support

For support and questions:

- Create an issue in the repository
- Contact the development team
- Check the documentation for common issues
- Review the FAQ section in the application

## 🔗 Additional Resources

For more information about each component, refer to their respective README files:

- [Backend README](./backend/README.md) - Backend API documentation
- [Frontend README](./frontend/README.md) - Frontend application documentation
- [Admin README](./admin/README.md) - Admin dashboard documentation

### External Documentation

- [React Documentation](https://reactjs.org/)
- [Node.js Documentation](https://nodejs.org/)
- [Express.js Documentation](https://expressjs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Material-UI Documentation](https://mui.com/)
- [Socket.io Documentation](https://socket.io/)
- [TypeScript Documentation](https://www.typescriptlang.org/)

---

**Note**: This is a sports betting and casino gaming platform. Please ensure compliance with local gambling laws and regulations in your jurisdiction. Responsible gaming practices should be implemented and enforced.
