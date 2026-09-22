# Memoraa — Memory Lane (HTML/CSS/JS + Tailwind)

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
4. Run `npm install`.
5. Run `npm start`.
6. Open `http://localhost:8080`.

### Environment variables
```env
ATLASDB_URL=mongodb+srv://...

> Tailwind is loaded from the official CDN in the HTML files, so no Tailwind build step is required. If you want a production Tailwind build, the UI classes can be moved to a Tailwind CLI/Vite setup later.
