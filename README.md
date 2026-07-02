# Portal de Utilidades y Herramientas de OPRobots

Repositorio independiente para las utilidades y herramientas de OPRobots,
desplegado en [utils.oprobots.org](https://utils.oprobots.org/).

Este repositorio contiene las herramientas originalmente alojadas en
la sección `/utils-helpers/` de [oprobots.org](https://oprobots.org/).

## Herramientas incluidas

- **[Maze Wall Placer](./maze-wall-placer/)** — Editor interactivo de
  laberintos para generar arrays de Bits y ASCII.
- **[OSHWDem Maze Generator](./oshwdem-maze-generator/)** — Port del
  generador oficial de laberintos de la OSHWDem.
- **[Timer Countdown](./timer-countdown/)** — Configura un contador
  regresivo para competiciones.
- **[Time-based Turn Profiles Generator](./time-based-turn-profiles-generator/)** —
  Generador de perfiles de giro MicroMouse basado en tiempos T1, T2, T3.

## Tecnologías

- HTML/CSS/JS estático (sin build system)
- [Material Kit v2.0.4](https://demos.creative-tim.com/material-kit/index.html) (Bootstrap 4)
- [Google Charts](https://developers.google.com/chart) (solo en Turn Profiles Generator)
- Google Fonts, Font Awesome, ScrollReveal (CDN)

## Desarrollo

Para desarrollar localmente, simplemente abre los archivos HTML en tu navegador
o sirve el directorio con cualquier servidor HTTP estático:

```bash
python3 -m http.server 8000
```

## Licencia

Este proyecto está bajo la licencia [PolyForm Noncommercial 1.0.0](./LICENSE).
El framework Material Kit es de [Creative Tim](https://www.creative-tim.com/).
