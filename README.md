
# 🛒 Sistema de Punto de Venta (Backend API)

API RESTful robusta desarrollada para la gestión de un sistema de punto de venta, construida con **Node.js**, **Express**, **TypeScript** y **MySQL**.

## 🚀 Tecnologías y Herramientas
- **Node.js & Express:** Entorno de ejecución y framework para el servidor web.
- **TypeScript:** Tipado estático para un código más limpio y seguro.
- **MySQL (`mysql2/promise`):** Conexión a base de datos relacional optimizada mediante Pool de conexiones.
- **Dotenv:** Gestión segura de variables de entorno.
- **TSX & Nodemon:** Recarga en tiempo real para desarrollo ágil.

---

## ⚙️ Instrucciones de Instalación y Uso

Sigue estos pasos para clonar y echar a andar el proyecto en tu máquina local:

1. **Clona el repositorio:**
   ```bash
   git clone [https://github.com/AngelCarmona31/CRUD_-punto-de-venta-ts.git](https://github.com/AngelCarmona31/CRUD_-punto-de-venta-ts.git)
   cd CRUD_-punto-de-venta-ts

```

2. **Instala las dependencias:**
```bash
npm install

```


3. **Configura tus variables de entorno:**
Crea un archivo llamado `.env` en la raíz del proyecto y agrega tus credenciales de MySQL basándote en este formato:
```env
PORT=3000
DB_HOST=localhost
DB_USER=tu_usuario_mysql
DB_PASSWORD=tu_contraseña_mysql
DB_NAME=nombre_de_tu_base_de_datos
DB_PORT=3306

```


4. **Inicia el servidor en modo desarrollo:**
```bash
npm run dev

```



---

## 📡 Endpoints Principales

| Método | Ruta | Descripción |
| --- | --- | --- |
| **GET** | `/api/productos` | Retorna la lista completa de productos registrados en la base de datos. |
| **POST** | `/api/productos` | Inserta un nuevo producto enviando un JSON con `nombre`, `precio` y `stock`. |

---

> Desarrollado con 💻 por **José Ángel Carmona González** para la universidad.