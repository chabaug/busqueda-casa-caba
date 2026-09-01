# Búsqueda Casa CABA

Buscador privado de Casas y PH en venta en Capital Federal (USD 150.000–230.000), armado a partir de un relevamiento combinado de MercadoLibre, ZonaProp y ArgenProp.

Sitio estático, sin backend. Vistos y guardados se persisten en `localStorage` del navegador (por dispositivo).

## Actualizar los datos

Este `index.html` se regenera desde una sesión de Claude Code que scrapea los tres portales y arma el archivo final. Para traer una versión nueva, pedile a Claude que actualice `busqueda_caba` y suba el `index.html` resultante a este repo.

## Publicar / actualizar GitHub Pages

```bash
git add index.html
git commit -m "Actualizar datos"
git push
```

GitHub Pages sirve automáticamente desde `main`.
