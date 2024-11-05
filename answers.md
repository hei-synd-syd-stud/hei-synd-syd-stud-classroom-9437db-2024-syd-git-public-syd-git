# Answers of Loris Charrex LorisCharrex

## Basics

### Task 1

Visualisation:

<img title="" src="file:///C:/Users/loris/Desktop/Semestre 3/S3fa SystemDesign/Github/2024-syd-git-public-LorisCharrex/img/Task1IMG.png" alt="logo" data-align="center">

On trouve les fichier suivants:

1. dossier ".git"

2. dossier image

3. fichier markdown ou .md pour les réponses

Le dossier .git est normalement caché puisqu'il est grisé. Il contient des dossiers et des fichiers:

Dossiers.

- **hooks:** Ce dossier contient des scripts qui s'exécutent automatiquement à des moments clés du cycle de vie d'un dépôt Git (par exemple, avant ou après un commit). Ils permettent d'automatiser certaines tâches.
- **info:** Ce dossier contient des informations supplémentaires sur le dépôt, souvent spécifiques à un système particulier.
- **logs:** Ce dossier stocke les journaux des opérations Git, ce qui peut être utile pour le débogage ou l'audit.
- **objects:** C'est ici que sont stockés les objets Git (commits, arbres, blobs) qui constituent l'historique de votre projet.
- **refs:** Ce dossier contient des pointeurs vers les différents objets Git, notamment les branches et les tags.

Fichiers:

- **config:** Ce fichier contient les paramètres de configuration du dépôt, tels que le nom de l'utilisateur, l'adresse e-mail, etc.
- **description:** Ce fichier contient une description courte du projet.
- **HEAD:** Ce fichier spécial pointe vers le commit actuellement vérifié (la branche sur laquelle je travaille).
- **index:** Ce fichier, aussi appelé "index de staging", contient une liste des modifications que j'ai préparé pour le prochain commit.
- **packed-refs:** Ce fichier contient une version compressée des références pour améliorer les performances.

### Task 2

<img title="" src="file:///C:/Users/loris/Desktop/Semestre 3/S3fa SystemDesign/Github/2024-syd-git-public-LorisCharrex/img/Task2IMG.png" alt="logo" data-align="center">

Lors de la commande `git status`, le fichier *answers.md* apparaît en rouge car il été modifié. Ces fichiers doivent être préparé pour être commité

Les fichiers *README.md* ainsi que l'image sont des fichiers qui apparaissent en rouge car ils ne soint pas encore suivis par Git. Ils ne sont pas encore enregistré dans l'historique du dépôt.

Lors de la commande  `git log --oneline`, il n'y a aucun **changement**.

### Task 3

<img src="file:///C:/Users/loris/Desktop/Semestre%203/S3fa%20SystemDesign/Github/2024-syd-git-public-LorisCharrex/img/Task3IMG.png" title="" alt="logo" data-align="center">

Les fichiers en vert dans la sortie de `git status`  signifient que la première étape pour enregistrer ces modifications dans mon dépôt Git a été faite. Ils sont désormais dans la _Staging Area_. Il ne reste plus qu'à exécuter la commande `git commit` pour créer un nouveau commit et enregistrer ces modifications de manière permanente.

Le fichier _answers.md_ est toujours dans le même endroit.

### Task 4

<img src="file:///C:/Users/loris/Desktop/Semestre%203/S3fa%20SystemDesign/Github/2024-syd-git-public-LorisCharrex/img/Task4IMG.png" title="" alt="logo" data-align="center">

Le fichier _README.md_ a été modifié et il est donc de retour dans la partie non commité car il n'est plus préparé pour faire un commit.

### Task 5

![logo](C:\Users\loris\Desktop\Semestre%203\S3fa%20SystemDesign\Github\2024-syd-git-public-LorisCharrex\img\Task5IMG.png)



La ligne _361a2a3 (**HEAD** -> **Main**) ADD: README file_ 

- 361a2a3 : C'est le hash du commit

- **HEAD** -> **MAIN** : indique que ce commit est le dernier sur la branche **MAIN**

- ADD : README file : Est le message de commit, indiquant que ce commit a ajouté un fichier nommé _README.md_.

La ligne *5da930b (**origin/main**, **origin/HEAD**) Intial commit*

- 5da930b: C'est le hash du commit

- **origin/main**, **origin/HEAD** : indique que cette branche a été synchronisée avec un dépôt distant nommé _origin_.



### Task 6

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)