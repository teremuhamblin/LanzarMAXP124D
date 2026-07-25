# Vue d’ensemble CI — LanzarMAXP124D

## Objectif

Définir les grandes lignes de l’intégration continue pour le projet.

---

## Triggers recommandés

- `push` sur `dev` et `main`.
- `pull_request` vers `dev`.

---

## Jobs typiques

- Lint (si code présent).
- Tests (unitaires / fonctionnels).
- Vérification GitOps :
  - absence de fichiers binaires non autorisés.
  - respect de la structure du repo.
- Génération de documentation (optionnel).

---

## Politique de statut

- PR ne peut pas être mergée si CI en échec.
- CI doit être rapide (< 5 minutes si possible).
