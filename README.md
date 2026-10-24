# MZN Customs

Sitio estático de MZN Customs & Cargo Solutions.

## Antes de publicar

- Crea un formulario en Formspree y pega su URL pública (`https://formspree.io/f/...`) en `CONFIG.formEndpoint` al final de `index.html`. Completa también `CONFIG.privacyContact` y `CONFIG.privacyAddress`, actualiza `aviso-privacidad.html` y cambia `CONFIG.privacyNoticeReady` a `true`; hasta entonces, el formulario permanece oculto.
- Sustituye la ruta relativa de `og:image` en `index.html` por la URL absoluta de `social-preview.webp` en el dominio público del sitio. El dominio de producción aún no está definido.
- Completa el aviso de privacidad con el domicilio legal, el correo para solicitudes sobre datos, los plazos de conservación y las transferencias aplicables antes de habilitar la recolección de datos.
