# Frontend - Reseñas y Servicios

Este proyecto es el frontend de una aplicación para gestionar servicios y reseñas. Permite a los usuarios interactuar con las funcionalidades del backend a través de una interfaz web.

## Tecnologías Utilizadas

- **React**
- **Axios**
- **React Router DOM**
- **HTML5 & CSS3**

## Estructura del Proyecto

- `components`: Componentes de React para diferentes partes de la interfaz.
  - `Login.jsx`
  - `Register.jsx`
  - `ViewReviews.jsx`
  - `RateService.jsx`
  - `CompareServices.jsx`
- `App.js`: Configuración de las rutas principales.

## Requisitos Previos

1. **Node.js** instalado.
2. **npm** o **yarn** para manejar dependencias.

## Configuración del Proyecto

1. Clonar el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. Ir al directorio del frontend:
   ```bash
   cd frontend
   ```

3. Instalar las dependencias:
   ```bash
   npm install
   ```

## Ejecución del Proyecto

1. Iniciar el servidor de desarrollo:
   ```bash
   npm start
   ```

2. Abrir el navegador en `http://localhost:3000`.

## Funcionalidades

### Reseñas
- Ver todas las reseñas.
- Filtrar reseñas por rango de fechas.
- Comparar porcentajes de reseñas dentro y fuera del rango seleccionado.

### Servicios
- Calificar servicios.
- Comparar servicios por criterios como calificación y precio.

### Seguridad
- Login y registro de usuarios.
- Redirección automática al login si no se está autenticado.

## Configuración de Axios
En el archivo `AxiosConfig.js` (si existe), asegúrate de que la URL base sea correcta:
```javascript
axios.defaults.baseURL = "http://localhost:8085/api/v1";
```

## Scripts Disponibles

- `npm start`: Inicia el servidor de desarrollo.
- `npm run build`: Genera los archivos para producción.

## Notas Adicionales

- Asegúrate de que el backend esté corriendo en `http://localhost:8085` antes de iniciar el frontend.
- Las rutas protegidas están configuradas para redirigir al login si el usuario no está autenticado.

---
