# Citizen Quest: Quantum Quest

A game about the mathematics of Quantum Computing.

Based on the interactive exhibit [Citizen Quest](https://github.com/IMAGINARY/citizen-quest),
developed by [Imaginary](https://about.imaginary.org/) for [Futurium](https://futurium.de/de/citizen-quest).

Part of the Quantum Arcade project by BMBF with partners MPI-MiS and Leipzig University (SCADS.AI).

## Building

Requires Node.js (v18.19 or greater) and npm.

Run the following from the root directory of the project:

```bash
npm install
npm run build
```

This will create a `dist` directory with the compiled game. This directory can be served by any web
server.

## Themes

The game's theme (which controls the colors and some other aesthetic aspects) can be changed by
overriding or modifying the configuration. Check `extras/config/settings.yml` for the available
themes.

## Credits

- **Story:** Eric Londaits, Elisabeth Schaber, and Andreas Matt
- **Images:** Eric Londaits
- **Game engine:** Eric Londaits and Christian Stussak (see [Citizen Quest](https://github.com/IMAGINARY/citizen-quest)).

## License

Code licensed under the MIT License. See [LICENSE](LICENSE) for details.
Images licensed under the Creative Commons Attribution-ShareAlike 4.0 International License.
See [extras/static/README-citizen-quest-edsoc.md](extras/static/README-datalove-quest.md) for details.

Copyright 2024 Imaginary gGmbH.
