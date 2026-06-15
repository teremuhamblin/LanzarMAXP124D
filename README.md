###### README.md >> markdown

---

# 🔥 LanzarMAXP124D
- Compétition

Le projet LanzarMAXP124D-Comp vise à concevoir, documenter et optimiser un système de basses haute‑puissance basé sur deux subwoofers Lanzar MAXP124D, des modèles réputés dans le milieu SPL pour leur robustesse, leur rendement et leur capacité à encaisser de fortes charges électriques.

---

🎯 Objectif du projet

Créer un caisson SPL performant, capable d’exploiter 2× Lanzar MAXP124D dans une configuration 4Ω finale, avec une puissance totale exploitable de 1200 à 1600W RMS, tout en garantissant :

- une pression acoustique élevée,  
- une réponse propre et maîtrisée,  
- une fiabilité mécanique et électrique,  
- une documentation complète pour la construction, le câblage et le tuning.

---

🔊 Description des subwoofers Lanzar MAXP124D

Les Lanzar MAXP124D sont des subwoofers 12" double bobine 4Ω, conçus pour les applications SPL et compétition.

Caractéristiques principales :

- Diamètre : 12 pouces  
- Type : DVC (Dual Voice Coil)  
- Impédance par bobine : 4Ω  
- Puissance admissible : ~600–800W RMS (1600W max)  
- Usage : SPL, caissons haute pression, forte excursion  
- Avantages :
  - Flexibilité de câblage (1Ω, 4Ω, 8Ω selon montage)  
  - Construction robuste (spider renforcé, aimant massif)  
  - Bon rapport qualité/prix pour la compétition amateur et semi-pro  

---

⚡ Configuration électrique retenue

Pour obtenir une charge 4Ω finale, idéale pour la majorité des amplis puissants :

- Étape 1 – Par subwoofer :  
  - Bobine 1 (4Ω) + Bobine 2 (4Ω) en série → 8Ω par sub

- Étape 2 – Assemblage des deux subs :  
  - Sub A 8Ω en parallèle avec Sub B 8Ω → 4Ω final

Résultat :  
➡️ Impédance finale : 4Ω  
➡️ Puissance totale exploitable : 1200–1600W RMS

---

📦 Conception du caisson

Le projet inclut la création d’un caisson optimisé pour tirer le meilleur des MAXP124D :

- Type : Bass‑reflex SPL  
- Volume interne visé : 110–130 L brut  
- Accord : 32–38 Hz (selon usage : musique / SPL / daily)  
- Matériau : CP bouleau 18 ou 21 mm  
- Renforts :  
  - Renfort central  
  - Renforts latéraux  
  - Double baffle avant possible  
- Évents :  
  - Slot port ou évents circulaires haute section  

---

🗂️ Contenu du projet

Le dépôt LanzarMAXP124D-Comp regroupe :

- docs/
  - Spécifications techniques des MAXP124D  
  - Schémas de câblage  
  - Plans du caisson  
  - Matching ampli (puissance, stabilité, rendement)

- src/
  - Simulations WinISD  
  - Presets DSP (EQ, filtres, subsonic)

- build/
  - Cut‑list  
  - Guide d’assemblage  
  - Plan de renforts  

- README.md
  - Présentation du projet  
  - Objectifs  
  - Instructions de montage  
  - Notes SPL / tuning  

---

🧭 Finalité

Ce projet fournit une base complète pour construire un système SPL puissant, fiable et documenté, utilisant deux subwoofers Lanzar MAXP124D dans une configuration optimisée pour la performance et la durabilité.

---
