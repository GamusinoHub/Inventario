# Inventario de cajas (web app instalable)

Todo se guarda en el iPhone. No hay servidor ni cuenta. La página de GitHub solo entrega la app.

## Publicar en GitHub Pages (una vez)
1. Crea un repositorio nuevo en GitHub (público; GitHub Pages gratis lo exige).
2. Sube a la raíz del repositorio estos 6 archivos: index.html, sw.js, manifest.webmanifest, icon-180.png, icon-192.png, icon-512.png.
3. En el repositorio: Settings → Pages → Source: "Deploy from a branch" → Branch: main, carpeta / (root) → Save.
4. Espera uno o dos minutos. La dirección queda como https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/

## Instalar en el iPhone (con internet)
1. Abre esa dirección en **Safari**.
2. Compartir → "Añadir a pantalla de inicio".
3. Abre la app desde el ícono nuevo, una vez, con internet. Así guarda todo para usarlo sin conexión.
4. Prueba: activa el modo avión y ábrela de nuevo. Debe abrir.

## Reglas importantes
- Captura y consulta **solo desde el ícono instalado**. Safari y el ícono guardan datos por separado.
- Escanea los QR con el botón "Escanear" dentro de la app. La cámara normal del iPhone solo muestra el texto de la etiqueta.
- Exporta un respaldo seguido (Respaldo y etiquetas → Exportar respaldo) y guárdalo en Archivos / iCloud Drive. Si borras la app o el iPhone limpia su almacenamiento, los datos se pierden.
- En la laptop: abre la misma dirección en Safari o Chrome, e importa el respaldo para ajustar. Para pasar los cambios al iPhone, exporta en la laptop e importa en el iPhone. Se conserva la versión más reciente de cada caja.
- Actualizar la app: sube el archivo nuevo a GitHub y cambia `cajas-v1` por `cajas-v2` en sw.js.
