<p align="center">
  <a href="https://github.com/Christian0162/kapitmart" target="_blank">
    <img src="https://raw.githubusercontent.com/Christian0162/kapitmart/main/logo.png" width="300" alt="KapitMart Logo">
  </a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/version-1.0.0-blue" alt="Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-MIT-green" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/Laravel-10-red" alt="Laravel"></a>
  <a href="#"><img src="https://img.shields.io/badge/PHP-8.2-purple" alt="PHP"></a>
  <a href="#"><img src="https://img.shields.io/badge/React-18-blue" alt="React"></a>
  <a href="#"><img src="https://img.shields.io/badge/TailwindCSS-3.3-teal" alt="Tailwind"></a>
  <a href="#"><img src="https://img.shields.io/badge/MySQL-8.0-orange" alt="MySQL"></a>
  <a href="#"><img src="https://img.shields.io/badge/Docker-enabled-blue" alt="Docker"></a>
</p>

---

# KapitMart

**KapitMart** is a multi-vendor e-commerce platform built with **Laravel (API backend) + React (SPA frontend)**.  
It connects **local sellers** with buyers, featuring **vendor trust scoring**, **smart order splitting**, and **real-time chat**.

---

## 🌟 Key Features

### 👤 Customers
- Browse products by category, vendor, or location
- Add products to cart (multi-vendor support)
- Checkout and track orders
- Rate & review products and vendors
- Chat with vendors and negotiate prices

### 🏬 Vendors
- Register & manage products
- View and update orders
- Earn trust badges based on performance
- Communicate with customers via chat

### 🛠 Admin
- Approve or suspend vendors
- Manage categories and users
- Monitor sales, top vendors, and order statistics
- Handle disputes and platform reports

### 📍 Unique Highlights
- Vendor trust scoring & badges
- Smart order splitting for multi-vendor carts
- Location-based vendor filtering
- Optional: AI-based product recommendations

---

## 💻 Tech Stack

### Backend (Laravel API)
- Laravel 10
- PHP 8.2
- MySQL 8
- Redis (cache & queues)
- Pusher (real-time chat)
- API routes for frontend consumption

### Frontend (React SPA)
- React 18 + Hooks
- Tailwind CSS 3.3
- Axios for API calls
- React Router for navigation
- Component-based architecture

### Deployment
- Docker (optional)
- Laravel Forge or VPS
- Nginx or Apache

---

## 🚀 Installation

### Backend (Laravel API)
```bash
git clone https://github.com/yourusername/kapitmart-backend.git
cd kapitmart-backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
