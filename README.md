# Algorithmique-et-pseudo-code

ALGORITHME NombreMaxBonbons

ENTRÉE : 
Argent=10 // montant d’argent disponible 
Bonbon_prix=0,67 // Prix unitaire d’un bonbon

SORTIE :
nombre_max_bonbons // nombre de bonbon que tu peux acheter avec ton argent, s’exprime en chiffre entier

DÉBUT :

Si argent =>0,67 acheter bonbon

Alors nombre_max_bonbons = +1 ; argent_restant = argent - (prix bonbon x nbonbon acheté)

Tant que argent_restant => bonbon_prix faire une boucle

Fin si argent_restant < 0,67 ET nombre_max_bonbons = chiffre entier 

Fin tant que 

Retourner nombre_max_bonbons

Fin algorithme 
