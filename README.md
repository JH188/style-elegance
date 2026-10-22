# Style Elegance — sitio web

Página adaptable a celulares para Style Elegance Barber Shop, ropa deportiva y artículos. Todos los botones de contacto dirigen a WhatsApp.

## Antes de publicar

1. Revisa los datos de contacto y redes en `index.html`.
2. Si el negocio vende productos concretos, reemplaza las tarjetas de ejemplo por nombres, fotos, tallas y precios confirmados.
3. Agrega la ciudad/dirección real del local en el texto y en el JSON-LD de `index.html`. Google necesita datos locales precisos para mostrar resultados cercanos; no publiques una dirección que no sea del negocio.
4. Cuando tengas dominio, cambia `TU-DOMINIO` en `robots.txt` y `sitemap.xml`, y agrega el dominio como URL canónica y de Open Graph en `index.html`.

## Publicar con GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube todos los archivos y la carpeta `assets` manteniendo la estructura.
3. En el repositorio abre **Settings → Pages** y elige publicar desde la rama `main`, carpeta `/ (root)`.
4. Espera a que GitHub Pages muestre la dirección de tu web.

También puedes subir esta carpeta a Vercel como proyecto estático. No necesita instalar dependencias ni base de datos.

## Para que aparezca en Google

- Publicar la web no garantiza aparecer de inmediato ni en los primeros resultados.
- En Google Search Console, agrega y verifica el dominio o la URL de GitHub Pages. Luego envía `sitemap.xml` y solicita indexación de la página principal.
- Usa el nombre, teléfono, dirección y horarios iguales en la web y en el Perfil de Negocio de Google. Completa dirección/ciudad real para búsquedas como “barbería cerca de mí”.
- Comparte la web desde Facebook e Instagram. Mantén actualizados fotos, productos, precios y horarios.

## Archivos

- `index.html`: contenido, SEO básico y datos estructurados.
- `styles.css`: diseño adaptable.
- `script.js`: menú móvil y año automático.
- `assets/`: afiche entregado y favicon.
