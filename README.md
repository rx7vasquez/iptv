# IPTV para iPhone (web app)

Web app para cuentas Xtream Codes. Se instala desde Safari y no depende de ningún ordenador.
Navega por la cuenta directamente contra el proveedor y reproduce en **VLC para iOS**.

## Publicar en GitHub Pages
1. En github.com: **New repository** → nombre p. ej. `iptv` → **Public** → Create.
2. **Add file → Upload files** → arrastra todos los archivos de esta carpeta → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. En 1–2 minutos estará en `https://TU-USUARIO.github.io/iptv/`.

## Instalar en el iPhone
1. Abre esa dirección en **Safari**.
2. **Compartir → Añadir a pantalla de inicio**.
3. Abre la app desde el icono e inicia sesión (la app instalada tiene su propio almacenamiento,
   así que inicia sesión dentro de ella, no solo en Safari).
4. Instala **VLC** desde el App Store.

## Privacidad
- Este repositorio no contiene credenciales. Usuario y contraseña se guardan solo en el iPhone
  (almacenamiento local) y se envían únicamente al servidor del proveedor.
- Al abrir un canal en VLC, la dirección del stream (que incluye las credenciales, como en
  cualquier app Xtream) se pasa a VLC en el propio dispositivo.

## Limitaciones
- El servidor del proveedor debe admitir HTTPS (el tuyo sí: `https://crewplus26.com`).
- "Probar aquí" intenta reproducir dentro de la app, pero si el proveedor sirve el vídeo sin
  cifrar Safari lo bloqueará: para eso está VLC.
