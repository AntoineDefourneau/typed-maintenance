# Description
typed.js est une librairie JS permettant d'animer des textes et de donner l'impression qu'ils sont rédigés en temps réel au clavier.
Cette librairie comportent différents callback comme onStringTyped() qui est appelé quand la chaine a finit d'être tapée, ou encore onTypingPaused() quand l'animation est mise en pause.
J'ai trouvé intéressante l'idée d'ajouter un callback onCharTyped() qui est appelé à chaque caractère tapé lors de l'animation.
# Idées d'application
Cette méthode de callback pourait être utilisée pour par exemple :
* Jouer un son de touche de clavier à chaque lettre
* Faire des modifications esthétiques à chaque caractère tapé, comme changer la couleur du texte
# Utilisation
Importer le fichier typed.js dans le document HTML utilisé.
