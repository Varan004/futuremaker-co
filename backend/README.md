# Futuremaker Backend

This is a simple Node.js/Express backend for the Futuremaker website.

## Setup

1. Open a terminal and navigate to the `backend` folder:
   
   cd backend

2. Install dependencies:
   
   npm install

3. Start the backend server:
   
   npm start

The backend will run on http://localhost:3001

## API

- `GET /api/health` — Health check endpoint. Returns `{ status: 'ok', message: 'Backend is running!' }`

You can add more API routes in `index.js` as needed.
