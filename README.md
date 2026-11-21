# Gosset & Shewhart: sitio web

Sitio estático (HTML, CSS y JS en un solo archivo) en español e inglés, con botón para cambiar de idioma. No necesita compilación.

## Archivos

- `index.html`: la página completa.
- `favicon.svg`: ícono de la pestaña (concepto "punto fuera de control").
- `README.md`: este archivo.

## Antes de publicar: cambia esto

1. En `index.html`, busca `contacto@TU-DOMINIO.com` (aparece dos veces en la sección de contacto) y pon tu correo real.
2. Revisa los textos de "Qué hacemos": son áreas de enfoque genéricas; ajústalas a lo que realmente ofreces.
3. Cambia el año del pie de página si hace falta.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `gosset-shewhart`; si lo llamas `TU-USUARIO.github.io`, el sitio quedará en la raíz de ese dominio).
2. Sube los archivos: en la página del repositorio, **Add file → Upload files**, arrastra `index.html`, `favicon.svg` y `README.md` y haz commit.
3. Ve a **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
4. Espera uno o dos minutos. La URL aparece arriba en esa misma pantalla: `https://TU-USUARIO.github.io/gosset-shewhart/`.

## Dominio propio (opcional)

En **Settings → Pages → Custom domain** escribe tu dominio y crea los registros DNS que GitHub indique. Activa **Enforce HTTPS** cuando esté disponible.

## Notas

- La tipografía (Inter) se carga desde Google Fonts. Si prefieres no depender de un servicio externo, descarga la fuente y sírvela desde el repositorio.
- El sitio respeta la preferencia "reducir movimiento" del sistema: sin animaciones para quienes la tengan activada.
- Los datos históricos de Gosset (1908) y Shewhart (1924) vienen de fuentes públicas; verifícalos si los vas a usar en material formal.
