# ppal_store

Página de ppal_store: hoodies, camisas, perfumes y AirPods, por mayor y por menor. Negocio en línea de Huehuetenango, Guatemala.

Es una sola página: `index.html` (HTML, CSS y JavaScript juntos). Las fotos ya están dentro del archivo.

## Archivos

| Archivo | Para qué sirve | ¿Obligatorio? |
|---|---|---|
| `index.html` | La página completa | Sí |
| `musica-tienda.mp3` | La música del botón redondo | Sí, si quieres música |
| `README.md` | Esta guía | No |
| `.nojekyll` | Archivo vacío que le dice a GitHub que no procese la página | No (la página funciona sin él) |

`index.html` y `musica-tienda.mp3` deben estar **en la misma carpeta**.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `ppal_store`), público.
2. Entra a **Add file → Upload files** y sube `index.html`, `musica-tienda.mp3` y `README.md`. Confirma con **Commit changes**.
3. (Opcional) Para crear `.nojekyll`: **Add file → Create new file**, escribe `.nojekyll` como nombre y confirma con **Commit changes**. No hace falta escribir nada dentro.
4. Ve a **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda.
6. Espera uno o dos minutos. La página quedará en `https://TU-USUARIO.github.io/ppal_store/`.

Para actualizar la página más adelante, sube el nuevo `index.html` con **Add file → Upload files**. Se reemplaza solo.

## Contacto

- WhatsApp: [+502 5998 7791](https://wa.me/50259987791) y [+502 4870 3470](https://wa.me/50248703470)

## Formulario de contacto

Usa [FormSubmit](https://formsubmit.co). Envía los mensajes a giancarloggonzalez12@gmail.com con copia a diegojoelpalacios@gmail.com. El teléfono o WhatsApp es obligatorio.

Después de publicar, envía un mensaje de prueba desde el formulario. Llegará un correo de activación a giancarloggonzalez12@gmail.com: ábrelo y confirma (revisa también spam). Hasta que lo confirmes, los mensajes no llegan.

## Música

La página reproduce `musica-tienda.mp3` con el botón redondo de abajo a la derecha. Para cambiar la canción, reemplaza ese archivo por otro mp3 con el mismo nombre. El navegador solo deja sonar el audio después de que la persona toca la pantalla una vez. Usa solo música que tengas permiso de usar.

## Si ves un error 404

- `index.html` debe estar en la carpeta principal del repositorio, no dentro de otra carpeta. No subas el `.zip`: descomprímelo y sube los archivos que trae.
- En **Settings → Pages** debe decir **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Después de guardar, espera entre 1 y 10 minutos.
- El repositorio debe ser **público** (con una cuenta gratis, GitHub Pages no funciona en repositorios privados).
- Abre la dirección exacta que aparece arriba en **Settings → Pages**, con la forma `https://TU-USUARIO.github.io/ppal_store/`. Las mayúsculas y minúsculas cuentan.
- Si la página abre pero la música no suena: el archivo debe llamarse exactamente `musica-tienda.mp3` y estar en la misma carpeta que `index.html`. Y recuerda tocar la pantalla una vez, porque el navegador no deja sonar el audio antes.
