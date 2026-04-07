# 🎮 App Nativa — Game Keys

App web completa con **backend básico en Node.js/Express** y **frontend nativo** (HTML, CSS y JavaScript puro), desarrollada como ejercicio de práctica para integrar ambas capas sin frameworks de UI.

> ⚠️ **Proyecto inactivo** — Este repositorio fue desarrollado con fines educativos y actualmente no se encuentra en mantenimiento activo.

---

## 🛠️ Stack Tecnológico

| Tecnología | Uso |
|---|---|
| Node.js | Entorno de ejecución del servidor |
| Express.js v5 | Framework HTTP |
| JavaScript nativo | Frontend sin frameworks |
| HTML5 / CSS3 | Estructura y estilos del cliente |
| Nodemon | Recarga automática en desarrollo |

> Frontend 100% nativo — sin React, Vue ni ningún framework de UI.

---

## 📁 Estructura del Proyecto

```
AppNativa-GameKeys/
├── public/             # Frontend estático servido por Express
│   ├── index.html
│   ├── css/
│   └── js/
├── server.js           # Punto de entrada del servidor
├── package.json
└── README.md
```

---

## 🚀 Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/xpedrojfloresx/AppNativa-GameKeys.git

# 2. Entrar al proyecto
cd AppNativa-GameKeys

# 3. Instalar dependencias
npm install

# 4. Ejecutar en desarrollo (con recarga automática)
npm run dev

# 4. O ejecutar en producción
npm start
```

El servidor se ejecutará en `http://localhost:3000`

---

## ⚙️ Scripts Disponibles

| Comando | Descripción |
|---|---|
| `npm start` | Inicia el servidor con Node.js |
| `npm run dev` | Inicia el servidor con Nodemon (recarga automática) |

---

## 📌 Funcionalidades Implementadas

- ✅ Servidor HTTP con Express.js
- ✅ Servicio de archivos estáticos desde `/public`
- ✅ Frontend nativo integrado (sin frameworks)
- ✅ Estructura lista para agregar rutas y API REST

---

## 👤 Autor

**Pedro J. Flores**
- GitHub: [@xpedrojfloresx](https://github.com/xpedrojfloresx)
- LinkedIn: [Pedro Flores](https://www.linkedin.com/in/pedro-flores-dev/)

---

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).
