# Three.js Tee

This project contains a React client and an Express server that generates T‑shirt mockups using the OpenAI API.

## Setup

1. **Install dependencies**
   ```bash
   cd server && npm install
   cd ../client && npm install
   ```

2. **Environment variables**
   Copy `.env.example` in the `server` folder and update the values:
   ```bash
   cp server/.env.example server/.env
   ```
   - `OPENAI_API_KEY` – your OpenAI API key
   - `PORT` – port for the Express server (defaults to 8080)

3. **Run the app**
   In one terminal, start the server:
   ```bash
   cd server
   npm start
   ```
   In another terminal, run the React client:
   ```bash
   cd client
   npm run dev
   ```

The client will connect to the server using the URL configured in `src/config/config.js`.
