
# Listen 🎧

A modern **music streaming web app** built with **Vue 3** and **Laravel**, designed for smooth performance, scalability, and a clean, modular codebase.  
It features live data integration, user authentication, playlist management, and a responsive audio player UI.

---

## 🚀 Tech Stack

**Frontend:** Vue 3, TypeScript, Pinia, Vite, Tailwind CSS  
**Backend:** Laravel 10, RESTful APIs  
**Database:** MySQL / PostgreSQL  
**Other:** Axios, Vue Router, CI/CD pipelines

---

## 🧩 Features

- 🎵 **Music Player** – Stream songs with play, pause, skip, and volume controls  
- 📂 **Playlist Management** – Create, edit, and delete playlists  
- 👤 **User Authentication** – Secure login and registration (Laravel Sanctum / JWT)  
- 🔄 **Live API Integration** – Real-time sync between frontend and backend  
- 📱 **Responsive UI** – Optimized for mobile and desktop  
- ⚙️ **Modular Architecture** – Reusable components and maintainable state structure  
- 🚀 **CI/CD Ready** – Automated deployment and testing pipeline  
- 🧾 **Clear Documentation** – Commented code and structured file organization

---

## 🏗️ Project Setup

### Backend Setup
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev

