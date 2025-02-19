IPAGastronomie
==============

Ce repo git a pour but de mettre en commun des recettes pour les doctorants de l'IPAG. La solution adoptée dans un premier lieu est de tout faire sur LaTeX, si vous avez d'autres propositions gratuites qui ne nécessite pas d'installation lourdes vous pouvez les suggérer. Vous pouvez aussi suggérer des améliorations sur la mise en forme et le template. Le but est que chacun puisse ajouter ses propres recettes pour au final donner un pdf complet et agréable à lire pour que chacun puisse cuisiner ce qu'il veut !

Prérequis
---------

- Obsidian

Structure
---------

Le projet est organisé d'une façon qui permettra de d'ajouter/supprimer/modifier simplement une seule recette sans avoir un main.tex à rallonge. La structure des dossiers est faite pour pouvoir organiser les différents types de recettes (sucrées, salées, végé, végans, etc) au mieux et pour limiter la confusion lorsqu'il y en aura beaucoup. S'il vous plait, suivez cette structure de dossier afin d'éviter les conflits lors de la compilation du main.tex :

- `Salé/`:
  - `Salé/Végé/`: Contient tous les fichiers (au format .md) des recettes salées et végétariennes
  - `Salé/Végan/`: Contient tous les fichiers (au format .md) des recettes salées et végans
  - `Salé/Autre/`: Contient tous les fichiers (au format .md) des recettes salées et non végétariennes ou végans
- `Sucré/`:
  - `Sucré/Végé/`: Contient tous les fichiers (au format .md) des recettes sucrées et végétariennes
  - `Salé/Végan/`: Contient tous les fichiers (au format .md) des recettes sucrées et végans
  - `Salé/Autre/`: Contient tous les fichiers (au format .md) des recettes sucrées et non végétariennes ou végans
  
Contribution :
--------------

Pour connaître en détail les bonnes pratiques sur comment contribuer à un projet git (clonage du repo, branches, commit, etc), voir le fichier `contributing.md`. 

Pour ce qui concerne ce projet en particulier, les détails sont assez simples. Un fichier `template_recette.md` est fournit dans le repo. Pour ajouter une recette il suffit de créer un fichier .tex suivant ce template dans le bon dossier (par exemple un risotto végé sera dans `Salé/Végé/Risotto champignon carottes.md`). Vous n'avez alors plus qu'à ajouter toutes les informations sur le template afin de créer votre recette ! Si vous avez des suggestions de modifications du template, n'hésitez pas.
