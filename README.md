<header>

# GitHub Basics

<img src="https://octodex.github.com/images/original.png" align="right" height="160px" />

_Découvre GitHub en moins d'une heure, directement depuis l'interface web._

</header>

## Bienvenue

GitHub est une plateforme de collaboration pour les projets versionnés avec **Git**.

- **Git** enregistre l'historique des fichiers d'un projet.
- Un **dépôt** (ou _repository_) est le dossier de projet suivi par Git et hébergé sur GitHub.
- Une **Issue** est un fil de suivi utilisé pour discuter d'une tâche, d'un problème ou d'un objectif.
- Une **branche** est une version parallèle du projet sur laquelle tu peux travailler sans modifier immédiatement la version principale.
- Un **commit** est un enregistrement identifié d'un ensemble de modifications.
- Une **pull request** est une proposition pour intégrer les changements d'une branche dans une autre après les avoir relus.
- Un **merge** est l'intégration effective de ces changements.

Tu n'as pas besoin de mémoriser ces définitions maintenant. Le cours va reprendre chaque notion dans l'ordre, au moment où tu l'utiliseras.

## Ce que tu vas faire

Pendant l'exercice, tu vas :

1. créer une branche appelée `my-first-branch` ;
2. créer un fichier Markdown nommé `PROFILE.md` ;
3. prévisualiser son rendu puis enregistrer le changement dans un commit ;
4. ouvrir une pull request vers `main` ;
5. relire les changements et merger la pull request.

Le bot te guidera d'abord dans une Issue dédiée. Lorsque tu ouvriras ta pull request, la suite du cours apparaîtra directement dans sa conversation pour éviter de jongler entre plusieurs onglets.

> [!NOTE]
> Ce premier cours utilise volontairement l'interface web de GitHub. Le travail quotidien du club se fera ensuite surtout avec **Git en ligne de commande et VS Code**. Le tutoriel suivant est déjà disponible : [Git & VS Code](https://github.com/ENSTARobotics/tutorial-git-vscode).

## Pour qui ?

Ce cours s'adresse aux personnes qui découvrent GitHub, notamment aux étudiants et aux nouveaux contributeurs à un projet logiciel ou robotique.

- **Durée :** environ 30 à 60 minutes.
- **Prérequis :** aucun, à part un compte GitHub.

## Commencer le cours

Crée un nouveau dépôt à partir de ce **dépôt modèle** (_template_). Un dépôt modèle est un dépôt prévu pour servir de point de départ : GitHub en copie les fichiers et les automatisations dans ton nouveau dépôt. N'utilise pas **Fork** : un fork est une copie liée au dépôt d'origine, surtout utile pour proposer des contributions à un projet existant. Ici, on veut au contraire une copie indépendante créée depuis le modèle.

[![Commencer le cours](https://img.shields.io/badge/Commencer%20le%20cours-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=ENSTARobotics&template_name=tutorial-github-basics&owner=%40me&name=tutorial-github-basics&description=Tutoriel%20interactif%20%3A%20d%C3%A9couvrir%20les%20bases%20de%20GitHub&visibility=public)

Après la création du dépôt :

1. attends une vingtaine de secondes ;
2. actualise la page ;
3. ouvre l'Issue créée automatiquement par Mona.

<details>
<summary>Le cours ne démarre pas ?</summary>

Ouvre l'onglet **Actions** du dépôt. **GitHub Actions** est le système d'automatisation de GitHub utilisé par le bot du cours. Vérifie le **workflow** **Step 0**. Un workflow est une automatisation décrite pour GitHub Actions. Si son exécution a échoué, son journal indique généralement la cause.

</details>

---

Inspiré de [GitHub Skills - Introduction to GitHub](https://github.com/skills/introduction-to-github).
