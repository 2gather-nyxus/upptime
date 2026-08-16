---
name: Maintenance Event
about: Déclarer une fenêtre de maintenance planifiée
title: "[Maintenance planifiée] "
labels: maintenance
assignees: ""
---

<!--
start: 2026-08-20T02:00:00.000Z
end: 2026-08-20T03:00:00.000Z
expectedDown: api, api-acces-base-de-donnees
-->

Renseigner `start`, `end` et `expectedDown` dans le commentaire ci-dessus. Les dates sont en UTC,
au format ISO 8601. `expectedDown` prend les identifiants des services, c'est-à-dire le nom de leur
fichier dans `history/` sans l'extension. La période déclarée est exclue du calcul de disponibilité.

**Objet de la maintenance**
Ce qui est fait, sur quels services, et l'effet attendu pour les utilisateurs.
