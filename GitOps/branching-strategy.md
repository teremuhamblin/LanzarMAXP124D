# Stratégie de branches — LanzarMAXP124D

## Vue d’ensemble

Le projet suit une stratégie de branches inspirée des environnements militaires :
- `main` — zone sécurisée.
- `dev` — zone d’exercice.
- branches de mission — opérations ciblées.

---

## Détails des branches

### main
- Contient uniquement du code validé.
- Taguée pour les versions stables.
- Déploiement possible à tout moment.

### dev
- Intégration des features.
- Peut être instable.
- Nettoyage régulier par rebase/squash.

### feature/<nom>
- Une fonctionnalité = une branche.
- Nom explicite :
  - `feature/dsp-preset-45hz`
  - `feature/wiring-4ohms`

### fix/<nom>
- Corrections ciblées :
  - `fix/volume-calculation`
  - `fix/phase-inversion`

### docs/<nom>
- Documentation uniquement :
  - `docs/box-specs`
  - `docs/wiring-diagrams`

### ops/<nom>
- GitOps, scripts, infra :
  - `ops/gitops-pack`
  - `ops/ci-setup`

---

## Cycle de vie d’une branche

1. Création depuis `dev` :
   - `git checkout dev`
   - `git checkout -b feature/<nom>`
2. Travail, commits propres.
3. Push vers remote.
4. PR vers `dev`.
5. Review, corrections.
6. Merge (squash).
7. Suppression de la branche.
