# Blue Flex Systems — Landing page

Sitio estático (HTML + imágenes). No requiere PHP, base de datos ni build.

## Estructura
```
index.html        ← página completa (estilos, fuentes y logos incluidos)
assets/img/       ← fotos de productos y aplicaciones
assets/           ← logo y favicon
.htaccess         ← caché y compresión (Hostinger / Apache)
```

## Publicar
**GitHub Pages:** sube esta carpeta a la raíz del repo → Settings → Pages → Branch `main` / root. URL: `https://<usuario>.github.io/<repo>/`

**Hostinger:** hPanel → Administrador de archivos → `public_html/` → sube todo el contenido de esta carpeta (no la carpeta en sí).

**Netlify / Vercel:** arrastra la carpeta o conecta el repo; sin comando de build, directorio de publicación `/`.

## Pendientes antes de producción
- Reemplazar fotos de `assets/img/` por originales en alta resolución (mismos nombres de archivo).
- Confirmar correo (`ventas@blueflex.com.mx`) y número de WhatsApp (`525591801745`).
- El formulario abre WhatsApp con el mensaje prellenado. Si se requiere envío por correo, agregar un `enviar.php` en Hostinger.
- Enlazar "Aviso de privacidad".
