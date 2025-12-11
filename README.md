# Triple Espresso

Descripción del Proyecto

El proyecto consiste en el desarrollo de una página web para el restaurante "Restaurante TripleTen-tación", cuyo objetivo es presentar información relevante sobre el establecimiento, mostrar recetas destacadas y permitir a los usuarios reservar una mesa mediante un formulario interactivo. El diseño sigue una estructura clara, modular y escalable, basada en la metodología BEM (Block, Element, Modifier) para garantizar mantenibilidad, reutilización y coherencia en los estilos.

La interfaz está dividida en secciones principales:

Header: Incluye navegación, título principal, descripción y una imagen representativa del local.

Recipes: Muestra videos incrustados desde YouTube y sus descripciones breves.

Reservation: Contiene un formulario con validación HTML nativa para que los usuarios ingresen nombre, número de comensales, fecha, correo y consentimiento de términos.

Footer: Presenta los enlaces a redes sociales y los datos del autor.

La arquitectura del proyecto utiliza archivos CSS separados dentro de la carpeta /blocks, uno por cada bloque funcional (header, nav, page, recipes, form, reservation, footer). Esto asegura una clara separación de responsabilidades y facilita el mantenimiento del código.

Tecnologías utilizadas

HTML5: para la estructura semántica de las secciones.

CSS3: para el diseño visual, incluyendo uso de Flexbox y estilos responsivos.

Metodología BEM: para estandarizar nombres de clase y modularizar estilos.

Google Fonts (Inter y Noto Serif): para una mejor experiencia tipográfica.

YouTube Embed API: para mostrar videos dentro del apartado de recetas.
