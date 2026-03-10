# 🍲 Food Recipes – Frontend (Client)

![React](https://img.shields.io/badge/React-18-blue)
![Redux](https://img.shields.io/badge/Redux-Toolkit-purple)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![CSS](https://img.shields.io/badge/CSS3-Modules-orange)
![Axios](https://img.shields.io/badge/Axios-HTTP-lightgrey)

Aplicación web (SPA) diseñada para explorar el mundo culinario. Este cliente consume la API REST del proyecto para visualizar recetas, aplicar filtros combinados y gestionar la creación de nuevo contenido.
Se enfoca en una experiencia de usuario (UX) fluida y un diseño responsivo.

> **Nota de Arquitectura:** Este repositorio contiene el código del **Frontend**.
> El Backend (API) necesario para su funcionamiento se encuentra aquí:
> 👉 [**Recipes API Repository**](https://github.com/Priscilla-Rojas/Recipes-Api)

<!-- ## 🚀 Despliegue (Deploy)

Puedes ver la aplicación funcionando aquí:
🔗 **[Link a deploy en Vercel/Netlify]** -->

## 🖼️ Capturas de Pantalla

![Landing Page](./src/assets/img/home.png)
*Vista de la Landing Page*

![Home Page](./src/assets/img/index.png)
*Vista principal con listado de recetas y paginado*

![Create Page](./src/assets/img/create.png)
*Vista del formulario para crear nuevas recetas*

## 🛠️ Tecnologías Utilizadas

El frontend fue construido utilizando las siguientes tecnologías y librerías:

* **React**: Construcción de componentes e interfaz de usuario.
* **Redux**: Manejo del estado global (store) para recetas, filtros y ordenamientos.
* **Axios / Fetch**: Para realizar las peticiones HTTP a la API.

## ✨ Funcionalidades

* **Landing Page:** Página de bienvenida con imagen representativa y botón de ingreso.
* **Home:**
    * Visualización de tarjetas de recetas.
    * **Búsqueda:** Barra de búsqueda para encontrar recetas por nombre.
    * **Filtros:** Filtrado por tipo de dieta (Gluten Free, Vegan, etc.) y origen (API o Base de Datos).
    * **Ordenamiento:** Orden alfabético (A-Z, Z-A) y por "Health Score".
    * **Paginado:** Navegación optimizada para ver múltiples recetas.
* **Detalle:** Vista exclusiva con información detallada de la receta (resumen del plato, paso a paso, dietas, score).
* **Formulario de Creación:** Formulario controlado con validaciones en JavaScript para agregar nuevas recetas a la base de datos.

## ⚙️ Instalación y Ejecución Local

Sigue estos pasos para correr el proyecto en tu máquina local:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/Priscilla-Rojas/Recipes-Front.git](https://github.com/Priscilla-Rojas/Recipes-Front.git)
    ```

2.  **Instalar dependencias:**
    Navega a la carpeta del proyecto y ejecuta:
    ```bash
    npm install
    ```

3.  **Iniciar la aplicación:**
    ```bash
    npm start
    ```
    La aplicación correrá en `http://localhost:3000`.

---

## 📂 Estructura del proyecto
```
client/
├── public/          # Assets estáticos
├── src/
│   ├── components/  # Componentes reutilizables (Cards, Nav, etc.)
│   ├── views/       # Vistas principales (Home, Landing, Form)
│   ├── redux/       # Actions y Reducers (Store)
│   ├── styles/      # Módulos CSS / Estilos globales
│   └── App.js       # Rutas y renderizado principal
└── package.json
```
## 🔄 Flujo de Datos

User Interaction ↔ React Components ↔ Redux Actions ↔ Axios ↔ API Backend

## 👩‍💻 Mi rol y responsabilidades
* Diseño y arquitectura de componentes (React).
* Implementación del ciclo de vida de la aplicación.
* Gestión del estado asíncrono y síncrono (Redux).
* Validaciones de formularios y UX.
* Consumo de servicios REST.
* Diseño visual (CSS puro/Modules).
* Diseño visual (CSS puro/Modules).

## 📬 Contacto
Priscilla Rojas 
🔗[LinkedIn](https://www.linkedin.com/in/priscilla-k-rojas/)
📫[Mail](priscilla.k.rojas@hotmail.com)
