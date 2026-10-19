# Living Mandalas

The home page for a growing family of interactive mandalas: The Pregnancy and Birth Mandala, The Fourth Trimester Mandala, The Return Mandala, and The Window Mandala.

A single static page (`index.html`). The cards are built from the `MANDALAS` list near the bottom of the file.

## Adding a mandala

1. Save round, 800 × 800 images of its wheel to `img/`, one in light mode and one in dark (WebP with a transparent outside works best).
2. Add an entry to `MANDALAS`: name, link, `img` and `imgDark`, eyebrow, a one-sentence description, alt text, a `tint` pair (an accent colour from its own palette for light and dark mode), and `themeKey`, the localStorage key the mandala keeps its light or dark choice under.

## Light and dark

The page follows the system until the switch is used. The switch saves the choice as `lm-theme`, and also under every mandala's `themeKey` (`pm-theme`, `ft-theme`, `rm-theme`, `wm-theme`). They all share one site, erinsarita.github.io, so each mandala opens in the same mode.

The grid fits as many as there are, up to three across.
