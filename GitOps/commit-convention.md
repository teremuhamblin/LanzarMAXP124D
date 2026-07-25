# Convention de commits — LanzarMAXP124D

## Format

<type>: <description courte>

Exemples :
- feat: ajout preset SPL 45Hz
- fix: correction calcul volume net
- docs: ajout schéma de câblage

---

## Types

- feat — nouvelle fonctionnalité.
- fix — correction de bug.
- docs — documentation.
- style — formatage, indentation.
- refactor — amélioration interne sans changement de comportement.
- perf — optimisation.
- test — ajout/modif de tests.
- chore — maintenance, dépendances.
- ops — scripts GitOps, CI, infra.

---

## Règles

- Description en français, claire, orientée action.
- Pas de commits fourre-tout :
  - éviter `feat: plein de trucs`.
- Commits atomiques :
  - une idée = un commit.
- Pas de fichiers temporaires, audio ou binaires non nécessaires.
