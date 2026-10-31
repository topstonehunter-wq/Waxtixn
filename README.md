# 🌈 WAXTIX - Mobile-First Social Media & Short Video Platform

WAXTIX is a modern, mobile-first social media and short-form video platform featuring a rich dark theme UI, a dedicated news feed, real-time translated private chat, media uploading, and Firebase backend integration.

---

## 🚀 Key Features

- **📱 Reels Video Feed:** Vertical snap-scrolling video feed featuring creator metadata, verified badges, sound tickers, and an interactive right-hand engagement sidebar (Likes, Comments, Share, Save).
- **📰 News Feed:** Real-time news cards categorized with tags and interactive engagement metrics.
- **💬 Real-Time Chat:** Instant messaging interface equipped with a dynamic auto-translation toggle.
- **📤 Media Uploader:** Drag-and-drop file upload interface designed for public videos, images, and user avatars.
- **👤 Profile Management:** User profile tabs displaying follower counts, bio details, and personal content grids.
- **⚡ Zero-Cost Infrastructure:** Engineered to deploy and run entirely for free using GitHub, Render, and Firebase.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS (Dark Theme UI), JavaScript (ES6+), FontAwesome Icons.
- **Backend & Database:** Firebase Realtime Database (`https://waxtix-3cc19-default-rtdb.firebaseio.com/`).
- **Hosting & Deployment:** GitHub & Render Static Site Hosting.

---

## 📦 How to Deploy on Render

1. **GitHub:** Clone or push this repository (`index.html` and `README.md`) to your GitHub account.
2. **Render Dashboard:**
   - Go to the [Render Dashboard](https://dashboard.render.com/).
   - Click **New +** and select **Static Site**.
   - Connect your GitHub account and select your WAXTIX repository.
3. **Configuration Settings:**
   - **Name:** `waxtix` (or your preferred name)
   - **Branch:** `main` (or `master`)
   - **Build Command:** *(Leave blank)*
   - **Publish Directory:** `.`
4. Click **Create Static Site**. Your live app URL will be generated instantly!

---

## 🔒 Configuration & Environment Variables

To securely configure your Firebase backend connection, ensure your Firebase project keys are properly integrated or mapped to your hosting provider's environment variables:

| Variable Name | Description |
| :--- | :--- |
| `VITE_FIREBASE_DATABASE_URL` | `https://waxtix-3cc19-default-rtdb.firebaseio.com/` |
| `VITE_FIREBASE_PROJECT_ID` | `waxtix-3cc19` |

---

© 2026 **WAXTIX App**. All rights reserved.
