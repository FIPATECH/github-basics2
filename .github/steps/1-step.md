## Étape 1 : créer une branche

Bienvenue dans ta première manipulation GitHub.

Avant de modifier un projet partagé, on évite généralement de travailler directement sur la branche principale. On crée une **branche** dédiée à son travail.

### 📖 Qu'est-ce qu'une branche ?

Une branche est une version parallèle de l'historique du dépôt.

La branche principale de ce dépôt s'appelle `main`. Elle représente la version de référence du projet.

En créant une autre branche, tu peux modifier des fichiers, faire des commits et expérimenter sans modifier immédiatement `main`.

C'est une pratique fondamentale dans la plupart des projets logiciels, qu'il s'agisse d'une application web, d'un logiciel embarqué, d'un projet scientifique, d'un drone, d'un robot ou d'un outil interne.

### ⌨️ Exercice : créer `my-first-branch`

1. Garde cette Issue ouverte dans cet onglet.
2. Ouvre la page principale du dépôt dans un **second onglet**.
3. Dans l'onglet **Code**, ouvre le menu des branches, qui affiche actuellement `main`.
4. Dans le champ de recherche, saisis exactement :

   ```text
   my-first-branch
   ```

5. Clique sur **Create branch: my-first-branch from main**.

GitHub basculera automatiquement sur ta nouvelle branche.

> [!IMPORTANT]
> Le nom `my-first-branch` est vérifié automatiquement. Utilise exactement ce nom pour que le cours puisse détecter ta progression.

### 💻 Option terminal

Si tu utilises Git en ligne de commande :

```bash
git checkout -b my-first-branch
git push -u origin my-first-branch
```

La première commande crée la branche localement et s'y place. La seconde la publie sur GitHub.

### Pourquoi ne pas travailler directement sur `main` ?

Une branche permet notamment de :

- isoler une fonctionnalité ou une correction ;
- travailler sans perturber la version principale ;
- partager son travail avant de l'intégrer ;
- faire relire les changements ;
- abandonner une expérimentation sans casser le projet.

<details>
<summary>Un problème ?</summary>

Vérifie que :

- la branche s'appelle exactement `my-first-branch` ;
- elle a été créée à partir de `main` ;
- si tu travailles en local, tu l'as bien poussée sur GitHub avec `git push -u origin my-first-branch`.

</details>

Une fois la branche créée, le cours détectera automatiquement l'action et affichera l'étape suivante dans cette Issue.
