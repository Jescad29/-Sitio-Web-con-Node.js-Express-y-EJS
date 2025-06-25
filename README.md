# 🌐 Sitio Web con Node.js, Express y EJS

Este es un proyecto de una **página web dinámica** construido con **Node.js**, **Express** y **EJS**. Utiliza **templates reutilizables**, **partials** y **layouts** para mantener una estructura limpia y modular.

---

## 🧰 Tecnologías utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [EJS](https://ejs.co/)

---

## 📄 Páginas incluidas

- 🏠 **Home** – Página principal con bienvenida y diseño general.
- ℹ️ **About** – Información sobre el proyecto o autor.
- 📬 **Contact** – Formulario o información de contacto.

---

## 📦 Instalación

1. Clona este repositorio:

```bash
git https://github.com/Jescad29/-Sitio-Web-con-Node.js-Express-y-EJS
```

2. Instala las dependencias:

```bash
cd web-ejs-app
npm install
```

3. Ejecuta el servidor.

```bash
node app.js
```

4. Abre tu navegador:

```bash
http://localhost:3000
```

## 🧰 Detalles técnicos

- Uso de Express como framework backend.
- Motor de plantillas EJS con soporte para:
  - Layouts generales (index.ejs, contact.ejs, about.ejs)
  - Partials: encabezado (header.ejs) y pie de página (footer.ejs)
- Enrutamiento para cada página (home, about, contact).
- Archivos estáticos servidos desde la carpeta /public.

## 🌱 Posibles mejoras

- Añadir validación al formulario de contacto.
- Conexión con una base de datos para guardar mensajes.
- Agregar controladores y separar lógica en carpetas.
- Implementar un sistema de autenticación.

## 🙌 Contribuciones

- ¡Eres bienvenido a contribuir!
- Haz un fork.
- Crea una nueva rama

```bash
git checkout -b nueva-funcionalidad
```

- Haz tus cambios.
- Sube la rama

```bash
git push origin nueva-funcionalidad
```

- Abre un Pull Request.
