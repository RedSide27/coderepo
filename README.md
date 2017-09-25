# Aide mémoire de code
2017-09-25
``` bash
# Initialiser un projet git
$ git init

``` bash
# faire le lien entre ton dépot github et ton code local
git remote add origin https://github.com/username/repo.git

``` bash
# config global de base
$ git config --global user.name "ton nom/username"
$ git config --global user.email "ton@mail.com"

``` bash
# voir les fichiers modifiés qu'on ajoute au commit
$ git status

``` bash
# ajouter un ou les fichiers
$ git add .
$ git add index.php


``` bash
# Faire un commit avec un message
$ git commit -m "ton message"

``` bash
# envoyer le shit sur github
$ git push -u origin master
$ git push -u origin autrebranche

``` bash
# merge le nouveau code avec ton ancien
$ git pull

``` bash
# créer une branche pis switcher dessus directement
$ git checkout -B nomdelabranche

``` bash
# Supprimer la branche
$ git branch -D branche

``` bash
# switch de branche
$ git checkout nomdelabranche

``` bash
# pull une branche en particulier (va chercher)
$ git pull origin branch

``` bash
# merge une branche a master (fusionner la branche avec master)
$ git merge labranche

``` bash
# décoller un serveur php pour visualiser le site sur le navigateur
php -S localhost:8080
