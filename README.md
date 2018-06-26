# Calcul-de-moyenne
Programme qui permettrait de calculer les moyennes.

On veut programmer en JAVA le calcul de la moyenne d'un étudiant. 

a) Créer la classe Note qui comporte les champs: valeur et coefficient. Penser à générer une Exception quand la 
note n'est pas correcte (une note valable doit être dans l'intervalle [0, 20]) ou quand le coefficient fourni est négatif. 

b) Créer la classe Module qui comporte les champs nom, coefficient et crédit et une liste de notes. 

c) Créer la classe Matiere qui comporte le champ nom, coefficient et crédit et une liste de modules.

d) Créer la classe Etudiant qui comporte le champ nom et une liste de matieres. 

e) Créer l'interface Moyennable pour définir la méthode public double moyenne() qui permet de calculer la 
moyenne pondérée des valeurs. 

f) Ajouter cette interface dans les classes Module, Matiere et Etudiant afin de calculer la moyenne par module, par 
matière et la moyenne générale ? Prendre un exemple avec 3 matières comportant chacune 4 modules qui eux même 
possèdent 6 notes (Utiliser pour cela des valeurs aléatoires). 

g) sauvegarder toutes les notes d'un étudiant dans un fichier.

h) lire et ré-générer tous les objets à partir de ce fichier.
