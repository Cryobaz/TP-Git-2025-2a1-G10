Question 1 : 
- Les créations c'est OK
- Les merges ça va à peu près étant donné qu'on peut facilement accépter les différents changements, au pire on supprime ce qu'on veut pas garder
- les rebase c'est un peu plus compliqué ça demande de remonter en escalier pour régler les conflits, ça nous a pris pas mal de temps 

en terme de structure chacun à son tp.md (meme l'eleve3 fictif parce qu'on a créé sa branche à partir de celle de l'eleve 1 qui avait déjà fait son tp.md)

Question 2 :
le fetch c'est juste pour récup les commit sans fusionner avec ce qu'on a, alors que le pull ça fusionne en plus 

Question 3
Le reset c'est pour annuler une erreur par exemple, on le fait juste pour annuler un commit (je crois d'ailleurs que ça ne créé pas de commit de reset)
Par contre revert ça créé un commit de revert (il y a pleins d'occasions de se tromper avec les --continue, --skip, --abort, je me suis planté plein de fois j'ai fini par skip parce que j'ai mentalement craqué)

à mon avis c'est dangereux de revert si on revert sur commit qui mène vers un HEAD détaché, alors là bonne chance, c'est comme se reveiller dans un tonneau au milieu de la mer et voir son bateau avancer seul devant nous (et on a pas de rame).