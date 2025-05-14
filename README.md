# Geek Internship Summer 2025 - Product Frontend Challenge

This project is a submission for the **Geek Internship Summer 2025** technical assessment.  
It is a web application built using **React**, **Ant Design**, and **Refine**, with data fetched from `jsonplaceholder.typicode.com` and avatars generated using `ui-avatars.com`.

## 🔗 Live Demo

[https://github.com/conghuy251020](https://github.com/conghuy251020) _(Local development link)_

---

## 📦 Tech Stack

- **React**
- **Refine Framework** (React Query + Ant Design)
- **Ant Design** (UI Library)
- **React Router** (Routing & URL sync)
- **Axios** (API calls)
- **JSONPlaceholder API** (Mock data source)
- **UI Avatars API** (Dynamic user avatars)

---

## 📁 Folder Structure

```
├── public/
├── src/
│   ├── components/         # Reusable components
│   ├── pages/              # Page views: AlbumList, AlbumDetail, UserList, UserDetail
│   ├── services/           # API interaction logic
│   ├── routes/             # App routes
│   ├── utils/              # Helper functions
│   ├── App.tsx
│   └── index.tsx
├── .gitignore
├── package.json
├── README.md
└── vite.config.ts (if any)
```

---

## ⚙️ Setup & Run Locally

### 1. Create a new React app called my-web-app

```bash
npx create-react-app my-web-app
cd my-web-app

```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Development Server

```bash
npm start
```

> Open your browser at: `http://localhost:3000`

---

## 📸 Screenshots

_See attached folder or screenshots for examples of running application._

---

## 📝 Features Implemented

- ✅ Album list with user info, pagination synced to URL
- ✅ Album detail page with thumbnail preview
- ✅ User list with email, phone, and website links
- ✅ User detail page with associated albums
- ✅ Responsive UI for screens ≥1280px
- ✅ Loading states and accessible UI (alt tags, clickable cursors)
- ✅ Clean code with proper naming and file organization

---

## 📄 License

This project is for educational/testing purposes only and uses public APIs.
