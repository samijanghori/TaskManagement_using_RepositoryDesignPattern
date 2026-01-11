# Task Management (Todo App) – Laravel

This project is a **Todo / Task Management application** built with **Laravel** to practice and demonstrate
the use of **Repository Pattern**, **Service Pattern**, and **Observer Pattern** with email notifications using Mailtrap.

---

## 🚀 Features
- Create and list tasks (todos)
- Clean and maintainable architecture
- Repository Pattern for data access
- Service Layer for business logic
- Observer Pattern for task creation events
- Email notifications to users via Mailtrap
- Dependency Injection
- Simple and clean UI with Bootstrap 5

---

## 🧱 Architecture

Controller → Service → Repository Interface → Repository → Model → Observer → Notification

### Responsibilities
- **Controller**: Handles HTTP requests and responses
- **Service**: Contains business logic and application rules
- **Repository Interface**: Defines data access contracts
- **Repository**: Implements data access using Eloquent ORM
- **Model**: Represents database entities
- **Observer**: Watches for events (e.g., task creation)
- **Notification**: Sends email notifications to users

---

## 📂 Project Structure

app/
├── Http/Controllers/
│ └── TodoController.php
├── Services/
│ └── TodoService.php
├── Repositories/
│ └── TodoRepository.php
├── Interfaces/
│ └── TodoInterface.php
├── Models/
│ └── Todo.php
├── Observers/
│ └── TodoObserver.php
└── Notifications/
└── TaskCreatedNotification.php

resources/
└── views/
└── todos/
├── layout.blade.php
└── index.blade.php


---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/samijanghori/laravel-repository-service-pattern-todo.git

2. Install dependencies:
composer install


3. Copy environment file:
cp .env.example .env

4. Generate application key:
php artisan key:generate


5. Configure database in .env

6. Run migrations:
php artisan migrate


7. Start the application:
php artisan serve



🧪 Purpose of This Project

Practice Repository, Service, and Observer patterns in Laravel

Learn clean architecture and separation of concerns

Implement event-driven features (email notifications)

Create maintainable and scalable Laravel applications


📌 Author

samiulla – Laravel Developer
GitHub: https://github.com/samijanghori/laravel-design-patterns