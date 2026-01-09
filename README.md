# Task Management (Todo App) – Laravel

This project is a **Todo / Task Management application** built with **Laravel** to practice and demonstrate
the use of **Repository Pattern** and **Service Pattern** with clean architecture principles.

---

## 🚀 Features
- Create and list tasks (todos)
- Clean and maintainable architecture
- Repository Pattern for data access
- Service Layer for business logic
- Dependency Injection
- Simple and clean UI with Bootstrap 5

---

## 🧱 Architecture

Controller → Service → Repository Interface → Repository → Model

### Responsibilities
- **Controller**: Handles HTTP requests and responses
- **Service**: Contains business logic and application rules
- **Repository Interface**: Defines data access contracts
- **Repository**: Implements data access using Eloquent ORM
- **Model**: Represents database entities

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
└── Models/
└── Todo.php

resources/
└── views/
└── todos/
├── layout.blade.php
└── index.blade.php

---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/samijanghori/TaskManagement_using_RepositoryDesignPattern.git
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


