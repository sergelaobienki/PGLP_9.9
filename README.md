					#LOGICIEL DE DESSIN

    • OBJECTIF DU PROJET DE LOGICIEL DE DESSIN

Réalisation d’un logiciel de dessin permettant de faire une description textuelle et la manipuler des figures géométriques à savoir: des cercles, des rectangles, des carrés et des triangles.

    • DESCRIPTION DES FIGURES

Un cercle est une figure géométrique ayant un centre et un rayon. 
Exemple: Cercle(centre=(0,0),rayon=10)

    Un carré est une figure géométrique ayant un origine et un côté.
Exemple: Carre(origine=(5,5), coté=20)

    Un rectangle est une figure ayant un origine, une longueur, une largeur(hauteur).
 La longueur doit être toujours supérieure à la largeur(hauteur).
Exemple: Rectangle(origine=(3,3), longueur=30, largeur=10)

    Un triangle est une figure qui a trois côtés. 
Exemple: Triangle(cote1(2,4), cote2(3,5), cote3(1,0))

    • MANUEL D’UTILISATION

Une figure géométrique est un cercle, un carré, un rectangle, un triangle. 
Cette application possède plusieurs fonctionnalités à savoir:

    •     Créer une figure géométrique
    •     Déplacer une figure géométrique
    •     Afficher une ou un ensemble de figure géométrique
    •     Sauvegarder une ou un ensemble de figure géométrique
    •     Supprimer une figure géométrique
    •     Restaurer une commande précédemment annulée
    •     Annuler la dernière commande
    •     Quitter le programme.

Syntaxes valides pour passer une commande:

    •     Création d'un cercle: NomCercle =Cercle((OrigineX, origineY), rayon)
    •     Création d'un carré: Nomcarre =Carre((Point1_X, Point1_Y), coté)
    •     Création d'un rectancle: NomRectangle =Rectangle((Point1_X, Point1_Y), longueur, largeur)
    •     Création d'un triangle: NomTriangle =Triangle((Point1_X, Point1_Y), (Point2_X, Point2_Y), (Point3_X, Point3_Y)
    •     Création d'un groupe: NomGroupe =Groupe(NomCercle, Nomcarre, NomRectangle, NomTriangle NomTriangle  )
    •     Pour afficher le triangle t1: view t1
    •     Pour déplacer une figure : move(NomFigure, (Point1, Point2))
    •     Pour quitter le programme: exit

Pour passer une commande voici les exemples de commandes valides:

    Pour créer un cercle: c1 =Cercle((0, 0), 50)
    Pour créer un carré: c2 =Carre((0, 0), 30)
    Pour créer un rectancle: r1 =Rectangle((0, 0), 40, 10)
    Pour créer un triangle: t1 =Triangle((0, 0), (2, 2), (4, 0))
    Pour afficher le triangle t1: view t1
    Pour déplacer le cercle c1 : move(c1, (10, 20))
    Pour quitter le programme: Exit

Compilation et execution du projet:

    Le lien pour cloner le projet : (https://github.com/uvsq21922765/PGLP_9.9.githttps://github.com/uvsq21922765/PGLP_9.9.git)

    Pour le compiler et l'exécuter:

    • mvn clean

    • mvn package

    • Exercice_9_9-0.0.1-SNAPSHOT.jar
