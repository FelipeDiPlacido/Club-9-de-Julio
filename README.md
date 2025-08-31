# Despliegue y administración del sitio

## Cómo desplegar en Netlify

1. Sube el contenido de esta carpeta a un repositorio en GitHub, GitLab o Bitbucket.
2. Ve a https://app.netlify.com/ y crea una cuenta (o inicia sesión).
3. Haz clic en "Add new site" > "Import an existing project" y conecta tu repositorio.
4. Netlify detectará automáticamente Eleventy (11ty). Si no, usa estos valores:
   - **Build command:** npm run build
   - **Publish directory:** _site
5. Haz clic en "Deploy site".

## Cómo funciona la galería de fotos

Las fotos del club se muestran automáticamente desde una carpeta de Google Drive compartida. Para agregar o quitar fotos, simplemente sube o elimina imágenes en la carpeta de Drive correspondiente a este enlace:

https://drive.google.com/drive/folders/1a5-FMf2A4COcMiozTsKWRon52BAWueyp

Los cambios se reflejan automáticamente en la web.

## Notas
- El diseño es responsivo y funciona bien en móvil.

¿Dudas? Consulta a tu desarrollador de confianza.
