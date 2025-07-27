# Let's start with the day 19 

DevConnect – A Developer Social Blogging Platform 👨‍💻🚀
DevConnect is a full-stack social platform for developers where users can write blogs, interact via likes and comments, and connect with fellow devs.

🚧 Status: Actively Building – Day 19/100
✅ Features Implemented So Far:
User Authentication (GitHub & Google via Passport.js)

Create, Edit & Delete Blog Posts with Rich Text Editor

Like/Unlike Blogs (stored in DB with compound index)

Comment on Blogs (real-time update with full persistence)

Cloudinary Integration for Image Upload

Protected Routes with ensureAuth middleware

UI Feedback (loading states, toast notifications)

🔨 Tech Stack:
Frontend: React, Tailwind CSS

Backend: Node.js, Express

Database: MongoDB + Mongoose

Auth: Passport.js (Google & GitHub)

Cloud: Cloudinary for blog images

Others: Socket.io (upcoming), React Context API

🚀 How to Run Locally:
bash
Copy
Edit
git clone https://github.com/Chetan1930/devconnect.git
cd devconnect
npm install
cd client
npm install
npm run dev
Make sure to set up a .env with:

MongoDB URI

Cloudinary credentials

Passport session secrets

OAuth Client IDs

📸 Screenshots (add yours)
 Login Page

 Blog Feed

 Like & Comment Interface

📅 Progress Timeline
✅ Day 1–10: Auth System, Dashboard UI, Blog Creation

✅ Day 11–18: Likes, Comments, UX Enhancements

✅ Day 19: Debugging & Data Persistence Fixes

🔜 Day 20+: Live Feed, Profile Pages, Search, Notifications

📬 Connect with Me:
GitHub: Chetan1930
LinkedIn: Chetan Chauhan