# Proyecto Web

El nombre de la marca es **MONBRO** y los productos se relacionan con el mundo de los simuladores.

## Herramientas utilizadas

Se crearon 5 html para las secciones de "inicio", "productos", "Faq", "contacto" y "nosotros"

### Bootstrap

Se utilizo el "grid layout" en todo el proyecto para hacer el sitio responsive, así como el uso de media queries.

Se utilizó el componente "navbar" en los heacers de todas las secciones, con algunas modificaciones en los estilos

En el index.html se uso el componente "carousell" a los que se les modifico estilos, tamaños y se agregaron animaciones mediante animate.css

En la sección productos se utilizo el componente "cards", personalizando estilos y agregando animaciones con animate.css

### Animate.css

Se usó la libreria de animaciones de **animate.css*. Para el carousell del index.html se utilizó **fade in down*, **fade in up* y **fade in*. Para las cards de products.html se usó
**slide in right*, **slide in right*, **fade in up*, **fade in*. En todos los casos se modifico la duración.-

### Sass

Se crearon carpetas para cada html a excepcion de las equiquetas **footer* y **header* que estan en la raiz del proyecto ya que las mismas son comunes a todos los html

se utilizaron **mixins*, **variables*, **maps* y **each* con el objeto de achicar lineas de código y facilitar su modificación

Se realizo nesting de todas las clases en el que fuera posible

