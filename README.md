# exosJava


E1.
Ecrire un algorithme qui demande l'âge d'un enfant. Ensuite, il l'informe de sa catégorie :

« Poussin » de 7 à 9 ans

« Pupille » de 10 à 11 ans

« Benjamin » de 12 à 13 ans

« Minime » de 14 à 15 ans

« Cadet » 16 à 17 ans

—--
Declarer variable integer age;

Obtenir l’age tapé par l’utilisateur.

Si age<7 alors renvoie “invalide”

Sinon si age<=9 alors renvoie “poussin”

Sinon si age<=11 alors renvoie “pupille”

Sinon si age<=13 alors renvoie “benjamin”

Sinon si age<=15 alors renvoie “minime”

Sinon si age <=17 alors renvoie “cadet”

Sinon alors renvoie “invalide”

—-
E2.
Ecrire un programme Java qui demande à l'utilisateur de saisir la valeur du diamètre, et qui ensuite va effectuer le calcul de la surface.

Surface = Rayon x Rayon x PI;

Rayon = Diamètre / 2
—-

Declarer valeur diametre float

declarer float rayon

declarer float pi

declarer float surface

surface=rayonxrayonxpi

rayon=diametre/2


—
E3.
Ecrire un programme Java qui demande à l'utilisateur de saisir son nom, prenom et age, et qui ensuite va afficher le message : "Vous vous appelez <prenom> <nom>, et vous avez <age> ans"
—-
  
declarer nom, prenom string
  
declarer age int
  
recuperer prenom, nom et age
  
print "Vous vous appelez <prenom> <nom>, et vous avez <age> ans"



—
E4.
Ecrire un programme Java qui déclare 3 variables, a,b,c et qui va ensuite effectuer une permutation de ces valeurs :
Exemple : 
Entrez la première valeur(a) : 51
Entrez la deuxième valeur(b) : 876
Entrez la troisième valeur(c) : 235
Les valeurs entrées sont : a = 51, b = 876 et c = 235
Permutation: b <== a, c <== b, a <== c
Les valeurs permutées sont : a = 235, b = 51 et c = 876
—
                                    
declarer int a,b,c
                                    
intermediaire=b
                                    
b=a
                                    
a=c
                                    
c=intermediaire

Print 
Les valeurs permutées sont : a = 235, b = 51 et c = 876


—

E5.
Ecrivez un programme Age.java qui :
declare l'âge de l'utilisateur ;
lit la réponse de l'utilisateur et l'enregistre dans une variable age de type entier ;
Effectue le calcul de l'année de naissance de l'utilisateur et l'enregistre dans la variable annee de type entier ;
affiche l'année de naissance ainsi calculée.

Exemple d'exécution du programme: 
age = 30
Votre année de naissance est : 1992
—-
  
declarer int age 
  
recuperer age
  
declarer int anneeNaissance
  
anneeNaissance=2022-age
  
print Votre année de naissance est : 1992

