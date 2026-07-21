# SYNERVIX — WEB FINAL

Plataforma educativa desarrollada para el proyecto **Crea y Emprende**.

## Contenido incluido

- Página pública del emprendimiento.
- Diseño moderno, minimalista y adaptable a celular.
- Autenticación real mediante Firebase.
- Recuperación de contraseña.
- Cierre y persistencia de sesión.
- Dos videos tutoriales.
- Enlaces rápidos a herramientas tecnológicas.
- Materiales descargables.
- Formulario conectado a Formspree.
- Contacto directo por WhatsApp.
- Paquetes y precios de lanzamiento.

## Archivos principales

```text
index.html
css/
  styles.css
js/
  app.js
assets/
  images/
    logo-synervix.png
  videos/
    tutorial-herramientas.mp4
    tutorial-proyector.mp4
  materials/
    guia-proyector.txt
    prompts-docentes.txt
    checklist-clase-virtual.txt
```

## Cuenta docente

La cuenta debe existir en Firebase Authentication.

- Correo registrado: `docente@synervix.com`
- Contraseña: la creada por el equipo en Firebase.

## Configuración necesaria en Firebase

1. Abrir Firebase.
2. Ir a **Authentication → Settings / Configuración → Authorized domains / Dominios autorizados**.
3. Agregar:

```text
synervix.github.io
```

4. Confirmar que el proveedor **Correo electrónico/contraseña** esté habilitado.

## Publicación en GitHub Pages

1. Crear un repositorio público llamado `synervix-plataforma`.
2. Extraer este ZIP.
3. Subir **todo el contenido extraído**, no el ZIP.
4. Verificar que `index.html` quede en la raíz.
5. Entrar a:

```text
Settings → Pages
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

6. Guardar.
7. Abrir:

```text
https://synervix.github.io/synervix-plataforma/
```

## Formulario de contacto

El formulario está conectado a:

```text
https://formspree.io/f/xlgqlgjo
```

Después de publicar la web:

1. Realizar una consulta de prueba.
2. Revisar `synervix.oficial@gmail.com`.
3. Confirmar Formspree desde el correo si lo solicita.

## Datos oficiales

- Correo: `synervix.oficial@gmail.com`
- WhatsApp: `+51 984 469 436`

## Nota de seguridad

Firebase protege el inicio de sesión. Sin embargo, como GitHub Pages aloja archivos públicos,
los videos y materiales podrían abrirse si alguien conoce su dirección directa. Para proteger
también los archivos sería necesario almacenarlos en un servicio privado con reglas de acceso.
