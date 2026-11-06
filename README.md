# Daniela Heels — Web oficial

Web de una sola página de **Daniela Heels**, cantante de soul, funky y jazz en Ibiza.

## Contenido

```
index.html      La web completa (HTML, estilos y código en un solo archivo)
fotos/          Fotos optimizadas y logo (logo.png con fondo transparente)
```

No necesita instalación ni compilación: es HTML estático. Las tipografías (Bodoni Moda y Manrope) se cargan desde Google Fonts.

## Secciones

- Portada
- Sobre mí
- Vídeos (enlazan a YouTube)
- Eventos
- Galería (con visor a pantalla completa)
- Contacto: WhatsApp, email y redes. El formulario abre WhatsApp con el mensaje ya escrito.
- Botón flotante de WhatsApp

## Datos de contacto en la web

- WhatsApp: 651 741 512
- Email: info@danielaheelsmusic.com
- Instagram: https://www.instagram.com/danielaheelsmusic/
- Facebook: https://www.facebook.com/danielaheels
- YouTube: https://www.youtube.com/@danielaheels8879

## Cómo editar

- **Textos:** busca el texto en `index.html` y cámbialo.
- **Fotos:** sustituye el archivo en `fotos/` manteniendo el mismo nombre, o cambia la ruta en `index.html`.
- **Colores:** están al principio del `<style>`, en el bloque `:root` (`--gold`, `--gold-hi`, `--gold-lo`, `--ink`...).

## Publicar

### En Hostinger
Sube `index.html` y la carpeta `fotos/` a `public_html`.

### En GitHub Pages (gratis)
1. Repositorio → **Settings → Pages**.
2. En *Source*, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
3. Para usar el dominio propio, escribe `danielaheelsmusic.com` en *Custom domain* y configura los DNS del dominio según indica GitHub.
