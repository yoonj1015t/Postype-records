# Postype Records

## Overview
A Node.js/Express web application serving as the foundation for the Postype Records project.

## Architecture
- **Runtime**: Node.js 20
- **Framework**: Express.js
- **Port**: 5000 (0.0.0.0)

## Project Structure
```
├── server.js        # Express server entry point
├── public/
│   └── index.html   # Static frontend
├── package.json     # Node.js dependencies
└── .gitignore
```

## Running the Project
The application is configured to run via the "Start application" workflow:
```
node server.js
```

## Deployment
Configured for autoscale deployment with:
```
run: ["node", "server.js"]
```
