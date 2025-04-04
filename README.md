# Circulation_routiere
Ce projet vise à modéliser la circulation routière d'une ville. Les routes de la ville sont représentées sous forme de grille, où la direction de chaque route est également indiquée. Le simulateur permet d'ajouter des obstacles en cliquant droit avec la souris.
Une fonctionnalité est implémentée pour générer des voitures numérotées, chacune ayant une destination. Les voitures ne peuvent pas traverser une case contenant un obstacle. Elles doivent le contourner tout en empruntant le chemin le plus court pour atteindre leur destination. Par ailleurs, une voiture ne peut occuper une case déjà occupée par une autre voiture. Elle doit patienter jusqu'à ce que la case soit libérée.
Les feux de signalisation sont également intégrés dans le projet. Ils fonctionnent avec les durées suivantes :
-	Feu vert : 20 secondes
-	Feu orange : 3 secondes
-	Feu rouge : 8 secondes
Les voitures adaptent leur comportement en fonction des feux : elles avancent si un feu vert se trouve devant elles, ralentissent en cas de feu orange, et s'arrêtent lorsqu'un feu rouge est sur leur chemin. Lorsqu'une voiture atteint sa destination, elle s'arrête pendant 3 secondes, puis disparaît avec l'indication de sa destination. 
