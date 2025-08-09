# Sitio de Alan Montoya — Tours Mexicas

Este repositorio contiene un sitio estático (HTML/CSS/JS) listo para publicarse en **GitHub Pages**.

## Publicar en GitHub Pages (sin usar la terminal)

1. Crea un repositorio nuevo en tu cuenta (por ejemplo, `alan-montoya`).
2. Sube los archivos `index.html`, `README.md` y (opcional) `CNAME` usando el botón **Add file → Upload files**.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Source: Deploy from a branch**.
5. En **Branch**, selecciona `main` y la carpeta `/ (root)`. Guarda.
6. Espera 1–2 minutos. Tu sitio estará en `https://TU-USUARIO.github.io/alan-montoya/`.
7. (Opcional) Si tienes dominio propio, configura DNS y el archivo `CNAME` como se indica abajo.

## Editar contenido

Abre `index.html` y edita:
- Datos de contacto (correo, WhatsApp, redes).
- Fechas y puntos de encuentro.
- Imágenes y testimonios.
- SEO (título y meta descripciones).

## Dominio personalizado (ej. alanmontoya.mx)

1. Compra el dominio en tu registrador favorito.
2. En el DNS, crea los siguientes registros **CNAME**:
   - `www` → `TU-USUARIO.github.io.`
   - (Opcional) `@` con un **ALIAS**/ANAME hacia `TU-USUARIO.github.io` si tu registrador lo permite; si no, redirige `@`→`www`.
3. Mantén en el repositorio un archivo llamado `CNAME` con el texto de tu dominio (por ejemplo, `alanmontoya.mx` o `www.alanmontoya.mx`).
4. En **Settings → Pages** del repositorio, establece tu Custom domain y habilita **Enforce HTTPS**.

## Nota
- Si aún no tienes el dominio listo, puedes borrar o editar el archivo `CNAME`.
- El formulario actualmente solo muestra un aviso; para recibir correos, integra un servicio (Formspree, Netlify Forms, o GitHub Actions + API).

## Licencia
Uso personal de Eduardo para el proyecto de Alan Montoya.
