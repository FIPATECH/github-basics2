<!-- github-basics:step-4 -->

## Étape 4 : relire puis merger ta pull request

Ta pull request est valide. La suite se déroule directement ici, dans sa **Conversation**.

Avant de merger, prends quelques minutes pour comprendre les principales vues d'une PR.

### Les principales vues d'une pull request

- **Conversation** : le fil de discussion et l'historique des événements de la PR. C'est ici que Mona te parle.
- **Commits** : les commits contenus dans ta branche et proposés par cette PR.
- **Checks** : les vérifications automatiques exécutées par GitHub Actions ou d'autres outils.
- **Files changed** : le **diff**, c'est-à-dire l'affichage précis des lignes ajoutées, supprimées ou modifiées.
- Selon la configuration du dépôt, un onglet **Findings** peut aussi apparaître pour regrouper certains résultats automatiques de revue ou d'analyse.

Une **review** est la relecture d'une pull request par une autre personne. Elle peut approuver le changement, poser une question ou demander une modification.

### Activité : relire ton changement

1. Ouvre **Files changed**.
2. Vérifie que `PROFILE.md` contient uniquement ce que tu voulais ajouter.
3. Quand tu as fini de relire ce fichier, marque-le **Viewed**. GitHub peut ainsi suivre ce que tu as déjà vérifié.
4. Ouvre **Checks** et vérifie que les automatisations ont terminé.
5. Reviens dans **Conversation**.

Sur un vrai projet, tu peux aussi commenter directement une ligne du diff pendant une review.

Cette relecture est importante : un merge intègre ce qui est affiché dans la PR, pas ce que tu pensais avoir modifié.

### Qu'est-ce qu'un merge ?

Un **merge** intègre les changements de ta branche dans la branche de destination, ici `main`.

Après le merge, `PROFILE.md` fera partie de la version principale du dépôt.

![Bouton Merge pull request](../images/merge-pull-request-button.png)

### Activité : merger la pull request

1. Clique sur **Merge pull request**.
2. Clique sur **Confirm merge**.
3. Une fois le merge terminé, clique sur **Delete branch** si GitHub te le propose.

   ![Bouton Delete branch](../images/delete-branch-button.png)

> [!NOTE]
> Si le bouton de merge est temporairement désactivé, attends la fin des checks puis actualise la page.

Après le merge, reste encore dans cette conversation : Mona y publiera le bilan du cours.
