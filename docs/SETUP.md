# Setup Guide

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/crispychicken123/Control-Tower.git
cd Control-Tower
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Environment Configuration

```bash
# Copy the example env file
cp .env.example .env.local

# Edit with your configuration
nano .env.local  # or your favorite editor
```

### 4. Run Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Project Structure

### `/app`
- Next.js App Router configuration
- Page components and layouts
- API routes

### `/components`
- Reusable React components
- UI components
- Feature components

### `/lib`
- Utility functions
- Helper methods
- Constants

### `/public`
- Static files
- Images
- Fonts

### `/sample-data`
- Mock data for development
- Example JSON files
- Test data

### `/docs`
- Documentation files
- Setup guides
- API documentation

## Building for Production

```bash
# Build the application
npm run build

# Start production server
npm start
```

## Troubleshooting

### Port 3000 Already in Use

```bash
# Use a different port
npm run dev -- -p 3001
```

### Dependency Issues

```bash
# Clear cache and reinstall
rm -rf node_modules
npm install
```

## Code Quality

```bash
# Run linter
npm run lint

# Format code
npm run format

# Type checking
npm run type-check
```
