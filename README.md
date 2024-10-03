<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# OPERACIONES CRUD LARAVEL

OPERACIONES CRUD LARAVEL

## Requisitos

- PHP >= 8.0
- Composer
- SQLite

## Instalación

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. **Clona el repositorio**

   ```bash
   git clone https://github.com/royer2001/laravel-crud-tt.git
   ```

2. **Navega al directorio del proyecto**

   ```bash
   laravel-crud-tt
   ```

3. **Instala las dependencias utilizando Composer**

   ```bash
   composer install
   ```

4. **Configura el archivo de entorno**

   Copia el archivo `.env.example` a `.env` y ajusta las configuraciones según sea necesario.

   ```bash
   cp .env.example .env
   ```

5. **Configura la base de datos**

   Asegúrate de que la configuración de tu base de datos en el archivo `.env` sea similar a la siguiente:

   ```dotenv
   DB_CONNECTION=sqlite
   DB_DATABASE=/ruta/a/tu/base_de_datos.sqlite
   ```

6. **Genera la clave de aplicación**

   ```bash
   php artisan key:generate
   ```

7. **Ejecuta las migraciones**

   Si tienes migraciones, puedes ejecutarlas con el siguiente comando:

   ```bash
   php artisan migrate
   ```

## Uso

- Levanta el servidor de desarrollo

```bash
php artisan serve
```

Accede a la aplicación en `http://localhost:8000`.

## Endpoints

El proyecto cuenta con los siguientes Endpoints para realizar alguna operación CRUD

`HTTP GET: /api/products` --> LISTAR TODOS LOS REGISTROS

`HTTP GET: /api/products/{id}` --> OBTENER UN REGISTRO PASANDO EL ID

`HTTP POST: /api/products` --> INGRESAR UN NUEVO REGISTRO

`HTTP PUT: /api/products/{id}` --> MODIFICAR UN REGISTRO EXISTETE PASANDO EL ID

`HTTP DELETE: /api/products/{id}` --> ELIMINAR UN REGISTRO PASANDO EL ID