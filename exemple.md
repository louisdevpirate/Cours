22/10/2022


# GIT

### Versionner = Initialiser un fichier ou un dossier sous Git 

_Si on devait trouver une façon imagée de versionner un projet sous Git, on pourrait utiliser l'exemple des courses de Noël où on achète les cadeaux au magasin, puis on les fait emballer par une personne bénévole sur une table à papier cadeau, avant de les expédier.
Voyons les différentes commandes et à quoi elles correspondent selon l'exemple que nous avons choisi._ 

`git init` : On rentre dans le magasin, puis on choisit les cadeaux qu'on souhaite mettre dans le caddie.
// Grâce au Terminal, on navigue jusqu'au dossier de notre choix (le moment où on rentre dans le magasin) et on initialise Git dans ce dossier, pour indiquer à Git que c'est l'ensemble du dossier qu'il doit prendre en compte et créer une arborescence (c'est le moment où on met les cadeaux dans le caddie). Une fois Git initialisé, chaque modification des fichiers contenus dans le dossier sera prise en compte par Git. 


`git add` :  Après avoir passé la caisse (où on confirme les cadeaux qu'on a choisi), on se dirige vers le stand pour les emballer. On dépose donc les cadeaux de notre choix sur la table.
// Via la commande git add, on sélectionne quels fichiers on va commiter par la suite. En d'autres termes, quels fichiers sont importants à sauvegarder. 


`git status` : Avant de se préparer à emballer les cadeaux, on fait le point, histoire de savoir quels cadeaux sont sur la table, prêts à être emballés, et quels cadeaux sont restés dans le caddie.
//git status permet de faire un dernier récapitulatif des fichiers qu'on souhaite ou non sauvegarder, avant de les commiter. Le Terminal affichera un compte-rendu du git add précédent, avec une ligne qui affichera lesquels sont pris en compte et une autre qui affichera lesquels ne le sont pas.


`git commit -m "nom de la modification`" : Une fois les cadeaux sélectionnés et posés sur la table, on les emballe tous et on y associe un petit message du type "cadeau pour Og, cadeau pour Laura etc".
//Quand on fait un commit, on décide d'empaqueter tous les fichiers sauvegardés et modifiés, puis on donne un intitulé précis à ce "paquet" afin de savoir quelles modifications ont été apportées. On peut ainsi voir le cheminement de notre code et comment on l'a fait évoluer, étape par étape. Cela permet également, en cas de disfonctionnement du code, de comprendre à quel moment, à l'ajout de quelle étape celui-ci a commencé à bugger, et donc de débugger le code beaucoup plus facilement.
Par exemple : Si j'ai modifié le titre principal d'un fichier en rouge, je créerais alors à la suite de mon git commit un message intitulé "Modification du titre principal en rouge". Cette description des modifications doit être la plus précise possible car elle doit permettre de comprendre fondamentalement quelle modification exacte a été opérée sur ce commit en particulier. 
**Remarque** : Le commit, comme les antibiotiques, n'est pas automatique. Pas besoin de créer un nouveau commit si on a juste ajouté un point virgule à la fin d'une ligne de code. C'est à la personne de faire preuve de jugement sur ce qui lui semble important de décrire comme modification (ajout d'une div, d'une fonction, insertion d'un fichier etc...)


`git push` (facultatif) : Une fois que nos cadeaux sont bien emballés et qu'ils ont leur petit message associé, on peut (ou pas) décider d'aller les placer sous le sapin, afin que tout le monde les voient et puissent les ouvrir. 
//On envoie nos fichiers commités avec l'intitulé de leur(s) modification(s) sur GitHub ou GitLab, afin que d'autres personnes puissent voir le cheminement de notre code et comment on l'a fait évoluer, étape par étape. Si cette partie est facultative c'est uniquement parce qu'il n'est pas obligatoire de présenter son code à d'autres personnes, même si cela s'avérera évidemment essentiel lors du travail en entreprise.


## Objectif semaine prochaine :
- Mettre en forme la page d'accueil (manipuler HTML/CSS)
- Créer un formulaire pour ajouter des films
