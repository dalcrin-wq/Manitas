# Conato

App personal para la casa: mejoras por pasos, mantenimiento periódico, lista de la compra y calendario con guardias.
Un solo `index.html`, sin servidor ni cuentas. Los datos se guardan **en el móvil**, no en GitHub.

## Publicarla (una vez, unos 5 minutos)

1. Entra en [github.com](https://github.com) (crea una cuenta si no tienes).
2. Arriba a la derecha: **+ → New repository**.
   - Nombre: `conato`
   - Visibilidad: **Public** (GitHub Pages gratis lo exige; solo se publica el código, nunca tus datos).
   - Pulsa **Create repository**.
3. En la página del repositorio: **uploading an existing file** (o *Add file → Upload files*).
   Arrastra **todos los archivos de esta carpeta** (no la carpeta) y pulsa **Commit changes**.
4. **Settings → Pages**. En *Build and deployment*: Source **Deploy from a branch**, Branch **main** y **/(root)**. Guarda.
5. Espera uno o dos minutos. Tu app estará en:
   `https://TU-USUARIO.github.io/conato/`

## Instalarla en el móvil

- **Android (Chrome):** abre la dirección, menú **⋮ → Instalar aplicación** (o *Añadir a pantalla de inicio*).
- **iPhone (Safari):** abre la dirección, **Compartir → Añadir a pantalla de inicio**.

Se abre a pantalla completa, con su icono, y funciona sin conexión.

## Pasar tus datos de la versión anterior

Los datos viven en cada "sitio" por separado, así que la app nueva arranca vacía:

1. En la versión que usabas: **Calendario → Copia de seguridad → Exportar JSON** (o *Guardar la app con mis datos*).
2. En la app instalada: **Calendario → Copia de seguridad → Importar** y elige ese archivo.

## Actualizarla

Sube el `index.html` nuevo al repositorio (Add file → Upload files, reemplaza el anterior).
La app instalada descarga la versión nueva por detrás y la muestra la siguiente vez que la abras.
Tus datos no se tocan.

## Copias de seguridad

Haz de vez en cuando **Guardar la app con mis datos**: es un archivo con la app y todo dentro, fotos incluidas.
