# Carte
* 35 cartes, réparties en 7 manches (8,7,6,5,4,3,2)
1. 7 éclair
2. 7 tonnerres
3. 21 carte _meteo_
* 18 jetons obstacles, avec une couleur d'un côté (jetons de couleurs??)
* 30 tuiles recto-verso (5joueurs, 6 par couleur)
* 6 meeples animaux (mm couleur que les tuiles)
* 1 plateau central
* 5 pions noir pour compter les points, de formes différentes

# Répartition des cartes
* T: `tonnerre`
* E: `eclair`
* x: **meteo**
  * `soleil`
  * `pluie`
  * `vent`
* |: séparation manche

> E x x x x x x T | E x x x x x T | E x x x x T | E x x x T |  E x x T |  E x T | E T

# Tuiles
* renard (#a35b1c)
* herisson (#000000)
* lièvre (#068a1c)
* ecureuil (#cc0000)
* mouton (#f7e81b)
* sanglier (#b8b8b8)

Face avec dessin pour jouée, face sans dessin pour ne pas jouer

# Contrainte
* ne peut pas jouer: la couleur ne peut pas être jouée (`interdit`)
* double les points: les points marqués par l'animal de cette couleur sont doublés (`x2`)
* reviens sur ses pas: l'animal de la couleur ne change pas de direction mais fait demi tour (`demiTour`)
* rien: pas de contrainte (`vide`)
* pas de points: l'animal de la couleur peut être joué mais ne marque pas de points (`x0`)