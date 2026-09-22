# Retro Heads — Memory Lane (HTML/CSS/JS + Tailwind)

Converted from the original Express/EJS project into a vanilla HTML/CSS/JavaScript frontend using Tailwind CSS via CDN, while retaining the MongoDB-backed functionality.

## Features
- Login / signup / logout
- Password reset
- Memory feed
- Create and delete your own memories
- Search memories by username
- Personal diary
- Memory Map: create, view and delete your own places
- Express session authentication
- MongoDB persistence
- Tailwind utility classes with a custom nostalgia theme

## Setup
1. Install Node.js 18+.
2. Copy `.env.example` to `.env` if needed.
3. Put your MongoDB Atlas connection string in `ATLASDB_URL`.
4. Set a strong `SESSION_SECRET`.
5. Run `npm install`.
6. Run `npm start`.
7. Open `http://localhost:8080`.

### Environment variables
```env
ATLASDB_URL=mongodb+srv://...
PORT=8080
SESSION_SECRET=your-long-random-secret
```

> Tailwind is loaded from the official CDN in the HTML files, so no Tailwind build step is required. If you want a production Tailwind build, the UI classes can be moved to a Tailwind CLI/Vite setup later.
