Tous ce qui est controllers, entities, interfaces et repositories sont dans le dossier App.

Tous ce qui est configurations des routes/controllers est dans le fichier config\RouteConfig.php.

Tous ce qui est configurations de la base de données est dans le fichier config\BddConfig.php.

Toutes les methodes (differentes de celle de base) qu'on veux ajouter a une entity se met dans le repository correspondant a l'entity.

Tous les éléments qu'on veut rendre obligatoire dans toutes les entities sont présent dans le fichier Core\Repository\CoreRepository.php.

Toutes les vues sont dans le dossier templates.


Tous ce qui sera visible publiquement sera present dans le dossier public (css, js, ...). Le dossier public est celui qui sera utilisé par defaut pour lancer l'autoloader et le kernel du mvc.