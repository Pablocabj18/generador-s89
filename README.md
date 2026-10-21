# Generador de hojas S-89

Herramienta web estática para preparar hojas individuales S-89 a partir de los PDF mensuales.

## Publicar gratis con GitHub Pages

1. En GitHub, crea un repositorio nuevo llamado `generador-s89`.
2. Para que GitHub Pages gratis funcione de la forma más sencilla, selecciona **Public**. No subas PDF con nombres ni datos personales al repositorio.
3. En el repositorio, pulsa **Add file → Upload files**.
4. Sube `index.html` (y opcionalmente este `README.md`) desde esta carpeta.
5. Entra en **Settings → Pages**.
6. En **Build and deployment**, selecciona **Deploy from a branch**.
7. Selecciona la rama `main` y la carpeta `/(root)`, luego pulsa **Save**.
8. Espera a que termine la publicación. La dirección será similar a `https://TU-USUARIO.github.io/generador-s89/`.

## Agregar al inicio del iPhone

1. Abre la dirección publicada en Safari.
2. Pulsa **Compartir**.
3. Selecciona **Agregar a pantalla de inicio**.
4. Pulsa **Agregar**.

## Nota

La app utiliza PDF.js desde un CDN para leer los PDF en el navegador. Probá el resultado con una copia de tus documentos antes de usarlo para todas las asignaciones: la detección automática de nombres y la posición de los textos pueden requerir ajustes según el formato de los PDF.
