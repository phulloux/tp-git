Ouvrir un terminal (terminal Git Bash à privilégier)

Créer, en ligne de commande, un répertoire tp-git
- git init tp-git

Se déplacer dans le répertoire
- cd tp-git

Vérifier qu’on est dans le bon répertoire en affichant le chemin du répertoire courant
- pwd

Initialiser un dépôt Git


Lister tous les fichiers du répertoire (y compris les fichiers cachés) pour s’assurer que le répertoire .git à été créé
- ls -a

Ouvrir ce répertoire sous VS Code


Exécuter git status et copier/coller la sortie
- On branch master

- No commits yet

- nothing to commit (create/copy files and use "git add" to track)

Créer le fichier fichier1.md avec un contenu quelconque et l’enregistrer (vous pouvez utiliser VS Code pour créer et éditer des fichiers)
- touch fichier.md, et ajout d'un contenu via VS Code

Attention, il s’agit bien de créer un nouveau fichier, et non un répertoire. Il en sera de même tout au long de ce TP.
Créer le fichier fichier2.md avec un contenu quelconque et l’enregistrer
- touch fichier2.md, et ajout d'un contenu via VS Code

Exécuter git status et copier/coller la sortie
- On branch master

- No commits yet

- Untracked files:
-   (use "git add <file>..." to include in what will be committed)
-         fichier.md
-         fichier2.md

- nothing added to commit but untracked files present (use "git add" to track)

Ajouter fichier1.md à l’index de Git (zone de Staging)
git add fichier.md

Exécuter git status et copier/coller la sortie
- On branch master

- No commits yet

- Changes to be committed:
-   (use "git rm --cached <file>..." to unstage)
-         new file:   fichier.md

- Untracked files:
-   (use "git add <file>..." to include in what will be committed)
-         fichier2.md


Créer un commit avec pour message : “Ajout de fichier1.md”
git commit -m "Ajout de fichier.md"

VALIDATION PROF01
- ok

Exécuter git status et copier/coller la sortie
- On branch master
- Untracked files:
-   (use "git add <file>..." to include in what will be committed)
-         fichier2.md

- nothing added to commit but untracked files present (use "git add" to track)

Modifier fichier1.md et enregistrer


Exécuter git status et copier/coller la sortie
- On branch master
- Changes not staged for commit:
-   (use "git add <file>..." to update what will be committed)
-   (use "git restore <file>..." to discard changes in working directory)
-         modified:   fichier.md

- Untracked files:
-   (use "git add <file>..." to include in what will be committed)
-         fichier2.md

- no changes added to commit (use "git add" and/or "git commit -a")

Ajouter fichier1.md et fichier2.md à la zone de Staging
git add fichier.md fichier2.md

Créer un commit “Ajout de fichier2.md et modification de fichier1.md”
git commit -m "Ajout de fichier2.md et modification de fichier.md."

Exécuter git status et copier/coller la sortie
- On branch master
- nothing to commit, working tree clean


Copier/coller l’ID des deux premiers commits (utiliser log) :

ID commit 1 : ea339bf8c6593e07a697abacb5bba96b6c6f107a
ID commit 2 : d602041ce1c3bc549597885dbccf692e7dfff80c

Que signifie qu’un fichier est “tracked” ou “untracked“ ?
- cela signifie qu'il a été ajouté ou pas dans le git.

Pourquoi doit-on passer les fichiers par la zone de Staging (l’index) avant de les committer ?
- le git va pouvoir les prendre en charge pour les commit apres.

salut les copains, je modifie juste le fichier
