# Programmation-orientee-objet-creation-d-une-classe
Créer une classe qui va permettre de simuler la vie d'un data analyst. 

On souhaite créer notre première classe dataAnalyst qui va simuler la vie d'un data analyst. Voici les caractéristiques de la classe :
attributs :
nom (str)
prenom (str)
age (int)
sexe (str)
formationPrecedante (str)
motivation (int valant 100 à l'instanciation)
progression (int valant 0 à l'instanciation)
méthode :
suivreFormation() : chaque fois qu'elle est utilisé diminue la motivation d'une valeur random entre 5 et 25 et augmente la progression d'une valeur random entre 20 et 30
bosserPlus() : chaque fois qu'elle est utilisée augmente la motivation et la progression d'une valeur random entre 10 et 30
echouer() : chaque fois qu'elle est utilisée baisse la motivation d'une valeur random entre 20 et 40 et augmente la progression d'une valeur random entre 20 et 40
reussir() : chaque fois qu'elle est utilisée augmente la motivation d'une valeur random entre 20 et 40 et augmente la progression d'une valeur random entre 10 et 20
Instancie un objet dataAnalyst et indique un nom, un prenom, le sexe et la formationPrecedante. L'attribut motivation vaudra 100 au début et l'attribut progression vaudra 0.

Le programme va automatiquement et aléatoirement lancer des méthodes et afficher le récapitulatif de l'état des attributs motivation et progression. Le programme s'arrête quand la motivation tombe à zéro et affiche "BRAVO TU AS GAGNÉ !!!" ou quand progression atteint 100 et affiche "BRAVO TU AS APPRIS !!!".
