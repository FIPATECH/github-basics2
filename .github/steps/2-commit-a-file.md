## Étape 2 : créer un fichier et ton premier commit

Ta branche existe maintenant. Tu peux y modifier le projet sans changer `main`.

### Qu'est-ce qu'un fichier Markdown ?

Tu vas créer `PROFILE.md`. L'extension `.md` indique un fichier **Markdown**, un format texte simple utilisé partout sur GitHub pour écrire des README, de la documentation et des commentaires structurés.

GitHub sait afficher le texte Markdown sous une forme mise en page. Avant d'enregistrer ton fichier, tu vas donc comparer le texte que tu écris avec son rendu.

### Qu'est-ce qu'un commit ?

Un **commit** est un point enregistré dans l'historique Git.

Il contient notamment :

- les modifications enregistrées ;
- leur auteur ;
- leur date ;
- un **message de commit** qui résume ce qui a changé.

À la base, ce message se rédige à la main : il doit être court, clair et décrire l'intention du changement.

> [!NOTE]
> Sur GitHub.com, si GitHub Copilot est disponible sur ton compte, GitHub peut aujourd'hui proposer automatiquement un résumé et une description lorsque tu cliques sur **Commit changes...**. Relis toujours cette proposition et modifie-la si nécessaire avant de valider. Si aucune suggestion n'apparaît, écris simplement le message toi-même. La génération automatique peut notamment te proposer un message en anglais.

### Activité : créer `PROFILE.md`

1. Dans l'onglet **Code**, vérifie que la branche affichée est bien `my-first-branch`.
2. Clique sur **Add file**, puis **Create new file**.

   <img width="300" alt="Créer un nouveau fichier dans GitHub" src="../images/create-new-file-option.png">

3. Dans **Name your file...**, saisis :

   ```text
   PROFILE.md
   ```

4. Dans le fichier, écris au minimum :

   ```markdown
   # Mon profil

   Hello GitHub !

   Je découvre les branches, les commits et la collaboration sur GitHub.
   ```

   ![Éditeur GitHub contenant PROFILE.md](../images/add-profile-file.png)

5. Clique sur **Preview** au-dessus de l'éditeur et observe comment GitHub rend le Markdown.
6. Reviens dans l'éditeur si tu veux corriger quelque chose, puis clique sur **Commit changes...**.
7. Vérifie le message de commit :
   - soit tu écris toi-même un message clair, par exemple `Ajouter PROFILE.md` ;
   - soit GitHub Copilot t'en propose un : lis-le et adapte-le si nécessaire.
8. Confirme avec **Commit changes**.

> [!IMPORTANT]
> Le cours vérifiera que `PROFILE.md` existe et qu'il contient le mot `Hello`. Le texte exact de ton message de commit n'est pas imposé : l'objectif est qu'il décrive clairement le changement.

Dès que GitHub reçoit ce commit sur `my-first-branch`, Mona vérifie ton travail puis affiche l'étape suivante.
