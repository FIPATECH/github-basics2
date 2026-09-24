## Bilan du cours

🎉 Félicitations, tu viens de terminer **GitHub Basics** !

<img src="https://octodex.github.com/images/collabocats.jpg" alt="Octocats collaborant" width="300" align="right" />

Tu viens d'effectuer un workflow de contribution complet sur GitHub.

### Ce que tu as pratiqué

Tu as :

- créé une branche à partir de `main` ;
- modifié un fichier sans toucher directement à la branche principale ;
- créé un commit avec ton changement ;
- poussé ton travail sur GitHub ;
- ouvert une pull request ;
- décrit l'objectif de ton changement ;
- examiné le diff entre deux branches ;
- mergé ta contribution dans `main`.

### Le workflow à retenir

```text
main
  │
  ├── créer une branche
  │
  ▼
branche de travail
  │
  ├── modifier des fichiers
  ├── commit
  ├── push
  │
  ▼
pull request
  │
  ├── review
  ├── checks
  ├── corrections éventuelles
  │
  ▼
merge
  │
  ▼
main mis à jour
```

Ce modèle, avec des variantes, est utilisé dans énormément de projets logiciels.

### Quelques bonnes habitudes

- Évite de développer directement sur `main`.
- Fais des commits cohérents et compréhensibles.
- Donne à tes branches et à tes PR des noms explicites.
- Relis toujours le diff avant de merger.
- Explique le **pourquoi** d'un changement, pas uniquement le **quoi**.
- Demande une review lorsqu'un changement mérite un second regard.
- Synchronise régulièrement ton dépôt local avec le dépôt distant.

### Git et GitHub ne sont pas la même chose

À retenir :

- **Git** est le système de gestion de versions distribué ;
- **GitHub** est une plateforme qui héberge des dépôts Git et ajoute des outils de collaboration : pull requests, Issues, Actions, reviews, permissions, etc.

Tu peux utiliser Git sans GitHub, et GitHub s'appuie sur Git pour le versionnement.

### Pour aller plus loin

Tu peux maintenant explorer :

- les commandes Git en ligne de commande ;
- les reviews et suggestions de code ;
- les Issues ;
- GitHub Actions et la CI/CD ;
- les tags et releases ;
- les stratégies de branches ;
- les conflits et le rebase ;
- les fichiers `.gitignore`.

Documentation officielle : <https://docs.github.com/>

L'objectif n'est pas de mémoriser toutes les commandes immédiatement. Le plus important est de comprendre le cycle **branche → commit → pull request → review → merge** et de le pratiquer régulièrement.
