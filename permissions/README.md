# Projet : Shell, permissions

Ce dépôt contient l'ensemble des scripts de la série d'exercices sur la gestion des permissions sous Linux (Holberton School).


* **0-iam_iam**: Affiche le nom de l'utilisateur actuellement connecté.
* **1-who_am_i**: Affiche le nom d'utilisateur effectif de l'utilisateur connecté.
* **2-groups**: Affiche tous les groupes dont l'utilisateur actuel est membre.
* **3-new_owner**: Change le propriétaire du fichier `hello` pour le mettre à `betty`.
* **4-empty**: Crée un fichier vide nommé `hello`.
* **5-execute**: Ajoute la permission d'exécution au fichier `hello` pour le propriétaire.
* **6-multiple_permissions**: Ajoute la permission d'exécution au fichier `hello` pour le propriétaire et le groupe, et la lecture pour les autres.
* **7-everybody**: Ajoute les permissions de lecture, écriture et exécution à tout le monde sur le fichier `hello`.
* **8-james_bond**: Modifie les permissions du fichier `hello` pour qu'il n'y ait aucune permission pour le propriétaire et le groupe, et toutes les permissions pour les autres (`--x--x--x`).
* **9-john_doe**: Attribue les permissions spécifiques `-rwxR----` au fichier `hello`.
* **10-mirror_permissions**: Copie les permissions du fichier `u5` sur le fichier `hello`.
* **11-directories_permissions**: Ajoute les permissions d'exécution pour le propriétaire, le groupe et les autres sur tous les sous-dossiers de manière récursive.
* **12-directory_permissions**: Crée un répertoire nommé `my_dir` avec les permissions `751`.
* **13-change_group**: Change le groupe propriétaire du fichier `hello` pour le groupe `school`.
* **14-change_owner_and_group**: Change de manière récursive le propriétaire (`vincent`) et le groupe (`staff`) de tous les fichiers et répertoires du dossier courant.
* **15-symbolic_link_permissions**: Change le propriétaire (`vincent`) et le groupe (`staff`) du lien symbolique `_hello` lui-même.
* **16-if_only**: Change le propriétaire du fichier `hello` à `vincent` uniquement si le propriétaire actuel est `guillaume`.

