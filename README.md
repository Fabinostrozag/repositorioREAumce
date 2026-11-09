# Repositorio de REA sobre ciudadanía digital · UMCE 2026

Trabajos finales del módulo *Fundamentos de las TIC para la educación y Ciudadanía digital* del
Diplomado en Inteligencia Artificial y Tecnologías Digitales para Transformación Educativa (UMCE).

## Contenido

- `index.html`: la página completa (diseño, datos y funciones en un solo archivo).
- `fichas/`: fichas técnico-pedagógicas en PDF de cada grupo.
- `LICENSE.md`: licencia del sitio (CC BY-NC-SA 4.0).
- `.nojekyll`: indica a GitHub Pages que publique los archivos tal cual.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub (por ejemplo, `repositorio-rea-umce`).
2. Sube todos los archivos de esta carpeta con **Add file → Upload files** y confirma con **Commit changes**.
3. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En uno o dos minutos el sitio queda disponible en `https://<tu-usuario>.github.io/repositorio-rea-umce/`.

## Agregar o corregir un REA

Abre `index.html` y edita la lista `REA` que está al inicio del bloque `<script>` (al final del archivo).
Para sumar una ficha, copia el PDF en `fichas/` y escribe su ruta en el campo `ficha`.
Para mostrar el botón de instrucciones del trabajo final, guarda el PDF en `fichas/` y escribe su ruta en `INSTRUCCIONES`.
