<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# CMS (Content Management System)

[![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![Spatie Permissions](https://img.shields.io/badge/Spatie_Permissions-4A4A4A?style=for-the-badge)](https://spatie.be/docs/laravel-permission)

A comprehensive CMS built with Laravel featuring advanced CRUD generation, granular permissions, and intuitive content management.

![Dashboard Preview Light Mode](./images/dashboard_light.png)

### Dark Mode support

![Dashboard Preview Dark Mode](./images/dashboard_dark.png)

## Table of Contents
- [Features](#features-)
- [Content Management](#content-management-)
- [Role & Permission Management](#role--permission-management-)
- [Installation](#installation-)
- [Custom Commands](#CRUD-Operations-)
- [Security](#security-)
- [Contribution](#contribution-)
- [License](#license-)

## Features ✨

### Core Functionality
- **⚡ Instant CRUD Generation** - Scaffold full modules with artisan commands
- **🔐 Role-Based Access Control** - Granular permissions using Spatie
- **🔄 Dynamic Routing** - Automatic route registration and optimization
- **📊 Dashboard Analytics** - At-a-glance system overview
- **📱 Responsive Design** - Mobile-friendly interface

## Content Management 📝

| Feature               | Preview                      | Description                              |
|-----------------------|------------------------------|------------------------------------------|
| **CRUD Interface**    | ![Index](./images/content_index.png) | Full-featured interface for content creation, listing, and management |
| **Drag-n-Drop Sort**  | ![Sorting](./images/drag_drop.png) | Visually reorder items with intuitive drag-and-drop functionality |
| **Publish States**    | ![Publish](./images/draft.png) | Toggle between published/draft states with instant status updates |
| **Advanced Search**   | ![Search](./images/searching.png) | Filter content using title with real-time results |
| **Detailed View**     | ![View](./images/view.png) | Comprehensive view showing creator, last editor, and details |

## Role & Permission Management 👥

| Feature               | Preview                      | Description                              |
|-----------------------|------------------------------|------------------------------------------|
| **Roles Listing**     | ![Roles](./images/roles_index.png) | View all roles with assigned permissions |
| **Role Creation**     | ![Create Role](./images/roles_create.png) | Create new roles with permission checkboxes |
| **User Assignment**   | ![Assignment](./images/role_assignment.png) | Assign roles to users through intuitive interface |


### CRUD Operations
```php
# Generate complete CRUD for blogs
php artisan crud:generate blogs
```

```php
# Remove blogs CRUD components
php artisan crud:delete blogs
```
A example crud operation output.
![Crud Operation](./images/crud-operation.png)


### Initial Setup
```bash
# Setup entire system run this after running 
# on localhost and before navigating to login page
php artisan setup:master
```
## Installation ⚡

### Requirements
- PHP 8.1+ with extensions: BCMath, Ctype, Fileinfo, JSON, Mbstring, OpenSSL, PDO, Tokenizer, XML
- MySQL 8.0+ or MariaDB 10.3+
- Composer 2.5+
- Node.js 18+

```php
git clone https://github.com/MeSafal/project_showcase.git
cd project_showcase
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```
---

## 🤝 License & Contribution

© All rights reserved by [Gokul Subedi](https://github.com/mesafal). This project is closed-source.

Got ideas, feedback, or want to collaborate? I’m open to meaningful contributions and discussions.  
Reach out via [GitHub](https://github.com/meSafal) or email at [subedigokul119@gmail.com](mailto:subedigokul119@gmail.com).

---

> Happy Coding 🙂🙂🙂  
> Contact me if you have any queries.

<sub><p align="center">📘 This repository and its documentation were prepared and maintained by <a href="https://github.com/MeSafal/" target="_blank"><u><strong>Gokul Subedi</strong></u></a>. For the latest updates and related projects, visit <a href="https://github.com/MeSafal" target="_blank">github.com/MeSafal</a>.</p></sub>
