# MapQuilt — user manual

MapQuilt is a QGIS plugin for automatic raster assembly, georeferencing and vectorisation of scanned cadastral maps (developed on the ICPROM Iași 1:1000 plans, 1988–1990).

**Read the manual:** https://raduandrei-source.github.io/MapQuilt/ (English; Romanian from the language switch).

This repository holds only the manual, a single web page generated from the Markdown sections of the project (sections, literature, changelog). The plugin itself is distributed separately. The manual of [Rhino Sync](https://raduandrei-source.github.io/RhinoSync/) is in its own repository.

## Shared external sources

`sources.json` is the list the plugin downloads with **Shared** (⚙ Settings › External sources): building footprints and street centrelines other users found useful, for example a municipal WFS or a cadastral service. To add one, export it from the plugin (**Export…**) and open an issue in this repository with the `.json` file, its licence and the area it covers. A source is listed only when its terms allow reuse.

Created by Radu Andrei, "Gheorghe Asachi" Technical University of Iași, Faculty of Architecture "G. M. Cantacuzino", with the help of Claude (Anthropic).

The text of the manual is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see LICENSE).
