# 🌿 Book Post Management - Frontend

This is the frontend part of **Book Post Web App**, designed for users to interact with the system via HTML/CSS + Fetch API.

## 💡 Features

- 📌 Login / Register Forms
- 📌 Display All Posts on Home Page
- 📌 Create New Post with Image Upload
- 📌 Edit / Delete Own Posts Only (with JWT)
- 📌 Beautiful UI inspired by Green Nature Theme 🍃

## 🗂️ Structure

```
📁 public/
├── index.html         ← main post display page
├── login.html         ← login form
├── register.html      ← register form
├── create-post.html   ← create form
└── style.css
```

## 🔗 Backend API

This frontend interacts with the backend at:

```
https://your-backend-url.onrender.com/
```

Example fetch call in `script.js`:

```js
fetch("https://your-backend-url.onrender.com/posts")
```

## 🚀 Deployment (Vercel)

1. Push this code to GitHub (e.g., `book-frontend`).
2. Go to [Vercel](https://vercel.com/) → Import GitHub project
3. Deploy with default settings (no build command needed for static site).
4. Add environment variables if needed (or use `.env.js` pattern).
5. Update all `fetch()` backend URLs to your deployed backend URL.

---

### 🔐 Login Required

- Users **must log in** before accessing `index.html` or managing posts.
- Tokens are stored in cookies and sent via `Authorization` header.

---

Enjoy your project! 🌱
