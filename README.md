# Diagrammes de classe - HAUTE ÉCOLE
Réalisez le diagramme de classe (de domaine) correspondant à la description suivante :
<br><br>
On considère l’organisation d’une haute école pour laquelle on à 3 types de membres: Professeurs, assistants et étudiants. On connait le nom et prénom de tous les membres. Par ailleurs, on sait à quelle filière les étudiants appartiennent et dans quel institut les professeurs travaillent.
<br><br>
Chaque professeur est expert dans un certain nombre de disciplines et l’école désirant assurer une certaine redondance, il y a au moins 2 professeurs experts dans chaque discipline. Par ailleurs, chaque assistant doit indiquer son niveau de compétence dans chacune des disciplines proposées. Ce niveau varie entre 1 (faible) et 4 (expert)
<br><br>
Chaque cours est donné par un professeur et encadré par au plus 3 assistants. Par soucis pédagogique, un cours ne peut couvrir de matière que d’une seule discipline. Par soucis financier, l’école n’ouvre pas de cours pour moins de 5 étudiants. 

## Etape 1 : Classes conceptuelles
On considère l’organisation d’une haute école pour laquelle on à 3 types de **membres: Professeurs, assistants et étudiants**. On connait le nom et prénom de tous les membres. Par ailleurs, on sait à quelle filière les étudiants appartiennent et dans quel institut les professeurs travaillent.
<br><br>
Chaque **professeur** est expert dans un certain nombre de **disciplines** et l’école désirant assurer une certaine redondance, il y a au moins 2 professeurs experts dans chaque **discipline**. Par ailleurs, chaque assistant doit indiquer son niveau de compétence dans chacune des disciplines proposées. Ce niveau varie entre 1 (faible) et 4 (expert)
<br><br>
Chaque **cours** est donné par un **professeur** et encadré par au plus 3 **assistants**. Par soucis pédagogique, un **cours** ne peut couvrir de matière que d’une seule **discipline**. Par soucis financier, l’école n’ouvre pas de **cours** pour moins de 5 **étudiants**.

![step1](https://www.plantuml.com/plantuml/png/LOwx3O0m34JxJ945Kj1J104zAo1Y94iXGJwdOtXIy2rzx_JE7ZgBbYrQAEsDMU8Cs8a4EIMwpWxWsajwOyah0LJa2aOjWLy-C1RU8p-2FXU1CRVMjeTp7-i__zZ_u5dnb49z-GG0 "step1")

## Etape 2 : Associations
