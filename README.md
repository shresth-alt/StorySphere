# StorySphere (Demo)

This is a frontend-only demo of StorySphere (Instagram-like) using React + Vite.
It uses **localStorage** to simulate accounts, posts and events.

## Requirements
- Node.js (16+ recommended)
- npm or yarn

## Run locally
1. unzip and `cd StorySphere`
2. `npm install`
3. `npm run dev`
4. Open http://localhost:5173

## Notes & limitations
- This is a demo frontend only (no server). Data is stored in your browser localStorage.
- Use the Sign Up page to create accounts.
- Events can be created on the Events page or via quick-create in Feed.
- Images are stored as data URLs in localStorage (may use a lot of space).
- This is provided as a starting point — to make a production app you'd add a proper backend, authentication, storage, and CDN for images.
