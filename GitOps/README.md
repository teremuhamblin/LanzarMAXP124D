# GitOps — Projet LanzarMAXP124D

Ce document définit la doctrine GitOps du projet LanzarMAXP124D.

## Objectifs
- Historique Git propre, lisible, exploitable.
- Processus de développement reproductible.
- Intégration continue fiable.
- Discipline de branches et de merges.

---

## Branches

### Branches principales
- `main` — stable, toujours déployable.
- `dev` — intégration des features avant passage en `main`.

### Branches de travail
- `feature/<nom>` — nouvelles fonctionnalités.
- `fix/<nom>` — corrections de bugs.
- `docs/<nom>` — documentation uniquement.
- `ops/<nom>` — scripts, infra, GitOps.

---

## Règles de commit

Format :

<type>: <description courte>

Types autorisés :
- feat
- fix
- docs
- style
- refactor
- perf
- test
- chore
- ops

Exemples :
- feat: ajout preset SPL 45Hz
- fix: correction calcul volume net
- ops: ajout script de vérification GitOps

---

## Pull Requests

- Toujours ouvrir une PR vers `dev`.
- Description obligatoire :
  - Contexte
  - Changements
  - Tests effectués
- Pas de PR > 500 lignes sans justification.
- Review obligatoire avant merge.

---

## Politique de merge

- `Squash and merge` recommandé.
- Rebase sur `dev` avant merge si conflit.
- Pas de merge direct sur `main`.

---

## CI / Vérifications

Avant merge :
- Tests unitaires (si présents).
- Lint (si configuré).
- Vérification que aucun fichier binaire inutile n’est ajouté.
