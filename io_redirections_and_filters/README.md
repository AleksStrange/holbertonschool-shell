# IO Redirections and Filters

Ce dépôt contient une série de scripts bash réalisés dans le cadre du projet Holberton School "io_redirections_and_filters".


* **0-hello_world** : Affiche "Hello, World", suivi d'un saut de ligne, sur la sortie standard.

* **1-confused_smiley** : Affiche un smiley confus `\("(o_o)"\)`

* **2-hellofile** : Affiche le contenu du fichier `/etc/passwd`.

* **3-twofiles** : Affiche le contenu de `/etc/passwd` et de `/etc/hosts`.

* **4-lastlines** : Affiche les 10 dernières lignes du fichier `/etc/passwd`.

* **5-firstlines** : Affiche les 10 premières lignes du fichier `/etc/passwd`.

* **6-third_line** : Affiche la 3ème ligne du fichier `iactu` (sans utiliser `sed`).

* **7-file** : Crée un fichier nommé exactement `*\"Best School\"*'--$?/\*~*` contenant le texte `Best School` suivi d'un saut de ligne.

* **8-cwd_state** : Inscrit le résultat de la commande `ls -la` dans le fichier `ls_cwd_content`. Si le fichier existe déjà, il doit être écrasé, sinon il doit être créé.

* **9-duplicate_last_line** : Duplique la dernière ligne du fichier `iactu`.

* **10-no_more_js** : Supprime tous les fichiers ordinaires (sauf répertoires) ayant une extension `.js`, présents dans le répertoire courant ainsi que dans tous ses sous-répertoires.

* **11-directories** : Compte le nombre de répertoires présents dans le répertoire courant (les répertoires courant et parent ne doivent pas être pris en compte, les répertoires cachés doivent être comptés).

* **12-newest_files** : Affiche les 10 fichiers les plus récents du répertoire courant (un fichier par ligne, du plus récent au plus ancien).

* **13-unique** : Prend une liste de mots en entrée et n'affiche que les mots qui n'apparaissent qu'une fois (format d'entrée : un mot par ligne ; les mots doivent être triés de sortie : un mot par ligne).

* **14-findthatword** : Affiche les lignes contenant le motif "root" issu du fichier `/etc/passwd`.

* **15-countthatword** : Affiche le nombre de lignes contenant le motif "bin" dans le fichier `/etc/passwd`.

* **16-whatsnext** : Affiche les lignes contenant le motif "root" ainsi que les 3 lignes qui les suivent dans le fichier `/etc/passwd

* **17-hidethisword** : Affiche toutes les lignes du fichier `/etc/passwd` qui ne contiennent pas la chaîne "bin".

* **18-letteronly** : Affiche toutes les lignes du fichier `/etc/ssh/sshd_config` qui commencent par une lettre.

* **19-AZ** : Remplace tous les caractères "A" et "c" de l'entrée par, respectivement, "Z" et "e".

* **20-hiago** : Supprime toutes les petites "c" et "C" de l'entrée.

* **21-reverse** : Inverse son entrée.

* **22-users_and_homes** : Affiche tous les utilisateurs ainsi que leur répertoire personnel, triés par utilisateur (le script doit se baser sur le fichier `/etc/passwd`).

