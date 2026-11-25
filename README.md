# Cuaderno de Rodaje

Cuaderno de consulta de Ronald Guzmán Dávila: filosofía y habilidades blandas aplicadas al oficio audiovisual y musical, tendencias de video, banco de ideas y referentes documentales.

**Ver en línea:** https://guzmandavila.github.io/cuaderno-de-rodaje/

## Archivos

- `index.html`: la página, sin dependencias de compilación.
- `entradas.json`: las fichas del cuaderno. Cada ficha tiene `categoria` (`filosofia`, `tendencias`, `ideas` o `referentes`), `titulo`, `resumen`, `detalle`, `aplicacion`, `autor`, `anio`, `plataforma`, `estado`, `enlace`, `etiquetas` y `orden`.

## Probar en tu computadora

La página carga `entradas.json` con `fetch`, así que necesita un servidor local:

```bash
python3 -m http.server 8000
```

Luego abre http://localhost:8000
