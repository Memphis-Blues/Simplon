#Commandes GitBash vues le jeudi 17 octobre 2024 :

* $ git clone [URL valide] 
=> clone le repo Github dans la zone sélectionnée pour ouvrir GitBash.

* $ git add README.md (ou autre nom+extension de fichier)
=> charge / sélectionne le fichier souhaité. (Ici README.md !)
Indexe le fichier, le sélectionne. On l’indexe pour le commit. 

* $ git commit -m “Update README.md” 
=> commit = enregistre les changements dans les répertoires, dans ceux qui ont été indexé (add). 
 -m = enregistre un message aditionnel (commentaire) pour l'upload du fichier. 

* $ git push 
=> Envoi tout ce qui a été commit, au repo cible. (repository / répertoire)

* $ git config --global user.name “Memphis-Blues” 
=> Configurer le pseudonyme de l'usager sur GitHub (lorsqu'on commence). 
=> [Chat-GPT] Définir le nom d'utilisateur associé à vos commits Git. 
Pour tout commit, ce nom apparaîtra dans l'historique des commits, permettant ainsi d'identifier qui a fait les changements.
L'option `--global` indique que ce paramètre s'applique à tous les dépôts Git de votre système. 
Si vous souhaitez définir un nom d'utilisateur spécifique pour un projet particulier, 
vous pouvez omettre l'option `--global` et exécuter la commande dans le répertoire du dépôt concerné. 
Essentielle pour personnaliser vos contributions dans Git et GitHub.

* $ git config --global user.email “[Ad email valide]”
=> [Chat-GPT] définit l'adresse e-mail associée à vos commits Git. 
Elle apparaîtra dans l'historique des commits, permettant d'identifier l'auteur des changements.
L'option `--global` signifie que l'adresse e-mail sera utilisée pour tous les dépôts Git en local. 
Pour définir une adresse e-mail spécifique sur un projet particulier, retirez `--global`, exécutez la commande dans le répertoire de ce dépôt.
Essentielle pour que vos contributions sont correctement identifiées dans Git et sur GitHub.
