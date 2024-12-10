# Mi Blog

Este es un proyecto desarrollado en Laravel para construir un blog. Incluye funcionalidades como autenticación, manejo de publicaciones y una interfaz sencilla para interactuar con el contenido.

## Descripción General

- **Nombre del Proyecto:** Mi Blog
- **Framework:** Laravel
- **Objetivo:** Permitir la creación, edición y visualización de publicaciones en un entorno seguro y bien diseñado.

## Temas Principales de Aprendizaje

1. **Desarrollo Web Backend:**
   - Uso de **Laravel** como framework principal para la gestión del backend.
   - Manejo de bases de datos con Eloquent ORM para operaciones CRUD (Create, Read, Update, Delete).
   - Configuración y uso de rutas con controladores.

2. **Autenticación y Seguridad:**
   - Implementación de autenticación de usuarios (registro, inicio de sesión y cierre de sesión).
   - Protección contra CSRF mediante tokens.
   - Validación de entradas de usuarios.

3. **Desarrollo Frontend:**
   - Uso de **Blade Templates** para crear vistas reutilizables y dinámicas.
   - Estilización con **Tailwind CSS** para un diseño moderno y responsivo.

4. **Gestión de Publicaciones:**
   - Creación, edición y eliminación de publicaciones.
   - Validación de datos mediante clases de solicitud (Request).

5. **Internacionalización:**
   - Soporte para múltiples idiomas (`en`, `es`).

## Lenguajes y Herramientas Utilizadas

- **PHP:** Lenguaje principal del backend.
- **Laravel:** Framework PHP para desarrollo web.
- **MySQL:** Base de datos relacional utilizada.
- **Blade:** Motor de plantillas de Laravel.
- **Tailwind CSS:** Framework CSS para diseño responsivo.
- **JavaScript:** Para interactividad básica.
- **Composer:** Gestión de dependencias de PHP.
- **Node.js y NPM:** Herramientas para gestionar paquetes frontend.

## Estructura del Proyecto

- **app/**: Contiene controladores, modelos y middleware.
- **config/**: Configuraciones del proyecto.
- **database/**: Migraciones y fábricas de la base de datos.
- **public/**: Archivos públicos, como CSS y JavaScript.
- **resources/**: Vistas Blade y archivos de recursos frontend.
- **routes/**: Definición de rutas web y API.
- **tests/**: Pruebas unitarias y funcionales.

## Instalación y Uso

1. **Requisitos:**
   - PHP >= 8.0
   - Composer
   - Node.js y NPM
   - Servidor web como Apache o Nginx
   - MySQL

2. **Instrucciones de Instalación:**
   - Clona este repositorio:
     ```bash
     git clone https://github.com/usuario/mi-blog.git
     ```
   - Instala dependencias de PHP:
     ```bash
     composer install
     ```
   - Instala dependencias de JavaScript:
     ```bash
     npm install && npm run dev
     ```
   - Configura el archivo `.env` y genera la clave de la aplicación:
     ```bash
     cp .env.example .env
     php artisan key:generate
     ```
   - Ejecuta las migraciones de la base de datos:
     ```bash
     php artisan migrate
     ```
   - Inicia el servidor local:
     ```bash
     php artisan serve
     ```

3. **Uso:**
   - Accede a la aplicación desde `http://localhost:8000`.
   - Regístrate o inicia sesión para comenzar a publicar.
