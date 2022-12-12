Vous réalisez que vous venez de commiter un fichier de backup: main.cpp~

Les fichiers de backups ne devraient pas être commité, vous devez corriger cette erreur:
- Supprimer le fichier avec 'rm'
- Ajoutez tous les changements (cela incluant la suppression du fichier) avec la commande `git add -A`
- Ajoutez un .gitignore qui empechera de reproduire cette erreur par inadvertance
- Ajoutez le
- Commitez

----------

* English Version *


You just realized that you have commited a backup file: main.cpp~.

Backup files should not be commited, let's correct that mistake.

- Delete the file with `rm`
- Add all changes, including deleted files with `git add -A`
- Write a gitignore that will correct your mistake
- Add it
- Commit
