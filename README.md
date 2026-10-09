# La Diez | Camisetas de Messi

Sitio web de una tienda ficticia de camisetas con el número 10 (selección, clubes y ediciones alternativas). Es el Proyecto 1 (pre-entrega) del curso y sirve para practicar HTML semántico, CSS, diseño responsivo y publicación en GitHub Pages.

> Proyecto educativo. No tiene relación con Lionel Messi ni con ningún club o selección.

## Propósito de la página

Mostrar los productos de la tienda, las reseñas de clientes y un formulario para que las personas puedan enviar consultas.

## Estructura de archivos

- `index.html`: página principal (`header`, `nav`, `main`, `section`, `footer`).
- `styles.css`: estilos externos.
- `images/`: logo y camisetas en formato SVG.
- `video.mp4` y `subtitulos.vtt`: video de presentación con subtítulos en español.

## Secciones

| Sección | Contenido | Técnica |
|---|---|---|
| Inicio | Presentación con imagen | Fondo con degradado |
| Productos | Cards con imagen, descripción, precio y botón | Flexbox |
| Conocé la tienda | Video con subtítulos | `<video>` y `<track>` |
| Reseñas | Opiniones de clientes | Grid |
| Contacto | Formulario, mapa (iframe) y tabla de mensajes | Grid y Media Queries |

## Cómo configuré Formspree

1. Me registré en [formspree.io](https://formspree.io) y confirmé mi correo.
2. Creé un formulario nuevo con el nombre "Contacto".
3. Copié la URL que me dio Formspree y la usé en el atributo `action` del formulario, con `method="POST"`.
4. Cada campo (`nombre`, `email`, `mensaje`) tiene su atributo `name`, para que Formspree reciba los datos.

**Por qué es útil:** un sitio estático (como el de GitHub Pages) no tiene servidor para procesar formularios. Formspree recibe los datos y los reenvía a mi correo, sin necesidad de programar un backend.

## Tecnologías

- HTML5 semántico y CSS3 (Flexbox, Grid, Media Queries), con clases nombradas con metodología BEM
- Google Fonts: Anton (títulos) y Work Sans (párrafos)
- Font Awesome (íconos)
- Formspree (envío del formulario)

## Publicación

- Repositorio: `https://github.com/TU-USUARIO/TU-REPOSITORIO`
- Sitio publicado: `https://TU-USUARIO.github.io/TU-REPOSITORIO/`
