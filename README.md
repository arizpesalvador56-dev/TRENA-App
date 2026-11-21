# TRENA · Your Performance, Your Way

App web de entrenamiento personalizada. Cada persona contesta un cuestionario corto y recibe su rutina, plan de carrera, dieta y tracker de progreso.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `TRENA-App`.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. Ve a Settings, luego Pages. En "Branch" elige `main` y la carpeta `/ (root)`. Guarda.
4. En unos minutos queda en `https://arizpesalvador56-dev.github.io/TRENA-App/`.

## Conectar tu dominio
1. En Settings, luego Pages, escribe tu dominio en "Custom domain", por ejemplo `trena.mx`.
2. En el panel de tu proveedor de dominio agrega estos registros DNS:
   - Cuatro registros `A` para `@` apuntando a 185.199.108.153, 185.199.109.153, 185.199.110.153 y 185.199.111.153
   - Un registro `CNAME` para `www` apuntando a `TU-USUARIO.github.io`
3. Cuando GitHub lo verifique, activa "Enforce HTTPS".

## Cómo se guardan los datos
Todo se guarda solo en el navegador de cada persona, sin cuentas ni botones. Si alguien cambia de celular puede usar "Copiar respaldo" en Extras. La sincronización entre dispositivos necesita agregar login y base de datos más adelante.

## Archivos
- `index.html` la app completa
- `manifest.webmanifest` e íconos para instalarla en la pantalla de inicio con el logo de TRENA
- `sw.js` hace que funcione sin internet después de abrirla una vez
