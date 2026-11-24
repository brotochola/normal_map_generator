# Normal Maps Web

Generador de mapas para iluminación 2D con preview en tiempo real, 100% en el navegador (un solo `index.html`, sin build ni dependencias).

## Qué hace

- **Mapa normal**: profundidad, desenfoque, invertir X/Y.
- **Bevel**: relieve a partir de la silueta (usa la transparencia de la imagen), con distancia, profundidad, desenfoque y perfil suave.
- **Specular** y **oclusión**: contraste, umbral, brillo, desenfoque, invertir. La oclusión tiene un modo distancia.
- **Tileable**: los desenfoques, gradientes y distancias se repiten en los bordes, y el preview se muestra en 2×2.
- **Preview con luz** que sigue al mouse: difusa, especular, ambiente, colores, toon y pixelado. Vistas: con luz, difuso, normal, specular y oclusión.
- **Exportar**: el normal map en PNG, o todos los mapas (`_n`, `_s`, `_o`) en un `.zip`.

## Uso

Abrí `index.html` en el navegador, o publicalo con GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). Cargá una imagen con el botón o arrastrándola a la ventana.

## Créditos y licencia

Los algoritmos están basados en [Laigter](https://github.com/azagaya/laigter) de Pablo Ivan Fonovich (azagaya), licenciado bajo GPL-3.0.
Este proyecto es una obra derivada y se distribuye bajo **GPL-3.0-or-later** (ver `LICENSE`).
