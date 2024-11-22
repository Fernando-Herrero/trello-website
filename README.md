# Clonación de Trello 🗂️

Este proyecto consiste en la clonación de la interfaz de la aplicación web **Trello**, diseñada para gestionar tareas y proyectos de forma visual. Ha sido desarrollado como un ejercicio práctico para aplicar conocimientos en HTML, CSS y diseño responsive, siguiendo una metodología **mobile-first**.

## 📄 Descripción

La web fue creada a partir de una visualización en archivos PDF que mostraban las diferentes vistas de la página en tamaños **desktop**, **tablet** y **mobile**. Su estructura y diseño se basan en:

- Un archivo `index.html` que organiza el contenido de la página.
- Tres archivos CSS:
  - `global.css` para estilos generales reutilizables.
  - `index.css` que incluye clases específicas, comenzando con el diseño **mobile**.
  - `responsive.css` donde se implementan las **media queries** para tablet y otros tamaños.
- Una carpeta `media` que contiene las imágenes necesarias para el diseño.
- Una carpeta `recursos` donde se encuentran los archivos PDF que sirvieron de guía para replicar las diferentes dimensiones de la página.

El objetivo del proyecto fue replicar el diseño con precisión mientras se garantiza una experiencia de usuario óptima en cualquier dispositivo.

## 🚀 Live Preview

Accede al proyecto desde el siguiente enlace: **[Ver Proyecto en Vivo](https://trello-website-clone.netlify.app)**

## 🛠️ Tecnologías utilizadas

- **HTML5**: Para la estructura semántica del contenido.
- **CSS3**: Para el diseño visual y estilos.
- **Metodología Mobile-First**: Diseño que prioriza dispositivos móviles antes de adaptarlo a pantallas más grandes.
- **Responsive Design**: Adaptación de estilos mediante media queries.

## 🏗️ Estructura del proyecto

1. **`index.html`**:
   - Contiene la estructura principal del proyecto.
   - Organización de elementos basándose en el diseño de Trello.

2. **Archivos CSS**:
   - **`global.css`**: Definición de estilos reutilizables como colores, tipografía y clases genéricas.
   - **`index.css`**: Clases específicas y diseño para la versión móvil.
   - **`responsive.css`**: Media queries para adaptar el diseño a **tablet** y **desktop**.

3. **Carpeta `media`**:
   - Contiene todas las imágenes utilizadas en el diseño del proyecto.

4. **Carpeta `recursos`**:
   - Incluye los archivos PDF con las visualizaciones de la página en diferentes tamaños: **mobile**, **tablet** y **desktop**.

## 🌟 Buenas prácticas implementadas

- **Separación de responsabilidades**: Cada archivo CSS tiene un propósito claro.
- **Metodología Mobile-First**: Garantiza que la página sea funcional en dispositivos móviles desde el inicio.
- **Uso semántico de HTML**: Mejora la accesibilidad y el SEO.
- **Código limpio y organizado**: Facilita la legibilidad y el mantenimiento del proyecto.

## 📐 Retos del proyecto

1. **Adaptación al diseño a partir de PDFs**: Requiere interpretar los tamaños y proporciones exactas.
2. **Implementación responsive**: Asegurarse de que todos los elementos sean completamente adaptables a diferentes tamaños de pantalla.
3. **Gestión modular del CSS**: Separar estilos generales de específicos y responsivos sin redundancias.

## 📸 Vistas

| Vista            | Dispositivo | Descripción                                        |
|-------------------|-------------|----------------------------------------------------|
| **Mobile**        | Teléfonos   | Diseño inicial, optimizado para pantallas pequeñas.|
| **Tablet**        | Tablets     | Ajustes específicos mediante media queries.        |
| **Desktop**       | Computadoras| Diseño final con mayor distribución espacial.      |