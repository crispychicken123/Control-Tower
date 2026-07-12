# Control Tower 🏢

A comprehensive dashboard and management system for order monitoring, SLA tracking, and performance metrics.

## Project Structure

```
ControlTower/
│
├── app/                 # Next.js app directory
├── components/          # Reusable React components
├── lib/                 # Utility functions and helpers
├── public/              # Static assets
├── sample-data/         # ✅ Sample data files only
├── docs/                # Documentation
├── scripts/             # Build and automation scripts
├── package.json         # Dependencies
├── .gitignore           # Git ignore rules
└── .env.example         # Environment variables template
```

## Features

- 📊 Real-time order monitoring
- ⏱️ SLA tracking and alerts
- 📈 Performance metrics dashboard
- 🤖 AI-powered chat assistant
- 📋 Order management system

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/crispychicken123/Control-Tower.git
cd Control-Tower

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Environment Variables

Copy `.env.example` to `.env.local` and fill in your values:

```env
# API Configuration
NEXT_PUBLIC_API_URL=your_api_url
API_KEY=your_api_key

# Database
DATABASE_URL=your_database_url

# Authentication
AUTH_SECRET=your_auth_secret
```

## Development

```bash
# Development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linter
npm run lint
```

## License

MIT License - see LICENSE file for details

## Contact

Created by [@crispychicken123](https://github.com/crispychicken123)
