Vous venez d'écrire un programme en C++.
Vous ne voulez pas prendre en compte dans Git les fichier temporaire ou de configuration
Vous décidez de les ajouter au .gitignore

Vous devez créer un fichier .gitignore qui fera les choses suivantes:
 - Ignorer tous les fichiers qui finissent pas ~
 - Ignorer tous les fichiers du dossier ou sauf le fichier conf.ini

 En d'autres termes une fois le .gitignore écrit la commande 'git add .' ne devrait ajouter au stage que les fichiers suivants:
 - .gitignore
 - main.cpp
 - out/conf.ini

 ----------

* English Version *

You just wrote a cpp program that reads it config from a file named conf.ini.
As you don't want to bother adding all files manualy, you have decided to use .gitignore.

You need to create a .gitignore file that will:
 - Ignore all files that end with a ~ (bakup files)
 - Ignore every files in the out directory but conf.ini

In other words, once the .gitignore file written, the command `git add .` should only stage:
 - .gitignore
 - main.cpp
 - out/conf.ini
