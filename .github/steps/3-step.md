## Étape 3 : ouvrir une pull request

Tu as maintenant une branche contenant un changement qui n'existe pas encore dans `main`.

Il faut proposer son intégration au projet.

### 📖 Qu'est-ce qu'une pull request ?

Une **pull request**, souvent abrégée **PR**, est une proposition de changement.

Elle compare deux branches et fournit un espace de collaboration autour des différences entre elles.

Une pull request permet notamment de :

- visualiser précisément les fichiers modifiés ;
- discuter des changements ;
- demander une review ;
- exécuter des vérifications automatiques ;
- corriger le travail avant son intégration ;
- conserver une trace de la discussion et de la décision.

Créer une PR ne modifie pas encore `main`. Elle demande simplement : « voici mon travail, est-ce qu'on l'intègre ? »

### ⌨️ Exercice : créer ta première pull request

1. Sur GitHub, tu devrais voir un bouton **Compare & pull request** après ton récent commit. Clique dessus.

   Si le bouton n'apparaît pas, ouvre **Pull requests**, puis **New pull request**.

2. Vérifie attentivement les branches :

   - **base** : `main`
   - **compare** : `my-first-branch`

3. Choisis un titre clair, par exemple :

   ```text
   docs: add my introduction
   ```

4. Ajoute une **courte description** expliquant ce que tu as fait et pourquoi.

   Par exemple :

   ```markdown
   ## Description

   J'ai ajouté une courte présentation dans playground/README.md
   afin de pratiquer mon premier workflow GitHub.
   ```

5. Clique sur **Create pull request**.

> [!IMPORTANT]
> Une description non vide est demandée par l'exercice. Dans un vrai projet, elle aide les reviewers à comprendre le contexte sans devoir deviner l'intention à partir du diff.

### 🔍 Prends le temps d'explorer ta PR

Avant de continuer, regarde les différents onglets :

- **Conversation** : discussion générale et événements de la PR ;
- **Commits** : commits contenus dans la branche ;
- **Checks** : vérifications automatisées éventuelles ;
- **Files changed** : différence exacte entre `my-first-branch` et `main`.

Le dernier onglet est particulièrement important lors d'une review : il permet de vérifier exactement ce qui sera intégré.

<details>
<summary>Un problème ?</summary>

Si ta branche n'apparaît pas :

- vérifie qu'elle a bien été poussée sur GitHub ;
- vérifie qu'elle contient au moins un commit différent de `main`.

Si GitHub indique qu'il n'y a aucune différence à comparer, assure-toi de sélectionner `main` comme base et `my-first-branch` comme branche de comparaison.

</details>

Une fois la pull request correctement créée, le cours vérifiera sa description et affichera la dernière étape.
