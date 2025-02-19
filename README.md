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
  

Comment contribuer
==================

Les contributions à ce dépôt sont les bienvenues. Veuillez suivre ces directives si vous souhaitez y contribuer.

Prise en main
-------------

1. Assurez-vous d’avoir un compte GitHub.
2. [Forkez](https://docs.github.com/fr/get-started/exploring-projects-on-github/contributing-to-a-project#about-forking) ce dépôt.

Faire des modifications
-----------------------

1. [Créez une branche](https://docs.github.com/fr/get-started/exploring-projects-on-github/contributing-to-a-project#creating-a-branch-to-work-on) de sujet pour vos commits.
2. Faites des commits de manière logique.
3. Assurez-vous que vos messages de commit suivent le format approprié :
  > - Un résumé court (50 caractères ou moins) des modifications. Pour le projet IPAGastronomie, préférez le format `Ajout/Modification/Suppression <nom de la recette>`. Faites un commit par recette ajoutée/modifiée/supprimée (modification du `main.tex` comprise).
  > - Un texte explicatif plus détaillé, si nécessaire. Formatez-le pour qu’il ait environ 72 caractères par ligne. Dans certains contextes, la première ligne est traitée comme l'objet d'un e-mail et le reste du texte comme le corps. La ligne vide séparant le résumé du corps est essentielle (à moins que vous n'omitiez complètement le corps). Les outils comme rebase peuvent être perturbés si les deux sont mélangés. Si le commit corrige un bug, la description doit inclure le numéro du bug, par exemple : "fixe le bug #3".

Soumettre les modifications
---------------------------

1. [Rebasez](https://docs.github.com/fr/get-started/using-git/about-git-rebase) votre travail sur la branche master du repo pour faciliter l'intégration et m'aider à maintenir un historique git propre.
2. [Poussez](https://docs.github.com/fr/get-started/using-git/pushing-commits-to-a-remote-repository) vos modifications vers la branche de sujet dans votre fork du dépôt.
3. [Soumettez une pull request](https://docs.github.com/fr/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) vers le dépôt.
4. Attendez que vos modifications soient examinées.

