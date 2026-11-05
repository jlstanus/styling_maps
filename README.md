# Styling maps

Organisation de styles cartographiques réutilisables, en privilégiant les formats ouverts.

## Contenu

- [`symbol_svg/`](./symbol_svg/README.md) — bibliothèque SVG commune, dont des modèles paramétrables pour QGIS.
- [`palettes/`](./palettes/README.md) — palettes de couleurs, notamment au format XML de QGIS.
- [`styles/`](./styles/README.md) — styles par moteur : SLD, QML, MapCSS et Mapbox/MapLibre.

Les SVG de `symbol_svg/` sont les sources à conserver. Les styles peuvent les référencer lorsqu'ils le permettent ; les formats qui nécessitent des sprites ou des images dérivées doivent les placer dans leur propre dossier `assets/`.

Privilégier des noms stables en minuscules avec des tirets, conserver les sources éditables et documenter la licence des ressources importées.
