## Étape 4 : relire et merger la pull request

Ta pull request relie maintenant ton travail à la branche principale.

Avant de merger, prends quelques instants pour relire ce que tu vas intégrer.

### 📖 Qu'est-ce qu'un merge ?

Un **merge** intègre dans une branche les changements provenant d'une autre branche.

Ici, le but est d'intégrer le contenu de `my-first-branch` dans `main`.

Après le merge, ton changement fera donc partie de la version principale du dépôt.

### 🔍 Avant de merger

Dans ta pull request :

1. ouvre **Files changed** ;
2. vérifie que seules les modifications attendues apparaissent ;
3. reviens dans **Conversation** ;
4. vérifie que les checks éventuels sont terminés.

Cette relecture finale évite d'intégrer accidentellement des fichiers ou des changements qui n'étaient pas prévus.

### ⌨️ Exercice : merger la pull request

Si GitHub indique que la branche peut être mergée :

1. clique sur **Merge pull request** ;
2. clique sur **Confirm merge** ;
3. une fois le merge effectué, GitHub peut te proposer **Delete branch**.

Tu peux supprimer `my-first-branch` après le merge. Son travail est désormais intégré dans `main` et son historique reste accessible.

### ⚠️ Et s'il y a un conflit ?

Un **conflit de merge** apparaît lorsque Git ne peut pas déterminer automatiquement quelle version d'une même partie d'un fichier doit être conservée.

Dans cet exercice simple, tu ne devrais normalement pas rencontrer de conflit. Mais dans un projet réel, cela arrive souvent lorsque plusieurs personnes modifient la même zone d'un fichier.

GitHub peut parfois proposer **Resolve conflicts** directement dans l'interface.

En ligne de commande, une résolution typique ressemble à :

```bash
git checkout my-first-branch
git fetch origin
git merge origin/main

# corriger les fichiers en conflit

git add .
git commit
git push
```

Les marqueurs de conflit ressemblent à ceci :

```text
<<<<<<< HEAD
ta version
=======
l'autre version
>>>>>>> main
```

Il faut choisir ou recomposer la bonne version, puis supprimer ces marqueurs avant de créer le commit de résolution.

### 🧠 Merge, squash, rebase

GitHub peut proposer plusieurs stratégies selon la configuration du dépôt :

- **Merge commit** : conserve les commits de la branche et ajoute un commit de merge ;
- **Squash and merge** : regroupe les commits de la PR en un seul commit ;
- **Rebase and merge** : rejoue les commits sur la branche cible pour obtenir un historique linéaire.

Il n'existe pas une méthode universellement meilleure. Les équipes choisissent généralement une convention cohérente pour leurs projets.

<details>
<summary>Un problème ?</summary>

Si le bouton de merge est désactivé :

- attends la fin des checks ;
- vérifie qu'aucun conflit n'est signalé ;
- vérifie que les étapes précédentes ont bien été validées.

</details>

Merge maintenant ta pull request. Le cours détectera l'événement et affichera automatiquement le bilan final.
