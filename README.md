# QueteGitWCS
Ce dêpot contient toutes les étapes pour créer un commit depuis le terminal ainsi que le lien qui dirige vers le dépôt Git de "Emmet.io". 

* Tout d'abord le lien vers le depôt de "Emmet.io", un plug-in pour IDE très pratique, je vous laisse le découvrir : https://github.com/emmetio.

* Ensuite les étapes permettant de créer un commit depuis le terminal : 

    - Création d'un dépôt ainsi que d'un commit :
    
          $ mkdir ../monprojet
          $ cd ../monprojet
          $ git init 
          $ touch Readme.txt
          $ git status 
          $ git add Readme.txt
          $ git commit -m "Ajout Lisez-moi.txt"
          $ git remove add origin https://github.com/profil/monprojet.git
          $ git remove -v
          $ git push 
    .      
    
    - Création du commit uniquement : 
    
          $ cd ../votreDossier
          $ git init
          
          // vérification du contenu du dossier 
          $ git status 
          
          // ligne suivante pour ajouter un fichier 
          $ git add monfichier.js
          
          // création du commit 
          $ git commit -m "Ajoute monfichier.js."
          
          // connection au depot 
          $ git remove add origin https://github.com/profil/depot
          $ git remove -v
          
          // envoi sur le depot 
          $ git push 
