# My Blog

This is a project developed in Laravel to build a blog. It includes features such as authentication, post management, and a simple interface to interact with the content.

## General Description

- **Project Name:** My Blog
- **Framework:** Laravel
- **Objective:** Enable the creation, editing, and viewing of posts in a secure and well-designed environment.

## Key Learning Areas

1. **Backend Web Development:**
   - Use of **Laravel** as the main framework for backend management.
   - Database management with Eloquent ORM for CRUD (Create, Read, Update, Delete) operations.
   - Configuration and use of routes with controllers.

2. **Authentication and Security:**
   - Implementation of user authentication (registration, login, and logout).
   - Protection against CSRF with tokens.
   - Validation of user inputs.

3. **Frontend Development:**
   - Use of **Blade Templates** to create reusable and dynamic views.
   - Styling with **Tailwind CSS** for a modern and responsive design.

4. **Post Management:**
   - Creation, editing, and deletion of posts.
   - Data validation through Request classes.

5. **Internationalization:**
   - Support for multiple languages (`en`, `es`).

## Languages and Tools Used

- **PHP:** Main language for the backend.
- **Laravel:** PHP framework for web development.
- **MySQL:** Relational database used.
- **Blade:** Laravel's templating engine.
- **Tailwind CSS:** CSS framework for responsive design.
- **JavaScript:** For basic interactivity.
- **Composer:** Dependency manager for PHP.
- **Node.js and NPM:** Tools to manage frontend packages.

## Project Structure

- **app/**: Contains controllers, models, and middleware.
- **config/**: Project configurations.
- **database/**: Database migrations and factories.
- **public/**: Public files, such as CSS and JavaScript.
- **resources/**: Blade views and frontend resource files.
- **routes/**: Web and API route definitions.
- **tests/**: Unit and functional tests.

## Installation and Usage

1. **Requirements:**
   - PHP >= 8.0
   - Composer
   - Node.js and NPM
   - A web server like Apache or Nginx
   - MySQL

2. **Installation Instructions:**
   - Clone this repository:
     ```bash
     git clone https://github.com/user/my-blog.git
     ```
   - Install PHP dependencies:
     ```bash
     composer install
     ```
   - Install JavaScript dependencies:
     ```bash
     npm install && npm run dev
     ```
   - Set up the `.env` file and generate the application key:
     ```bash
     cp .env.example .env
     php artisan key:generate
     ```
   - Run the database migrations:
     ```bash
     php artisan migrate
     ```
   - Start the local server:
     ```bash
     php artisan serve
     ```

3. **Usage:**
   - Access the application at `http://localhost:8000`.
   - Register or log in to start creating posts.
