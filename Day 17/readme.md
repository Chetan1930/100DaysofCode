# DevConnect – Phase 4: Like, Comment & Interactions 💬❤️

Welcome to **Phase 4** of DevConnect – a social platform built for developers by a developer.  
In this phase, we added full interactivity to blog posts through **likes and comments**.

---

## 🚀 Features Implemented

### ✅ Like System
- Users can like/unlike any blog post.
- Backend uses **compound indexes** to avoid duplicate likes.
- Real-time like counts shown on the frontend.

### ✅ Comment System
- Users can add and delete their own comments.
- Comments are stored with user reference and timestamp.
- Displayed in chronological order below each blog post.

---

## ⚙️ Backend Highlights

- **Routes:**
  - `POST /api/like` → Like a blog
  - `DELETE /api/like` → Unlike a blog
  - `POST /api/comment` → Add a comment
  - `DELETE /api/comment/:id` → Delete a comment

- **Models:**
  - `Like` model includes `user` and `blog`, with a unique compound index.
  - `Comment` model includes `text`, `user`, and `blog`.

- **Image Handling:**
  - Switched to uploading images to **Cloudinary**.
  - Image link stored in the database.

---

## 💻 Frontend Features

- **Like Button:**
  - Interactive toggle with feedback on loading.
  - Updates like count dynamically.

- **Comments UI:**
  - Comment input box below each blog.
  - Shows all comments with username and timestamp.
  - Delete option visible only to the author.

- **UX Improvements:**
  - Uploading state feedback (e.g. disabling buttons on publish).
  - Smooth UI transitions.

---

## 📸 Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB + Mongoose
- **Image Uploads:** Cloudinary
- **Authentication:** Passport.js (Session-based)

---

## 🔗 GitHub Repository

🌐 [https://github.com/Chetan1930](https://github.com/Chetan1930)

---

## 📅 Phase Progress

You're now in **Phase 4** of the DevConnect journey.

Next up:  
👉 **Phase 5: Explore Feed & Search Functionality**

---

Feel free to star ⭐ the repo if you find this useful or inspiring!

