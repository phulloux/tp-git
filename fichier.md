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


Attention, il s’agit bien de créer un nouveau fichier, et non un répertoire. Il en sera de même tout au long de ce TP.
Créer le fichier fichier2.md avec un contenu quelconque et l’enregistrer

Exécuter git status et copier/coller la sortie

Ajouter fichier1.md à l’index de Git (zone de Staging)

Exécuter git status et copier/coller la sortie

Créer un commit avec pour message : “Ajout de fichier1.md”

VALIDATION PROF01

Exécuter git status et copier/coller la sortie

Modifier fichier1.md et enregistrer

Exécuter git status et copier/coller la sortie

Ajouter fichier1.md et fichier2.md à la zone de Staging

Créer un commit “Ajout de fichier2.md et modification de fichier1.md”

Exécuter git status et copier/coller la sortie

Copier/coller l’ID des deux premiers commits (utiliser log) :

ID commit 1 :
ID commit 2 :
Que signifie qu’un fichier est “tracked” ou “untracked“ ?

Pourquoi doit-on passer les fichiers par la zone de Staging (l’index) avant de les committer ?