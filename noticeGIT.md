# NOTICE GIT

##  Titre
Dans ce paragraphe nous allons vous expliquer comment __*fonctionne*__ et __*changer*__ un titre en **GIT**.

#### Titre:

Pour créé des **titres** on utilise le dièse `#` autant de **dièse** que la valeur de la balise  `<h>` **un dièse pour un h1 deux dièses pour un h2**. 
 		
 		
 		 #titre sera l'équivalent d'un <h1> en html.
  		##titre2 sera l'équivalent html d'un <h2>
  		###titre3 #####titre4 ainsi de suite jusque au 6.

## Resumé
***Git*** est un **logiciel libre** qui a été créé en **2005** par le créateur de **Linux**, **Linus Torvalds**. Au départ, il a créé ce <em><strong>logiciel de gestion de version pour gérer les sources de son noyau open source.</em></strong> Il s'agit ainsi d'un **logiciel de versioning** qui permet de **conserver** un **historique des modifications**.
# Commande Git
##  Git Status
***git status*** affiche **l'état** du **répertoire de travail** et de la **zone de staging**. Elle vous permet de voir les **changements qui ont été stagés**, ceux qui **ne l'ont pas été**, ainsi que **les fichiers qui sont trackés par Git**. 
##  Git Clone
__*git clone*__ est un utilitaire de ligne de commande Git utilisé pour cibler un **dépôt existant** et créer un **clone** ou une copie du **dépôt cible**.


   `git clone ssh://john@example.com/path/to/my-project.git`
   
   `cd my-project`
   
   
##  Git Add
***Git add*** ajoute un changement dans le **répertoire de travail** à la zone de **staging**. Elle informe **Git** que vous voulez inclure les mises à jour dans un **fichier particulier du commit suivant**. 

Cependant, ***Git add*** n'impacte pas le **dépôt de manière significative**. Les changements **ne sont pas réellement enregistrés** jusqu'à ce que vous exécutiez ***Git commit***.

#### Utilisation de la commande Git Add
`git add <file>`

Permet de **stager** tous les changements dans `<fichier>` pour le **commit suivant**.

`git add <directory>`

Permet de **stager** tous les changements dans `<répertoire>` pour le **commit suivant**.

##  Git Commit
***Git commit*** capture un **instantané des changements actuellement stagés du projet**. Les **instantanés commités** peuvent être considérés comme des **versions « sûres » d'un projet**. Avant d'exécuter `git commit`, `git add` est utilisée pour **promouvoir ou « stager »** les **changements** apportés au projet qui seront stockés dans un **commit**. Ces deux commandes `git commit` et `git add` font partie des plus **fréquemment utilisées**.

#### Utilisation de la commande Git Commit
`git commit` 

**Commitez l'instantané stagé**. Cette action lancera un **éditeur de texte** qui vous demandera un **message de commit**. Après avoir saisi un message, **enregistrez le fichier** et **fermez l'éditeur** pour créer le **commit réel**.

`git commit -m "commit message"`

Une **commande de raccourci** qui **crée** immédiatement un **commit** avec un **message de commit transmis**. 
##  Git Push
__*Git push*__ est utilisée pour charger le contenu d'un __dépôt local__ vers un __dépôt distant__. Le __push__ vous permet de transférer les __commits__ de votre __dépôt local__ vers un __dépôt distant__. C'est l'équivalent de `git fetch`, mais à l'inverse du __fetch__ qui importe les __commits__ dans des __branches locales__, le push les exporte vers des __branches distantes__. 

Ces dernières sont configurées à l'aide de la commande `git remote`. Le __push__ est susceptible d'écraser les changements. Vous devez donc prendre des précautions lorsque vous **l'exécutez**. 

#### Utilisation de la commande Git Push
`git push <remote> <branch>`

##  Git Pull
***Git pull*** est utilisée pour faire un **fetch** du contenu d'un **dépôt distant** et pour le télécharger, puis pour mettre à jour immédiatement le **dépôt local** qui correspond à ce contenu. Faire un **merge** des changements en amont dans votre **dépôt local** est une tâche courante dans les **workflows Git**. 

La commande `git pull` est en fait la combinaison de **deux autres commandes**, `git fetch` suivie de `git merge`. Lors de la première étape, `git pull` exécute une commande `git fetch` étendue à la **branche locale** vers laquelle **HEAD pointe**. Une fois le contenu téléchargé, `git pull` entre un **workflow de merge**. Un nouveau commit de **merge** est créé et **HEAD** est mis à jour pour pointer vers le **nouveau commit**.

#### Utilisation de la commande Git Pull
`git pull <remote>`

Faites un **fetch** de la copie de la **branche actuelle** du **dépôt spécifié** et mergez-la immédiatement dans la **copie locale**.

##  suivi.md

