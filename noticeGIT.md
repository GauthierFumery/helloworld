# NOTICE GIT

##  Titre
Dans ce paragraphe nous allons vous expliquer comment __*fonctionne*__ et __*changer*__ un titre en GIT.

#### Titre:

Pour créé des titres on utilise le dièse `#`  autant de dièse que la valeur de la balise  `<h>`un dièse pour un h1 deux dièses pour un h2. 
 		
 		
 		 #titre sera l'équivalent d'un <h1> en html.
  		##titre2 sera l'équivalent html d'un <h2>
  		###titre3 #####titre4 ainsi de suite jusque au 6.

## Resumé
Git est un logiciel libre qui a été créé en 2005 par le créateur de Linux, Linus Torvalds. Au départ, il a créé ce <em><strong>logiciel de gestion de version pour gérer les sources de son noyau open source.</em></strong> Il s'agit ainsi d'un logiciel de versioning qui permet de conserver un historique des modifications.
##  Explication
##  git clone
__*git clone*__ est un utilitaire de ligne de commande Git utilisé pour cibler un dépôt existant et créer un clone ou une copie du dépôt cible.


   `git clone ssh://john@example.com/path/to/my-project.git`  
   
   `cd my-project`
   
   
# Start working on the project
##  git add
__*git add*__ ajoute un changement dans le répertoire de travail à la zone de staging. Elle informe Git que vous voulez inclure les mises à jour dans un fichier particulier du commit suivant. 

Cependant, __git add__ n'impacte pas le dépôt de manière significative. Les changements ne sont pas réellement enregistrés jusqu'à ce que vous exécutiez __git commit__.

#### Utilisation de la commande Git Add
`git add <file>`
Permet de stager tous les changements dans <fichier> pour le commit suivant.

`git add <directory>`
Permet de stager tous les changements dans <répertoire> pour le commit suivant.

`git add -p`
Permet de démarrer une session de staging interactif afin de choisir des parties d'un fichier à ajouter au commit suivant. Un bloc de changements apparaîtra, et vous serez invité à saisir une commande. Utilisez y pour stager le bloc, n pour l'ignorer, s pour le diviser en blocs plus petits, e pour le modifier manuellement et q pour quitter.
##  commit
##  push

La commande __git push__ est utilisée pour charger le contenu d'un __dépôt local__ vers un __dépôt distant__. Le __push__ vous permet de transférer les __commits__ de votre __dépôt local__ vers un __dépôt distant__. C'est l'équivalent de `git fetch`, mais à l'inverse du __fetch__ qui importe les __commits__ dans des __branches locales__, le push les exporte vers des __branches distantes__.  

Ces dernières sont configurées à l'aide de la commande `git remote`. Le __push__ est susceptible d'écraser les changements. Vous devez donc prendre des précautions lorsque vous l'exécutez. Ces problèmes sont abordés ci-dessous.

#### Utilisation de la commande Git Push
`git push <remote> <branch>`
##  pull
##  suivi.md

