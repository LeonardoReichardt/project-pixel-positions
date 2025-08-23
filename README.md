# 🎨 Pixel Positions

Pixel Positions is a **Laravel-based web application** designed to manage pixel positions and demonstrate modern web development best practices.  
Originally inspired by a Laracasts tutorial, this project highlights **clean architecture, authentication, migrations, Blade views, and asset management with Vite**.

---

## 🚀 Features

- Full **CRUD** management of pixel positions  
- **Authentication flow** (Register, Login, Logout)  
- Organized **MVC structure** (Controllers, Models, Policies)  
- **Database migrations, factories, and seeders**  
- **Blade templating** with modern asset bundling via Vite  
- Clean and modular project structure  

---

## 🛠️ Tech Stack

- **Backend:** PHP 8.x, Laravel 12.x  
- **Frontend:** Blade, TailwindCSS, JavaScript, Vite  
- **Database:** MySQL / PostgreSQL / SQLite  
- **Tooling:** Composer, npm  

---

## 📂 Project Structure

```
pixel-positions/
├── app/            # Controllers, models, policies, providers
├── bootstrap/      # Framework bootstrap files
├── config/         # Configuration files
├── database/       # Migrations, factories, seeders
├── public/         # Public assets (JS, CSS, images)
├── resources/      # Blade views, CSS/JS assets
├── routes/         # Web and API routes
├── storage/        # Generated files and logs
├── tests/          # Automated tests
└── ...             # Other Laravel default files
```

---

## ⚡ Installation & Setup

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/LeonardoReichardt/project-pixel-positions.git
   cd pixel-positions
   ```

2. **Install PHP dependencies:**  
   ```bash
   composer install
   ```

3. **Install frontend dependencies:**  
   ```bash
   npm install
   ```

4. **Copy and configure environment file:**  
   ```bash
   cp .env.example .env
   ```
   Update `.env` with your database and app settings.

5. **Generate application key:**  
   ```bash
   php artisan key:generate
   ```

6. **Run migrations (and seed if needed):**  
   ```bash
   php artisan migrate --seed
   ```

7. **Build frontend assets:**  
   ```bash
   npm run dev   # for development
   npm run build # for production
   ```

8. **Start the development server:**  
   ```bash
   php artisan serve
   ```

Now visit [http://localhost:8000](http://localhost:8000). 🎉

---

## 🌐 Available Routes

**Public Routes:**  
- `/` — Home (list all jobs/pixels)  
- `/search` — Search for jobs/pixels  
- `/tags/{tag:name}` — Filter by tag  

**Authentication:**  
- `/register` — Register  
- `/login` — Login  
- `/logout` — Logout (requires auth)  

**Protected Routes:**  
- `/jobs/create` — Create new job/pixel  
- `/jobs` (POST) — Store new job/pixel  

---

## 🤝 Contribution

Contributions are welcome!  

1. Fork the project  
2. Create a feature branch  
3. Commit and push your changes  
4. Open a Pull Request 🚀  

---

## 📖 Learn More

- [Laravel Documentation](https://laravel.com/docs)  
- [Laracasts](https://laracasts.com/)  
- [Vite in Laravel](https://laravel.com/docs/vite)  

---

### ✨ About

This project was built for **learning and demonstration purposes**.  
Feedback and contributions are highly appreciated!  

---
