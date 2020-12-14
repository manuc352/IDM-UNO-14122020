# IDM-UNO-14122020

## Question 1
Il y a une infinité de variantes de Uno.
Le feature Model implémenté ici prend en compte 3528 configurations possibles.
Il se trouve dans le répertoire UnoFeatureModel


## Question 3

## Question 4
Je développerais ce générateur en implémentant un compilateur prenant en charge la grammaire xtext créée pour la questions 2. Ce compilateur permettra de générer du text en fonctions du code écrit dans la grammaire.

## Question 5
Pour transformer un programme écrit avec mon DSL en un fichier Json et inversement, on pourrait écrire un second compilateur. On pourrait ajouter des instructions permettant de savoir si il s'agit d'un fichier JSON ou d'un programme avec le DSL. Pour cela il faudrait ajouter dans la grammaire xtext, la possibilité d'inclure du JSON.

Une fois que ceci est fait, on implémente le compilateur qui transforme le programme en Json et inversement.
