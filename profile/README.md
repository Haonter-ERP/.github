# Haonter-ERP

Haonter-ERP es un sistema de planificación de recursos empresariales (ERP) diseñado para gestionar las operaciones fundamentales de una empresa, como el manejo de usuarios, productos, proveedores y ventas. Este sistema permite una administración eficiente y centralizada, adaptándose a las necesidades básicas de un negocio en crecimiento.

---

## Características Principales
- **Gestión de usuarios:** Registro, roles, permisos y autenticación.
- **Control de inventario:** Administración de productos, proveedores y existencias.
- **Módulo de ventas:** Seguimiento de ventas y generación de reportes.
- **Seguridad:** Implementación de autenticación mediante tokens JWT.
- **Notificaciones:** Envío de correos electrónicos para eventos clave.

---

## Tecnologías Usadas

### Frontend
- **Vite:** Herramienta de desarrollo ultrarrápida para aplicaciones web modernas, que proporciona un entorno de desarrollo rápido y eficiente.
- **React:** Biblioteca de JavaScript para construir interfaces de usuario dinámicas y componentes reutilizables.
- **React Router Dom:** Librería para la navegación entre páginas en aplicaciones React.
- **Axios:** Cliente HTTP basado en promesas, utilizado para manejar peticiones entre el frontend y el backend.
- **Tailwind CSS:** Framework de diseño CSS que facilita la creación de interfaces modernas y responsivas.
- **SweetAlert2:** Biblioteca para mostrar alertas y diálogos personalizados en aplicaciones web.
- **Atropos:** Biblioteca para crear efectos de paralaje en elementos HTML, utilizada para la página de inicio.
- **React Icons:** Librería de iconos para React, que proporciona una amplia variedad de íconos personalizables.
- **Flowbite:** Kit de interfaz de usuario de código abierto, que incluye componentes y estilos predefinidos.
- **Lucide React:** Conjunto de iconos de alta calidad para React.

### Backend
- **Node.js:** Entorno de ejecución para JavaScript que permite construir aplicaciones del lado del servidor escalables y rápidas.
- **Express.js:** Framework de Node.js para la creación de APIs RESTful y gestión de rutas de forma sencilla.
- **Nodemon:** Herramienta que reinicia automáticamente el servidor al detectar cambios en los archivos, facilitando el desarrollo.
- **MSSQL:** Conector de SQL Server para Node.js, que facilita la conexión y consulta de la base de datos.
- **JWT (JSON Web Tokens):** Protocolo de autenticación que permite proteger las rutas y validar el acceso del usuario de manera segura.
- **Cors:** Middleware para Express.js que permite habilitar el intercambio de recursos entre diferentes dominios.
- **Morgan:** Middleware para Express.js que registra las solicitudes HTTP en la consola, facilitando la depuración.
- **Argon2:** Biblioteca para cifrar contraseñas de forma segura, utilizada para almacenar las credenciales de los usuarios.
- **Dotenv:** Módulo para cargar variables de entorno desde un archivo `.env`, que facilita la configuración de la aplicación.
- **Multer:** Middleware para Express.js que facilita la carga de archivos en el servidor, utilizado para subir imágenes de productos.
- **PDFKit:** Biblioteca para generar archivos PDF en Node.js, utilizada para crear reportes de ventas.
- **Nodemailer:** Módulo para enviar correos electrónicos desde Node.js, utilizado para notificaciones y alertas.
- **Puppeteer:** Librería para la automatización de tareas en el navegador y la generación de capturas de pantalla.
- **Sharp:** Biblioteca para el procesamiento de imágenes.

### Base de Datos
- **SQL Server:** Sistema de gestión de bases de datos relacional que proporciona almacenamiento seguro y escalable.
---

## Instalación
Para instalar y ejecutar Haonter-ERP en tu máquina local, sigue los siguientes pasos:

### Clonar el Repositorio
```github
git clone
```

### Instalar Dependencias
#### haonter-erp
```bash
cd haonter-erp
npm install
```

#### haonter-erp-backend
```bash
cd haonter-erp-backend
npm install
```

### Configurar la Base de Datos
1. Crea una base de datos en SQL Server.

2. Copia el contenido del archivo `haonter-erp-backend/database.sql` y ejecútalo en tu base de datos para crear las tablas necesarias.

3. Crea un archivo `.env` en la carpeta `haonter-erp-backend` y añade las siguientes variables de entorno:

```env
DB_SERVER=localhost
DB_DATABASE=tu_base_de_datos
DB_USER=tu_usuario
DB_PASSWORD=clave_de_base_de_datos
DB_PORT=1433
SERVER_PORT=7000
```

### Iniciar el Servidor
---
#### haonter-erp
```bash
cd haonter-erp
npm run dev
```

#### haonter-erp-backend
```bash
cd haonter-erp-backend
npm run dev
```

¡Listo! Ahora puedes acceder a Haonter-ERP en tu navegador a través de la dirección [http://localhost:7000](http://localhost:7000]).

---
## Licencia
Este proyecto cuenta con la Licencia MIT. Esto significa que eres libre de usar, modificar y distribuir el software, siempre y cuando incluyas la licencia original y la atribución al autor.

---

## Versión
**Versión 0.1**  
Se esperan futuras actualizaciones con nuevas características y mejoras. ¡Mantente atento!

---

## Información de Contacto
**Desarrolladores**: 
  - **Diego Rodriguez**  (Back-end, Front-end, UI/UX)
  - **Guillermo Arizmendi (Front-end, UI/UX)**
 
**Ubicación**: 
  - **España**
  - **Venezuela**
**Contacto**: [contacto@diegorodriguez.dev](mailto:contacto@diegorodriguez.dev)

¡Gracias por interesarte en Haonter-ERP! 
Si tienes alguna sugerencia o deseas contribuir al proyecto, no dudes en contactarme.
