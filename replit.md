# Request Header Parser Microservice

## Project Overview
This is a freeCodeCamp API microservice project built with Express.js. The application parses HTTP request headers and returns information about the client's IP address, preferred language, and user agent.

## Project Architecture
- **Framework**: Express.js (Node.js)
- **Type**: Web application with REST API
- **Port**: 5000 (configured for Replit environment)
- **Host**: 0.0.0.0 (allows Replit proxy access)

## File Structure
```
/
├── index.js           # Main application server
├── package.json       # Node.js dependencies and scripts
├── views/
│   └── index.html    # Frontend HTML page
└── public/
    └── style.css     # Stylesheet
```

## Recent Changes (Nov 28, 2025)
- Configured application to run on port 5000 with host 0.0.0.0 for Replit environment
- Set up PORT environment variable (5000)
- Configured workflow "Start application" to run npm start
- Installed npm dependencies (express, cors, dotenv)
- Configured deployment for autoscale with npm start command

## Dependencies
- express: ^4.18.1
- cors: ^2.8.1
- dotenv: ^8.2.0

## Running the Application
The application starts automatically via the "Start application" workflow.
Command: `npm start`
Access at: [base URL]/

## API Endpoints
- GET `/` - Main page with usage instructions
- GET `/api/hello` - Test endpoint
- GET `/api/whoami` - Returns client information (IP, language, user agent)

## Environment Variables
- `PORT`: Server port (default: 5000)

## Deployment
Configured for Replit autoscale deployment using npm start.
