Estructura del HTML

Este proyecto está estructurado en varias secciones dentro de un documento HTML.

1. Header y Navegación ("<nav>"):
   - Se utiliza una barra de navegación (navbar) expandible en pantallas grandes con la clase "navbar-expand-lg" y se estiliza utilizando las clases de Bootstrap.
   - La clase "navbar-toggler" permite que el menú de navegación se colapse en pantallas pequeñas, mejorando la experiencia en mobile.
   - Clases utilizadas: "navbar", "navbar-expand-lg", "navbar-brand", "navbar-toggler", "nav-item", "nav-link".

2. Sección de Introducción ("<section>"):
   - La introducción incluye un texto de bienvenida y una imagen circular, estilizada con la clase "img-fluid" de Bootstrap para que la imagen sea reponsive.
   - La imagen también utiliza un borde redondeado con "border-radius" personalizado en el CSS.
   - Clases utilizadas: "intro-section", "container", "row", "col-md-4", "col-md-8", "img-fluid".

3. Galería de Proyectos ("<section>"):
   - Los proyectos están organizados en una cuadrícula de 3 columnas utilizando "col-md-4" de Bootstrap para adaptarse bien a pantallas medianas y grandes.
   - Cada proyecto es una tarjeta (card) estilizada con Bootstrap y clases personalizadas para agregar efectos de hover y sombra.
   - Clases utilizadas: "container", "row", "col-md-4", "card", "project-card", "card-body", "card-title", "card-text".

4. Formulario de Contacto ("<section>"):
   - El formulario de contacto está centrado y usa la clase "form-control" de Bootstrap para estilizar los campos de entrada y texto.
   - El botón de envío usa la clase "btn" de Bootstrap y se personaliza con un gradiente de color.
   - Clases utilizadas: "container", "form", "form-control", "btn", "mb-3".

5. Footer ("<footer>"):
   - El footer incluye enlaces a redes sociales con iconos de Font Awesome y está alineado al centro con estilos personalizados.
   - Clases utilizadas: "container", "text-center", "social-links", "fab", "fa-linkedin", "fa-github".

Bootstrap

- Grid System: Utilizado en las secciones de introducción y proyectos, Bootstrap permite dividir la página en columnas ("col-md-4", "col-md-8") y organizar el contenido de manera responsive.
  
- Navbar: Se utiliza la clase "navbar" para la barra de navegación. La clase "navbar-expand-lg" permite que la barra sea colapsable en dispositivos más pequeños.

- Cards: La clase "card" se utiliza para las tarjetas de proyectos, con personalización adicional como sombras y efectos hover para hacerlas más atractivas.

- Formularios: Los campos del formulario están estilizados con las clases "form-control" de Bootstrap para inputs, y el botón con "btn".

CSS

- Gradientes: Se aplican gradientes de color en el "navbar" y en la sección de introducción utilizando CSS ("linear-gradient").
  
- Hover Effects: Las tarjetas de los proyectos tienen efectos de transformación y sombra al hacer hover, lo que se logra con transiciones CSS en las clases ".project-card".

- Imagen Redondeada: La imagen de la sección de introducción está estilizada para ser circular con "border-radius" y un borde blanco aplicado en CSS.
