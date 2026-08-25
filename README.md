# Homogmos Lab — estructura completa para GitHub Pages

Este paquete conserva el sitio multipágina. Cada ruta tiene su propia carpeta y su propio `index.html`.

## Estructura que debe aparecer en el repositorio

```text
index.html
.nojekyll
README.md
assets/
  styles.css
contacto/
  index.html
proyectos/
  index.html
sobre-mi/
  index.html
servicios/
  index.html
  analisis-visualizacion/
    index.html
  bioinformatica-investigacion/
    index.html
  consultoria-cientifica/
    index.html
  edna-metabarcoding/
    index.html
  genomica-evolutiva/
    index.html
  pipelines-automatizacion/
    index.html
```

## Publicar correctamente

1. Descomprima el ZIP en su computadora.
2. Abra el repositorio `hgmos.lab` en GitHub.
3. Use **Add file → Upload files**.
4. Arrastre **todo el contenido descomprimido de una sola vez**, incluidas las carpetas.
5. Confirme el commit en `main`.
6. Compruebe que GitHub muestre las carpetas `contacto`, `proyectos`, `sobre-mi` y `servicios` en la raíz.

Los estilos también están integrados en cada HTML, por lo que el sitio no depende de que `assets/styles.css` cargue correctamente.
