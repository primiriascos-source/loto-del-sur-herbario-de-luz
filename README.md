# Herbario de Luz

Micrositio editorial para una **propuesta académica de vitrinismo** inspirada en Loto del Sur. No es una página oficial de la marca.

**Concepto:** Herbario de Luz. Cuando la botánica despierta, comienza el ritual.

## Entregables del corte 2

El sitio responde a los seis puntos de la guía `Proyecto corte 2 26-2.pdf`:

1. **Concepto narrativo** (`#concepto`): título, historia del herbario nocturno y emoción buscada.
2. **Ficha de decisiones** (`#ficha`): producto protagonista, distribución, recorrido, tres principios, paleta y materiales.
3. **Boceto** (`#boceto`): lámina frontal aportada, con puntos interactivos sobre los elementos principales.
4. **Prompt utilizado** (`#prompt`): instrucción exacta usada para generar el render final, también en `PROMPT-UTILIZADO.md`.
5. **Imagen generada con IA** (`#resultado`): `assets/herbario-final-prompt-utilizado.jpg`.
6. **Justificación** (`#justificacion`): relación entre imagen y concepto, evaluación del primer estudio y ajustes realizados.

La imagen aportada por el usuario se conserva intacta en `assets/lamina-herbario-usuario.png`; su mitad izquierda aparece como boceto. El primer estudio visual se conserva en `assets/herbario-render-final.jpg`. El prompt original de la lámina aportada se desconoce: `PROMPT-RECONSTRUIDO.md` es una ingeniería inversa visual y **no** se presenta como prompt histórico. El prompt efectivamente usado para el resultado final está en `PROMPT-UTILIZADO.md`.

[ENTREGA-CORTE-2.md](ENTREGA-CORTE-2.md) reúne las seis respuestas en formato breve para exponer o revisar.

## Archivos

- `index.html`: contenido y estructura semántica.
- `styles.css`: dirección de arte, responsive y recortes de la lámina.
- `script.js`: navegación, apariciones, luz exploratoria, capas del boceto y comparador.
- `assets/lamina-herbario-usuario.png`: lámina aportada con boceto y render de referencia.
- `assets/herbario-final-prompt-utilizado.jpg`: imagen final generada con IA a partir del prompt documentado.
- `PROMPT-UTILIZADO.md`: prompt final y campos verificados.
- `PROMPT-RECONSTRUIDO.md`: reconstrucción del prompt de la lámina aportada.

## Abrir y publicar

Abra `index.html` o sirva la carpeta con un servidor estático. No requiere compilación ni backend. Las rutas son relativas y funcionan en un subdirectorio de GitHub Pages.

Para publicar en GitHub Pages, suba el contenido de esta carpeta a la raíz de un repositorio y active **Settings → Pages → Deploy from a branch → main → / (root)**. El archivo `.nojekyll` evita procesamientos de Jekyll.

## Accesibilidad

Incluye navegación por teclado, botón de salto, texto alternativo, contraste, menú móvil, controles del boceto y comparador operables con teclado, y respeto de `prefers-reduced-motion`.

## Referencia de marca

[Sitio oficial de Loto del Sur](https://www.lotodelsur.com/). La paleta, los materiales y la iluminación de este micrositio son interpretaciones académicas, no una identidad oficial.
