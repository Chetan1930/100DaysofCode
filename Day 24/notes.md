# 🚀 Day 24 – Backend-Synced Like System for DevConnect

### 🎯 What was done:

- Implemented a clean, reusable `<LikeButton />` component
- Added a `GET /blogs/:id/likes` route to fetch like status from DB
- Ensured like counts persist and reflect accurately after page refresh
- Moved state control to the parent component for better control and flexibility
- Removed redundant logic from child components to keep things modular and clean

### ✅ Features:

- Like/Unlike a blog in real time
- Fetch & show accurate like count on page reload
- Controlled UI state from parent component
- Toast feedback for success/error

This improves both user experience and data accuracy across sessions!

🛠 Tech Stack: React, TypeScript, Express.js, MongoDB, Axios, React-Toastify

