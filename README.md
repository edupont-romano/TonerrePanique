# idée
* chaque carte est recto verso
* d'un côté, la météo. De l'autre, les contraintes.
* il y a des animaux au centre. Ils doivent passer par certain points pour scorer.

# Déroulement de la partie
1. Peut retourner deux tuiles visibles contre une cachée. Il peut dans ce cas changer l'orientation d'un animal 
2. Doit choisir une tuile visible, la retourner face cachée et déplacer l'animal correspondant en ligne droit jusqu'au prochain obstacle 
3. tous les autres joueurs retournent cette tuile sur l'autre face 

## obstacles
Si un animal percute un obstacle il s'arrête et let s'oriente dans une autre direction. Si l'obstacle est:
* un animal, celui-ci part en courant
* un obstacle fixe (arbre, bord de plateau, etc), on change de joueur

## cartes meteo
Au début, un eclair. 7 cartes plus loin, un coup de tonnerre. Puis un éclair, 6 cartes plus loin un coup de tonnerre. Puis un éclair, 5cartes plus loin un coup de tonnerre, etc.
1. `vent` déplace  tous les animaux dans une direction 
2. `pluie` change orientation animaux
3. `soleil` ne fait rien
4. `éclair` nouvelle manche, à définir
5. `tonnerre` déclenche une panique tous les animaux partent en courant

# contrainte
* rebond, repars dans le direction d'où il vient
* double, obstacle-->change orientations--> rejoue
* ne peut pas jouer 

# Scoring
Si les obstacles sont colorés, on pourrait imaginer un systeme de points par obstacle, et de multiplicateur si l'obstacle et l'animal sont de même couleur. **à tester**