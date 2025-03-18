
# Mini Desafío 2: Consumo de API Pública y Renderizado en React

## ✅ Objetivo
Usar la API pública de **Open Brewery DB** para obtener un listado de cervecerías y mostrarlas en pantalla utilizando React.

## ✅ Requisitos
- Node.js instalado (versión 14 o superior recomendada)
- npm o yarn

## ✅ Pasos para clonar y ejecutar el proyecto

1. **Clona el repositorio:**
```bash
git clone [URL_DEL_REPOSITORIO]
```

2. **Accede al proyecto:**
```bash
cd [nombre-del-proyecto]
```

3. **Instala las dependencias:**
```bash
npm install
# o
yarn install
```

4. **Inicia el proyecto en modo desarrollo:**
```bash
npm start
# o
yarn start
```

La aplicación se abrirá automáticamente en `http://localhost:3000/`

---

## ✅ Instrucciones del desafío

- En la carpeta `Services` encontrarás funciones Axios preconfiguradas.
- En `App.js` tienes un punto de partida con un espacio para mostrar la información.
- Consulta la documentación de la API en [https://www.openbrewerydb.org/documentation](https://www.openbrewerydb.org/documentation).
- Utiliza `getAxios(url)` o adapta la función si es necesario.
- Muestra un listado con:
  - Nombre de la cervecería
  - Tipo de cervecería
  - Ciudad y estado
  - Enlace a su página web (si está disponible)

---

## ✅ Extras opcionales (para destacar):
- Implementar un buscador por nombre o ciudad.
- Añadir estados de carga y error.
- Incorporar paginación si es necesario.
