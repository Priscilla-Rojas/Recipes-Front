# 🍜 PI Food Recipes

[![React](https://img.shields.io/badge/React-17.0.1-blue)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16.x-green)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.17.1-lightgrey)](https://expressjs.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14.x-blue)](https://www.postgresql.org/)
[![Redux](https://img.shields.io/badge/Redux-4.1.2-purple)](https://redux.js.org/)
[![License](https://img.shields.io/badge/License-MIT-brightgreen)](./LICENSE)
[![Demo](https://img.shields.io/badge/Demo-Localhost-orange)](http://localhost:3000)

**Proyecto Individual (PI) - Bootcamp Soy Henry**  

> _Catálogo interactivo Full Stack: explora, crea y filtra recetas culinarias con integración de API externa y base de datos propia._

---

## 🌟 Highlights

| Aspecto | Detalle |
|---------|--------|
| **Frontend** | React 17 + Redux + React Router |
| **Backend** | Node.js 16 + Express + Sequelize |
| **Base de Datos** | PostgreSQL 14 |
| **API Externa** | Spoonacular |
| **Funcionalidades** | CRUD completo, búsqueda y filtrado avanzado |
| **Flujo** | DB → API → Frontend |

---

## 📂 Estructura del Proyecto
```
Recipes/
│
├── client/          # Frontend en React
│   ├── src/         # Componentes, Redux, rutas, estilos
│   └── public/      # Assets estáticos
│
└── api/             # Backend Node/Express
├── models/      # Modelos Sequelize
├── routes/      # Endpoints REST
└── controllers/ # Lógica de la API
````

> ✅ Frontend y Backend independientes, comunicándose mediante API REST.



## 🖼 Interfaz (Visual Cards)
---
| Home | Listado de Recetas | Detalle Receta | Crear Receta |
|------|-----------------|----------------|-------------|
| ![Home](./img/home.png) | ![Listado](./img/index.png) | ![Detalle](./img/detail.png) | ![Crear](./img/create.png) |
---
> Navegación intuitiva, filtros interactivos y CRUD completo.



## 🚀 Funcionalidades

- 📋 Listado de recetas con paginación  
- 🔍 Búsqueda por nombre o ingredientes  
- 🥗 Filtrado por tipo de dieta  
- ✏️ Crear, editar y eliminar recetas propias  
- 🌐 Integración de datos de API externa y base de datos interna  


## 👩‍💻 Mi Rol y Aprendizaje

- Diseño y modelado de base de datos relacional (PostgreSQL + Sequelize)  
- Desarrollo de API REST con Node/Express  
- Integración de API externa y datos propios  
- Desarrollo de frontend en React con Redux y React Router  
- Validación de datos y manejo de errores  
- Implementación de flujo completo Full Stack  

## 🧭 Decisiones técnicas
- Utilicé Sequelize para mapear la base de datos y facilitar migraciones.
- Las rutas están organizadas en /api/controllers y /api/routes para separar lógica de ruta.
- Implementé paginación para mejorar performance del listado de recetas.
- Manejo de errores centralizado con middleware de Express para asegurar respuestas consistentes.

## 🧪 Testing (Backend)

Este proyecto incluye **tests automatizados** en el backend, ubicados en `api/tests/`.

Las pruebas están construidas con:
- **Mocha / Chai** para assertions  
- **Supertest-session** para testear endpoints reales  
- Conexión real a la base de datos en entorno controlado  

Los tests cubren:
- Inicialización de la base de datos para cada caso de prueba  
- Creación de datos de ejemplo  
- Test de integración del endpoint `GET /recipes` verificando respuesta **200**  

### ▶️ Ejecutar los tests

Desde la carpeta `api/`:

npm test

## ⚙️ Instalación y Ejecución

### 1️⃣ Clonar repositorio
git clone https://github.com/Priscilla-Rojas/Recipes.git
### 2️⃣ Instalar dependencias
#### Backend
cd Recipes/api
npm install

#### Frontend
cd ../client
npm install

### 3️⃣ Configurar variables de entorno

#### Crear `.env` en `api/` con las siguientes variables:

- DB_USER=tu_usuario
- DB_PASSWORD=tu_contraseña
- DB_HOST=localhost
- DB_NAME=food
- DB_PORT=5432
- API_KEY1=tu_api_key_spoonacular

### 4️⃣ Ejecutar la aplicación
##### Backend
cd api
npm start

##### Frontend
cd client
npm start

La app estará disponible en http://localhost:3000 .
Conectada al backend en http://localhost:3001.

## ✅ Qué demuestra este proyecto

 Flujo completo Full Stack: DB → API → Frontend

 Integración de API externa + base de datos propia

 CRUD completo para recetas

 Filtrado y búsqueda avanzada

 Gestión de estado con Redux

 Validación de datos y manejo de errores

 Aplicación profesional de análisis y diseño de sistemas

## 🔚 Cierre

Este proyecto resume mi capacidad para diseñar y desarrollar una aplicación Full Stack completa, entendiendo el flujo de extremo a extremo: datos → backend → UI → experiencia de usuario.
Integra una API externa, una base de datos propia, una API REST escalable y un frontend en React con gestión de estado y validaciones.

Más allá de las funcionalidades, refleja mi forma de trabajar:
- criterio técnico,
- arquitectura clara,
- código mantenible,
- manejo de errores y validaciones reales,
- y foco en entregar un producto funcional y estable.

Es uno de los proyectos base de mi portfolio y establece el estándar desde el cual continúo desarrollando soluciones cada vez más robustas y orientadas a producción.