# Exercice : provoquer un conflit Git

Objectif : modifier la **même ligne** dans deux branches.

## Étapes suggérées

1. Créer une branche `branche-a`
2. Dans `src/app.py`, remplacer le message de salutation par :
   `Bonjour depuis la branche A !`
3. Faire un commit.
4. Revenir sur `main`.
5. Créer une branche `branche-b`.
6. Modifier exactement la même ligne avec :
   `Bonjour depuis la branche B !`
7. Faire un commit.
8. Fusionner les deux branches.

Git devrait alors demander de résoudre un conflit.
