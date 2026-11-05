# Diwali Celebration Website (MERN)

Three screens: welcome, interactive firecracker game, and final Diwali wishes featuring your supplied cartoon character.

## Run locally
Requirements: Node.js 18+ and (optional) MongoDB.

Terminal 1:
```bash
cd server
cp .env.example .env
npm install
npm run dev
```

Terminal 2:
```bash
cd client
npm install
npm run dev
```
Open http://localhost:5173. The site works without MongoDB; if configured, game results are stored in MongoDB.
