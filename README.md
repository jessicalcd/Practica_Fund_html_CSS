# Wonder Woman Portfolio

Este es el proyecto de mi portfolio, inspirado en el personaje ficticio de Wonder Woman. El objetivo de esta práctica es construir un portfolio utilizando únicamente **HTML5** y **CSS3**, sin hacer uso de JavaScript ni librerías externas. El proyecto está diseñado para ser completamente **responsive** y es **mobile-first**.

## Descripción

Este portfolio consta de varias secciones que detallan las habilidades y el perfil de Wonder Woman, presentando también una sección de contacto, un formulario interactivo y un banner con un video en el que aparece un fragmento del tráiler de la película *WW84*.

### Estructura del Proyecto

1. **Header**:
   - Barra de navegación con enlaces a las secciones del portfolio. Además, al pulsar sobre la imagen del **logo** en el **Header**, el usuario es redirigido al inicio de la web.
   - Los enlaces incluyen un efecto de transición al pasar el cursor (hover).
   - La transición de los enlaces no es visible en la versión móvil.

2. **Sección de Descripción**:
   - Breve descripción de Wonder Woman y sus habilidades.
   - Barras de progreso animadas que indican el nivel de habilidad en áreas como fuerza, velocidad y valentía.

3. **Banner**:
   - Imagen de fondo que cambia según el dispositivo (uso de media queries).
   - En dispositivos móviles, la imagen de fondo es diferente para una mejor visualización.

4. **Formulario de Contacto**:
   - Campos de formulario con validación HTML5:
     - Nombre, apellidos, teléfono (campos requeridos).
     - Radio buttons para seleccionar cómo se conoció a Wonder Woman (requerido).
     - Un campo para un tag de GitHub (con validación regex: `^@[^\s]+`).
     - Un mensaje con información adicional (campo requerido, máximo 180 caracteres).
     - Opción de suscribirse a la newsletter (checkbox).
     - Botones de "Guardar" y "Reset" con efecto de transición (hover).

5. **Footer**:
   - Enlaces a redes sociales de Wonder Woman, que redirigen a recursos externos. Al pasar el cursor por el enlace, incluyen un efecto de transición aumentando de tamaño.

6. **Página de Video**:
   - Una página con un video que se reproduce al entrar y aparece con una animación de **fadeIn**.

7. **Página de Proyectos**:
   - Un **grid** que presenta varios proyectos relacionados con Wonder Woman, organizados de manera estética.

### Características Técnicas

- **Sin JavaScript**: Todo el comportamiento dinámico se logra utilizando únicamente **CSS3** (animaciones, transiciones, etc.).
- **Mobile-First**: El diseño está optimizado para dispositivos móviles, utilizando **media queries** para adaptarse a pantallas más grandes.
- **HTML5 y CSS3**: Se hace uso de semántica HTML y se siguen buenas prácticas para la estructuración del contenido.
- **Validación HTML5**: Los formularios tienen validación de entrada para garantizar que los usuarios completen correctamente los campos.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/jessicalcd/Practica_Fund_html_CSS.git

## Cómo funciona

- El **Header** permite navegar entre las distintas secciones del portfolio. Además, al pulsar sobre la imagen del **logo** en el **Header**, el usuario es redirigido al inicio de la web. Al pasar el cursor por encima de los enlaces de navegación, se activa una transición suave.
- En la **Sección de Mis Habilidades**, se presentan las habilidades de Wonder Woman a través de barras de progreso animadas con **CSS**.
- El **Formulario de Contacto** recoge información de los usuarios y la valida con la funcionalidad nativa de HTML5.
- El **Banner** de la página tiene una imagen de fondo que cambia dependiendo del tamaño de la pantalla, usando **media queries**.
- El **Video** en una de las páginas se muestra con una animación de **fadeIn** al cargar la página.
- Los **proyectos** de Wonder Woman se presentan en una página usando un diseño de **grid**.

## Consideraciones

- **Responsive Design**: Este portfolio está diseñado para funcionar en una amplia variedad de dispositivos, desde móviles hasta pantallas grandes.
- **Sin Dependencias Externas**: El proyecto no utiliza ninguna librería o framework externo como Bootstrap. Todo el estilo y la funcionalidad se logran mediante **CSS** puro.
- **Accesibilidad**: Los formularios tienen etiquetas adecuadas y validación para garantizar una experiencia de usuario fluida.



