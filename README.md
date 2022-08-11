# Documentation git


| Fonctionnalité                                         | Ligne de code correspondant              |
|--------------------------------------------------------|------------------------------------------|
| Modifier son user.name                                 | git config --global user.name            |
| Modifier son email                                     | git config --global user.email           |
| Voir les configues git                                 | git config --list                        |
| Créer un dépôt git local                               | git init                                 |
| Ajouter un fichier                                     | git add fichier.ext                      |
| Ajouter un dossier                                     | git add dossier                          |
| Ajouter tous les fichiers                              | git add *                                |
| Ajouter les fichiers d'une extension spécifique        | git add*.ext                             |
| Montre l'état des fichiers en montrant les changements | git status                               |
| Création de version avec message                       | git commit -m "message"                  |
| Voir l'historique de nos changements                   | git log                                  |
| Voir l'histore avec une ligne par commit               | git log --oneline                        |
| Voir un nombre précis de commit                        | git log -n <nombre>                      |
| Voir l'historique des commits affectant un fichier     | git log -p <fichier>                     |
| Voir l'historique des commits par rapport à un auteur  | git log --author <nom_auteur>            |
| Voir toutes les branches                               | git branch                               |
| Changer de branche                                     | git checkout <nom_branch>                |
| Voir le code a un commit particulier                   | git checkout <hash_commit>               |
| Avoir un fichier précis à un commit précédent          | git checkout <hash_commit> <nom_fichier> |
| Revenir à l'étape du commit                            | git revert <nom_commit>                  |
| Revenir en arrière                                     | git reset                                |
| Créer une branch                                       | git branch <nom>                         |
| Stocke temporairement les changements                  | git stash                                |
| Envoyer vos changements dans le repo distant           | git push                                 |

  
 # Documentation ligne de commande git bash
  
  | Fonctionnalité                    | Ligne de code correspondant |
|-----------------------------------|-----------------------------|
| Lister le contenu d'un répertoire | ls                          |
| Créer un répertoire ou dossier    | mkdir <nom>                 |
| Supprimer un fichier              | rm <nom>                    |
| Supprimer un dossier et contenu   | rm -r <nom>                 |
| Créer un fichier                  | touch <nom>                 |
| Lire un fichier                   | cat <nom>                   |
| Naviguer dans notre file system   | cd                          |
| Naviguer en arrière               | ../                         |
| Dire a partir de ce file          | ./                          |
| Voir le chemin                    | pwd                         |
| Voir la taille d'un dossier       | du -h                       |
