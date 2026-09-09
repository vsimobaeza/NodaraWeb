# Nodara — Landing pública (Radar de Capacidad)

Landing de captación de **Nodara** desplegada con **GitHub Pages**:
**https://vsimobaeza.github.io/NodaraWeb/**

Es un repo público que contiene **solo** la web (el repo de producto `Nodara` es privado).

- `index.html` — la landing (autocontenida; formulario en Formspree).
- `og.png` — tarjeta 1200×630 para el preview de LinkedIn.
- `og-source.html` — fuente de la tarjeta; regenerar con Chrome headless si se edita.
- `fuentes/` — los `.woff2` servidos desde el propio sitio. **Viajan siempre con el HTML**:
  sin ellos la página se ve con tipos de reserva.

> **Fuente de la verdad:** el original vive en `captacion/` del repo privado `Nodara`.
> Este repo es una copia para publicar. Editar allí y copiar aquí.

⚠️ **Este repo se llamaba `NudoRedLanding` hasta el 2026-09-09**, cuando el proyecto pasó de
NudoRed a Nodara. **GitHub Pages no redirige el nombre viejo**: la URL anterior
(`…github.io/NudoRedLanding/`) devuelve 404, así que **cualquier enlace repartido antes de esa
fecha está muerto** y hay que volver a mandarlo. Las etiquetas `og:url` y `og:image` de
`index.html` ya apuntan al nombre nuevo — si el repo se vuelve a renombrar, hay que cambiarlas
**en el mismo movimiento** o la tarjeta se rompe.
