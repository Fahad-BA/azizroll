# 🎬 AzizRoll

![Laravel](https://img.shields.io/badge/Laravel-8.x-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-7.3%2B-777BB4?style=flat-square&logo=php&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-2.x-FB70A9?style=flat-square)
![Status](https://img.shields.io/badge/status-archived-orange?style=flat-square)

A Laravel 8 web application for managing and showcasing curated YouTube playlists. Features an admin dashboard with full CRUD operations for playlists, poster image uploads, and a public-facing gallery page.

## ✨ Features

- **Playlist Gallery** — public page displaying curated YouTube playlists with posters
- **Admin Dashboard** — create, edit, and delete playlists (auth-protected)
- **Image Upload** — poster image handling with unique filename generation
- **Form Validation** — server-side validation for all submissions
- **Custom Typography** — Microgramma D Extended Bold font
- **YouTube & Spotify Integration** — social platform linking

## 🛠️ Tech Stack

- **Laravel 8.54** — PHP framework
- **Jetstream + Sanctum** — authentication
- **Livewire 2.5** — reactive UI components
- **MySQL** — database
- **Blade** — templating

## 📦 Installation

```bash
git clone https://github.com/Fahad-BA/azizroll.git
cd azizroll
composer install
cp .env.example .env
php artisan key:generate
# Configure your database in .env
php artisan migrate
php artisan storage:link
php artisan serve
```

Visit `http://localhost:8000`.
