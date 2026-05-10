# Mayuri Fitness

Mayuri Fitness is a full stack fitness center web application built with PHP and MySQL. It offers a complete experience for end users and administrators, including secure authentication, a dynamic admin dashboard, and a structured catalog of services and content. This project was delivered as the capstone for the EazyByts internship program.

## Overview

The application is organized around a clean separation between the public facing site and the administrative interface. Visitors can browse services, learn about the fitness center, and create accounts, while administrators manage content through a protected dashboard. The codebase emphasizes security, maintainability, and a clear MVC inspired layout.

## Key Features

- Secure user registration and login with credential hashing and session management
- Dedicated administrative dashboard for managing site content and user data
- Modular file structure separating public application code, admin tooling, and configuration
- Custom styling and responsive layout using HTML, CSS, and JavaScript
- Relational database schema designed for users, services, and administrative records

## Tech Stack

| Layer | Technology |
| --- | --- |
| Backend | PHP |
| Database | MySQL |
| Frontend | HTML, CSS, JavaScript |
| Server | Apache (XAMPP, MAMP, or equivalent) |

## Project Structure

```
EazyByts-Final-Project/
Database/                   SQL schema and seed data
mayuri_fitness/
  admin/                    Admin dashboard and management tools
  app/                      Core application logic
  assets/                   Images and static media
  constant/                 Configuration and constants
  head.php                  Shared header markup
  index.php                 Public entry point
  secure_login.php          Authentication handler
  style.css                 Global stylesheet
  popup_style.css           Modal and popup styling
```

## Getting Started

### Prerequisites

- PHP 7.4 or later
- MySQL 5.7 or later
- A local web server such as XAMPP or MAMP

### Installation

1. Clone this repository into your web server document root, for example `htdocs`.
2. Create a new MySQL database and import the SQL file from the `Database/` directory.
3. Update database credentials inside `mayuri_fitness/constant/` to match your local environment.
4. Start Apache and MySQL through your local server control panel.
5. Open the application at http://localhost/mayuri_fitness in your browser.

### Default Access

- The public site is available at the project root.
- The admin dashboard is available at `/admin` and requires administrator credentials.

## Highlights

This project demonstrates practical experience with server side scripting, relational database design, authentication patterns, and full stack web development from schema to user interface.

## Author

Developed by Arup Halder as the final project for the EazyByts internship program.
