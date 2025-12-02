# 🍲 Recipes Web App - Frontend

¡Bienvenido al repositorio del Cliente (Frontend) de mi aplicación de Recetas!

Este proyecto es una Single Page Application (SPA) diseñada para buscar, filtrar, ordenar y crear recetas de cocina. Consume datos de una API externa y una base de datos propia, ofreciendo una experiencia de usuario fluida e interactiva.

> **Nota importante:** Este repositorio contiene únicamente el código del **Frontend**.
> El código del **Backend (API)** se encuentra en el siguiente repositorio:
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
* **CSS Modules**: Módulos CSS para el diseño visual.
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

### 📬 Contacto

Si tienes alguna sugerencia o quieres contactarme:
**Priscilla Rojas**
[[LinkedIn](https://www.linkedin.com/in/priscilla-k-rojas/)] | [[Email](mailto:priscilla.k.rojas@hotmail.com)]