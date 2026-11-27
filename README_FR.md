# mod-event-stranglethorn

[English](README.md) | [Français](README_FR.md)

Modifications de Murloc Village sur les événements de Strangleronce. Données uniquement (SQL), pas de scripts C++.

## Ce que fait le module

- **Arène de Gurubashi (course au trésor) :** pendant l'événement, un portail à Hurlevent et un à Orgrimmar emmènent les joueurs à l'arène.
- **Concours de pêche de Strangleronce :** pendant le concours, un portail à Hurlevent et un à Orgrimmar emmènent les joueurs à Baie-du-Butin.

En cours de développement, suivi dans l'issue #40 de Murloc Village.

## Installation

Placez le module dans `modules/mod-event-stranglethorn` et relancez CMake. AzerothCore applique `data/sql/` au démarrage du worldserver.

`src/` ne contient qu'un chargeur vide : AzerothCore n'applique le SQL d'un module que si celui-ci en a un.

## Crédits

* [Miorey](https://github.com/Miorey/)

Notre serveur : [Murloc Village](https://wotlk.murlocvillage.com/fr/). Merci à [AzerothCore](https://www.azerothcore.org/).
