# Câblage – Impédance finale 4Ω

## Objectif

Obtenir une charge **4Ω finale** à partir de **2× subwoofers Lanzar MAXP124D (DVC 4Ω)**.

## Étape 1 – Câblage par subwoofer

Chaque sub possède deux bobines de 4Ω.

Montage **en série** des bobines :

- Plus bobine 1 → ampli (via jonction)
- Moins bobine 1 → plus bobine 2
- Moins bobine 2 → retour commun

Résultat : **8Ω par sub**

## Étape 2 – Assemblage des deux subs

Les deux subs 8Ω sont câblés **en parallèle** :

- Plus sub A + plus sub B → borne + de l’ampli
- Moins sub A + moins sub B → borne – de l’ampli

Résultat : **4Ω final**

## Schéma ASCII simplifié

Sub A (DVC 4Ω) – série :

[ +AMP ]──( +B1 4Ω – )──( +B2 4Ω – )──[ –A ]

Sub B (DVC 4Ω) – série :

[ +AMP ]──( +B1 4Ω – )──( +B2 4Ω – )──[ –B ]

Parallèle des deux subs :

- Tous les +A et +B ensemble → + ampli
- Tous les –A et –B ensemble → – ampli

## Recommandations

- Utiliser du câble de section adaptée (min 2,5 mm², idéalement 4 mm²).
- Vérifier la polarité de tous les branchements.
- Tester l’impédance à l’ohmmètre (valeur proche de 3–4Ω).
