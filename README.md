# mod-event-stranglethorn

[English](README.md) | [Français](README_FR.md)

Murloc Village changes to the Stranglethorn Vale events. Data only (SQL), no C++ scripts.

## What it does

- **Gurubashi Arena (Booty Run):** while the event runs, a portal in Stormwind and one in Orgrimmar take players to the arena.
- **Stranglethorn Fishing Extravaganza:** while the contest runs, a portal in Stormwind and one in Orgrimmar take players to Booty Bay.

Work in progress, tracked in Murloc Village issue #40.

## Install

Put the module in `modules/mod-event-stranglethorn` and re-run CMake. AzerothCore applies `data/sql/` when the worldserver starts.

`src/` only holds an empty loader: AzerothCore applies a module's SQL only if the module has one.

## Credits

* [Miorey](https://github.com/Miorey/)

Our server: [Murloc Village](https://wotlk.murlocvillage.com/fr/). Thanks to [AzerothCore](https://www.azerothcore.org/).
