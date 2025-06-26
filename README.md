# Projet Git [SiteWebStatic]

## Stratégie de Branchement

- **Branche `main`** : Contient la version stable et prête pour la production du projet.
- **Branche `dev`** : Utilisée pour le développement et l'intégration des nouvelles fonctionnalités avant de les fusionner dans `main`.
- **Branches `feature/*`** : Chaque fonctionnalité est développée dans sa propre branche, nommée `feature/nom_de_la_fonctionnalité`. Cela permet de travailler sur plusieurs fonctionnalités simultanément sans interférer avec le code principal.

## Étapes Suivies

1. **Création des branches `feature`** :
   - Chaque nouvelle fonctionnalité a été développée dans une branche distincte.
   
2. **Tests et Intégration** :
   - Après le développement, chaque branche `feature` a été fusionnée dans la branche `test/frontend` pour des tests de cohérence et de fonctionnalité.

3. **Fusion finale** :
   - Les changements validés ont été fusionnés dans `dev`, puis intégrés dans `main` après validation finale.

## Commandes Git Utilisées

- **Créer une branche** :
  git checkout

  **pour pouser vers le depot distant
  git push -u origin (nom de ka branche)
   
   **pour creer une branche
  git checkout -b feature/nom_de_la_fonctionnalité

    **pour enregistre un commit
   git commit -m "message du commit"

    **pour fusionner 
  git merge (nom de la branche)

   **pour ajouter 
   git add .
   
   **pour cloner
   git clone