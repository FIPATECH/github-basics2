<!-- github-basics:review -->

## Bilan : tu as terminé GitHub Basics

🎉 Ta première contribution GitHub est mergée.

<img src="https://octodex.github.com/images/collabocats.jpg" alt="Octocats collaborant" width="300" align="right" />

### Le cycle que tu viens de pratiquer

1. **Dépôt** : le projet et son historique.
2. **Issue** : un fil de suivi pour une tâche, un problème ou un objectif.
3. **Branche** : une version parallèle utilisée pour préparer un changement.
4. **Fichier Markdown** : un fichier texte structuré, ici `PROFILE.md`.
5. **Commit** : un enregistrement identifié de modifications dans l'historique.
6. **Pull request** : une proposition pour intégrer une branche dans une autre.
7. **Diff** : la vue exacte des lignes modifiées par cette proposition.
8. **Check** : une vérification automatique.
9. **Review** : une relecture humaine du changement.
10. **Merge** : l'intégration du changement dans `main`.

### Git et GitHub

**Git** est le système de gestion de versions qui enregistre les commits et les branches.

**GitHub** héberge les dépôts Git et ajoute les outils de collaboration que tu viens d'utiliser : pull requests, reviews, Issues et GitHub Actions.

### Quelques habitudes à garder

- crée une branche pour isoler ton travail ;
- relis ce que tu vas committer ;
- écris ou vérifie un message de commit compréhensible ;
- explique le but d'une pull request ;
- lis toujours le diff avant de merger ;
- regarde les checks avant d'intégrer un changement ;
- demande une review lorsqu'un second regard est utile.

### La suite logique pour le club

Dans ce cours, tu as volontairement utilisé l'interface web pour voir chaque notion séparément.

Passe maintenant au tutoriel **[Git & VS Code](https://github.com/ENSTARobotics/tutorial-git-vscode)**. Tu y reprendras le même cycle depuis une copie locale du dépôt :

```text
clone → branche → modification dans VS Code → git status → git add → commit → push → pull request
```

Tu y apprendras à copier un dépôt sur ton ordinateur, comprendre ce que Git suit localement, préparer puis enregistrer un changement, l'envoyer sur GitHub et resynchroniser ton projet après un merge. Les termes techniques seront introduits au moment où ils deviennent utiles.

Les **conflits de merge** viendront ensuite dans un tutoriel dédié, une fois ce workflow normal maîtrisé.

Documentation officielle : <https://docs.github.com/>

Le plus important à retenir pour l'instant :

```text
branche → modification → commit → pull request → review/checks → merge
```
