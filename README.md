

````markdown
# 🚀 Proyecto Laravel

Este proyecto está construido con [Laravel](https://laravel.com/).  
A continuación encontrarás los pasos para configurarlo desde cero.

## 📦 Requisitos
- PHP >= 8.2
- Composer
- Node.js >= 18
- NPM o Yarn
- MySQL / PostgreSQL

---

## ⚙️ Instalación

```bash
git clone https://github.com/usuario/nombre-proyecto.git
cd nombre-proyecto
composer install
cp .env.example .env
php artisan key:generate
````

Configura el archivo `.env` con tus credenciales de base de datos.

---

## 🧱 Migraciones y Seeders

```bash
php artisan migrate --seed
```

---

## 🎨 Frontend

```bash
npm install
npm run dev
```

---

## 🚀 Ejecutar el servidor

```bash
php artisan serve
```

El proyecto estará disponible en:
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🧪 Comandos útiles

| Descripción                | Comando                                        |
| -------------------------- | ---------------------------------------------- |
| Limpiar cachés             | `php artisan optimize:clear`                   |
| Crear modelo con migración | `php artisan make:model Nombre -m`             |
| Crear controlador          | `php artisan make:controller NombreController` |
| Ver rutas                  | `php artisan route:list`                       |

---

## 🧑‍💻 Autor

**Celeste Castellanos**
📧 [celestecastell@gmail.com](mailto:celestecastell@gmail.com)

```

---
