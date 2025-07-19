# MERN Stack Application

## Project Overview
This is a full-stack MERN application with authentication, monitoring, and CI/CD pipeline.

## Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd <your-repo-name>
```

2. Install dependencies:
```bash
# Install frontend dependencies
npm install

# Install backend dependencies
cd backend
npm install
```

3. Environment Setup:
- Copy `.env.example` to `.env` in both root and backend directories
- Update the environment variables with your values

## Development

1. Start the backend server:
```bash
cd backend
npm run dev
```

2. Start the frontend development server:
```bash
# In another terminal
npm start
```

## Deployment

### Backend Deployment (Render/Railway/Heroku)
1. Create a new project
2. Connect your GitHub repository
3. Configure environment variables
4. Deploy the backend

### Frontend Deployment (Vercel/Netlify)
1. Create a new project
2. Connect your GitHub repository
3. Configure build settings
4. Deploy the frontend

## Monitoring
- Health check endpoint: `/health`
- Logging: Check `error.log` and `combined.log` in the backend directory
- Rate limiting: 100 requests per 15 minutes per IP

## CI/CD Pipeline
- Automated tests run on push and pull requests
- Automatic deployment on merge to main branch
- Monitoring and logging in production

## License
MIT