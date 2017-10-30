# QueteGitWCS
Ce dêpot contient toutes les étapes pour créer un commit depuis le terminal ainsi que le lien qui dirige vers le dépôt Git de "Emmet.io". 

* Tout d'abord le lien vers le depôt de "Emmet.io", un plug-in pour IDE très pratique, je vous laisse le découvrir : https://github.com/emmetio.

* Ensuite les étapes permettant de créer un commit depuis le terminal : 

    - Création d'un dépôt ainsi que d'un commit :
    
          $ mkdir ../monprojet
          $ cd ../monprojet
          $ git init 
          $ touch Readme.md
          $ git status 
          $ git add Readme.md
          $ git commit -m "Ajout Lisez-moi.md"
          $ git remote add origin https://github.com/profil/monprojet.git
          $ git push -u origin master
    .      
    
    - Création du commit uniquement : 
    
          $ cd ../votreDossier
          
          $ git status 
          
          // Pour un fichier
          $ git add monfichier.js
          
          // Pour tous les fichier
          $ git add * 
          
          // création du commit 
          $ git commit -m "Ajoute monfichier.js."
          
          // envoi sur le depot 
          $ git push 
