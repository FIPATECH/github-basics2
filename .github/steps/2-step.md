## Étape 2 : modifier un fichier et créer un commit

Ta branche est prête. Tu vas maintenant effectuer une petite modification et l'enregistrer dans l'historique du projet.

### 📖 Qu'est-ce qu'un commit ?

Un **commit** est un enregistrement d'un ensemble de modifications.

On peut le voir comme un point de sauvegarde identifié dans l'historique Git. Chaque commit contient notamment :

- les changements apportés aux fichiers ;
- un auteur ;
- une date ;
- un message décrivant le changement ;
- un lien vers le commit précédent.

Un bon historique permet de comprendre pourquoi un projet a évolué, de retrouver l'origine d'un changement et, si nécessaire, de revenir à une version antérieure.

### ✍️ Les messages de commit

Évite les messages vagues comme :

```text
update
changes
test
```

Préfère un message court qui décrit clairement l'intention :

```text
docs: add my introduction
fix: correct configuration path
feat: add export button
```

Dans un vrai projet, cette discipline rend l'historique beaucoup plus utile pour toute l'équipe.

### ⌨️ Exercice : modifier `playground/README.md`

Sur la branche **`my-first-branch`** :

1. Ouvre `playground/README.md`.
2. Clique sur l'icône d'édition.
3. Ajoute **2 ou 3 lignes** pour te présenter ou expliquer ce que tu souhaites apprendre.
4. Fais apparaître le mot **`Hello`** quelque part dans ton texte.
5. Clique sur **Commit changes...**.
6. Saisis un message clair, par exemple :

   ```text
   docs: add my introduction
   ```

7. Confirme le commit sur **`my-first-branch`**.

> [!IMPORTANT]
> Le cours vérifiera automatiquement que `playground/README.md` existe et contient le mot `Hello`.

### 💻 Option terminal

```bash
git checkout my-first-branch

printf "\nHello, je découvre GitHub !\n" >> playground/README.md

git status
git add playground/README.md
git commit -m "docs: add my introduction"
git push
```

Quelques commandes importantes apparaissent ici :

- `git status` affiche l'état de ton espace de travail ;
- `git add` prépare les modifications qui feront partie du prochain commit ;
- `git commit` crée le commit ;
- `git push` envoie tes nouveaux commits vers GitHub.

<details>
<summary>Un problème ?</summary>

Vérifie que :

- tu modifies le fichier sur `my-first-branch`, pas sur `main` ;
- le fichier est bien `playground/README.md` ;
- le mot `Hello` apparaît exactement dans le fichier ;
- ton commit a bien été poussé sur GitHub si tu travailles en local.

</details>

Dès que le commit correct est détecté, le cours vérifiera ton travail et affichera l'étape suivante.
