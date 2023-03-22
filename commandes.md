# Historique des commandes :
------------

## Création d'un dépôt :

####  Initialisation du dossier git : (dans le dossier)
*Exécuté 2 fois pour supprimer le dépôt.*
    `git init`

####  Récupération du dossier sur git :
    git pull https://github.com/eddytuto/41e.git

---
## Voir le status :

####  Voir les fichiers modifié : 
    git status

--- 
## Historique :

####  Affichage de l'historique :
    git log
####  Voir les branch et les commits :
    git log --oneline

---
## Naviguer dans les branches :

*On ne peut pas changer de branch si pas valider*

####  Voir les branch :
    git branch
####  Création de branche :
    git branch jf_entete
####  Changement de branch : 
    git checkout jf_entete
####  Création ou Modification de la branch main :

    *change le nom de la branch courante pour main*

    git branch -m main
    git branch -m "nouveau nom"
    

---
## Les commits

#### Ajout des fichiers modifié :
    git add --all

#### Ajout d'un commit :
    git commit -m "c4 création d'un fichier commandes"

####  Revenir sur un commit :
    `git checkout 'id commit'`
    `git checkout 'tag'`
####  Pour revenir au main :
    git checkout main

---
## Les Tag

#### Voir les tag
    git tag

#### Création de tag
    git tag v1.0.0

---
## Alias

####  Création de l'alias vers Github :
    git remote add 41e https://github.com/jeromeFosse/41e-exercice.git
####  Vérification de l'alias :
    git remote -v

---
#### Ajoute dans Github
    git push 41e jf_entete

---
## Merge

#### Merge la branch avec main : (Fast-Forward)
    git merge jf_entete

