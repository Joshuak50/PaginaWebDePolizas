# Sistema de Administración de Polizas y Facturas
Desarrollo de un sitio web para la gestión de pólizas y facturas, orientado a facilitar el registro, seguimiento y control de pólizas de seguros, así como la emisión y administración de facturas asociadas.

---

## 📌 Características

* Registro y gestión de usuarios
* Administración de polizas
* Gestión de Facturas
* Interfaz administrativa con AdminLTE
* Sistema CRUD completo

---

## 🛠 Tecnologías utilizadas

* PHP
* Laravel
* AdminLTE
* HTML
* PostgreSQL
* Bootstrap

---

## ⚙️ Instalación

Sigue estos pasos para ejecutar el proyecto en tu entorno local:

1. Clonar el repositorio

```bash
git clone https://github.com/Joshuak50/PaginaWebDePolizas.git
```

2. Entrar al proyecto

```bash
cd **ubicación del repositorio**
```

3. Instalar dependencias de PHP

```bash
composer install
```

4. Crear archivo `.env`

```bash
cp .env.example .env
```

5. Generar clave de la aplicación

```bash
php artisan key:generate
```

6. Configurar base de datos en `.env`

```env
DB_DATABASE=10ids1
DB_USERNAME=
DB_PASSWORD=
```

7. Ejecutar migraciones

```bash
php artisan migrate
```

8. Ejecutar el servidor

```bash
php artisan serve
```

El sistema estará disponible en:

```
http://127.0.0.1:8000
```

---

##  Autor

**Joshua Gabriel Bello Rivera**  
Ingeniero en Desarrollo y Gestión de Software

---

## 📄 Licencia

Este proyecto es de uso académico y educativo.
