# 🌈 WAXTIX - Mobile-First Social Media & Short Video Platform

WAXTIX ni urubuga rw'ikoranabuhanga rwayobowe n'amashusho magufi (Short-form Video Feed), amakuru y'imfura (News Feed), n'ubutumwa bwihuse mu gihe nyacyo (Real-Time Translated Chat). Urubuga rwubatswe mu buryo bw'ikijyambere (Dark Theme UI) ruhujwe n meza na Firebase Backend.

---

## 🚀 Ibintu nyamukuru bigize WAXTIX (Key Features)

- **📱 Reels Video Feed:** Feed y'amashusho magufi mu buryo bwa Vertical Snap Scrolling, irimo n'izina ry'uyifashe, sidebar y'ibitekerezo (Likes, Comments, Share, Save), n'amajwi.
- **📰 News Feed:** Ubutumwa n'amakuru agezweho mu ngeri zitandukanye.
- **💬 Real-Time Chat:** Uburyo bwo kuganira mu ibanga (Private Chat) burimo n'uburyo bwo guhita uhindura ururimi mu buryo bwihuse (Auto-Translation toggle).
- **📤 Media Uploader:** Uburyo bwo gushyiraho amashusho n'amafoto mu buryo bwa Drag & Drop bihita bibikwa mu bubiko (Storage Buckets).
- **👤 Profile Management:** Umwirondoro w'umukoresha, imiterere y'abamukurikira (Followers/Following), n'ibyo yakoze.
- **⚡ Zero-Cost Infrastructure:** Rwateguriwe gukora 100% ku buntu ukoresheje GitHub, Render, na Firebase.

---

## 🛠️ Ikoranabuhanga ryakoreshejwe (Tech Stack)

- **Frontend:** HTML5, Tailwind CSS (Design & Dark Theme UI), JavaScript (ES6+), FontAwesome Icons.
- **Backend & Database:** Firebase Realtime Database (`https://waxtix-3cc19-default-rtdb.firebaseio.com/`).
- **Hosting & Deployment:** GitHub & Render Static Site Hosting.

---

## 📦 Uko wayishyira kuri Render (Deploy on Render)

1. **GitHub:** Fork cyangwa Clone iyi repository kuri konti yawe ya GitHub.
2. **Render Dashboard:**
   - Jya kuri [Render Dashboard](https://dashboard.render.com/).
   - Kanda **New +** $\rightarrow$ Hitamo **Static Site**.
   - Huza konti yawe na GitHub maze uhitamo iyi repository (`waxtix`).
3. **Configuration Settings:**
   - **Name:** `waxtix`
   - **Branch:** `main`
   - **Build Command:** *(Irekere aho ari ubusa)*
   - **Publish Directory:** `.`
4. Kanda **Create Static Site**. Urubuga rwawe ruhita ruba ruzima mu munota 1!

---

## 🔒 Umutekano (Environment Variables)

Niba ushaka kubika Firebase Credentials zawe mu buryo bw'ibanga kuri Render cyangwa Netlify:

| Variable Name | Value |
| :--- | :--- |
| `VITE_FIREBASE_DATABASE_URL` | `https://waxtix-3cc19-default-rtdb.firebaseio.com/` |
| `VITE_FIREBASE_PROJECT_ID` | `waxtix-3cc19` |

---

© 2026 **WAXTIX App**. Uburenganzira bwose ni ubw'umuhimbyi.
