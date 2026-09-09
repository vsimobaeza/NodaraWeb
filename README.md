# Nodara — Landing pública (Radar de Capacidad)

Landing de captación de **Nodara** desplegada con **GitHub Pages**:
**https://vsimobaeza.github.io/NudoRedLanding/**

Es un repo público que contiene **solo** la web (el repo de producto `nudored` es privado).

- `index.html` — la landing (autocontenida; formulario en Formspree).
- `og.png` — tarjeta 1200×630 para el preview de LinkedIn.
- `og-source.html` — fuente de la tarjeta; regenerar con Chrome headless si se edita.
- `fuentes/` — los `.woff2` servidos desde el propio sitio. **Viajan siempre con el HTML**:
  sin ellos la página se ve con tipos de reserva.

> **Fuente de la verdad:** el original vive en `captacion/` del repo privado `nudored`.
> Este repo es una copia para publicar. Editar allí y copiar aquí.

⚠️ **El proyecto pasó a llamarse Nodara el 2026-09-09** (antes NudoRed). **Los dos repos siguen
con el nombre viejo a propósito**: renombrar `NudoRedLanding` cambia la URL pública de arriba y
rompe la tarjeta que ya está compartida. Cuando se renombren, hay que actualizar `og:url` y
`og:image` de `index.html` **en el mismo movimiento** — están apuntando a este nombre.
