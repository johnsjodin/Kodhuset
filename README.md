# Kodhuset AB

Umbraco-webbplats för Kodhuset AB. Stilmallen skrivs i Sass och kompileras till CSS.

## Stilmallen

Källfilerna ligger i mappen `Styles`:

- `_variabler.scss`: färger och mått
- `_mixins.scss`: mobilläge och knappar
- `_bas.scss`: grundstil för sidan
- `_komponenter.scss`: knappar och kort
- `main.scss`: samlar alla delar

Sidan läser den kompilerade filen `wwwroot/css/site.css`. Alla mallar länkar till den.

## Kommandon

Installera verktygen:

```
npm install
```

Kompilera en komprimerad stilmall:

```
npm run bygg
```

Kompilera om automatiskt varje gång en fil sparas (avsluta med Ctrl+C):

```
npm run sass
```

Ändra bara i filerna i `Styles`, aldrig direkt i `site.css`. Den skrivs över nästa gång stilmallen kompileras.

## Versioner

- Node.js 24.20.0
- Dart Sass 1.107.0
