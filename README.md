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

![Classes conceptuelles](https://www.plantuml.com/plantuml/png/TOyx3W8n34JxdC8NI45FiMYXvmfHCcWZXIIodOuBSGukHf3sMr1wtlXP7aGTQtic6fCJWP0lsQDgGqeGCy45C7tUwYheHFPFp_zIkeEbv8nvl8Z4xi-wO2uFzEN6St3J5kB6hr5yh2ckWh4q5cCMBPrVrkwintndFuBroe0S-gjV "Classes conceptuelles")

## Etape 2 : Associations
On considère l’organisation d’une haute école pour laquelle on à 3 types de membres: Professeurs, assistants et étudiants. On connait le nom et prénom de tous les membres. Par ailleurs, on sait à quelle filière les étudiants appartiennent et dans quel institut les professeurs travaillent.
<br><br>
Chaque professeur est **expert** dans un certain nombre de disciplines et l’école désirant assurer une certaine redondance, il y a au moins 2 professeurs experts dans chaque discipline. Par ailleurs, chaque assistant doit indiquer son niveau de **compétence** dans chacune des disciplines proposées. Ce niveau varie entre 1 (faible) et 4 (expert)
<br><br>
Chaque cours est **donné** par un professeur et encadré par au plus 3 assistants. Par soucis pédagogique, un cours ne peut **couvrir** de matière que d’une seule discipline. Par soucis financier, l’école n’ouvre pas de cours pour moins de 5 étudiants. 

![Associations](https://www.plantuml.com/plantuml/png/PP4n3i8m34NtdC8NwCA842e2TguG9GOijKbb9uY12t4EBeO5RTh0QF-Vzx-LLfBbbFiETYBHaKqKWvWhMeyChsUo0y8AcbfsdHM14xB4470SrK5A2scIEPvH13EFYsFAdcRzGE9ewAW0zZ6p63DXOVDecWMrtY_ejL1IJ7aAkfxJOAr9_Q2tON1OkpuLrA2AzOnQfiJyGL0Iu7r0Jk3nnpXp1EcY5vgfrbALJ5hpE_tINSmt9eQjCIq6hp_q1W00 "Associations")