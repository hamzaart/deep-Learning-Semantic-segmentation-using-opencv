
vous apprendrez à effectuer une segmentation sémantique à l'aide d'OpenCV, de l'apprentissage en profondeur et de l'architecture ENet. D'autre part, les algorithmes de segmentation sémantique tentent:

Partitionnez l'image en parties significatives Tout en même temps, associez chaque pixel d'une image d'entrée à une étiquette de classe (personne, route, voiture, bus, etc.).

. a formé ce jeu de données sur le jeu de données @ Cityscapes, une annotation sémantique, au niveau des pixels, de 20 à 30 classes (selon le modèle que vous utilisez). Le modèle que nous utilisons est formé sur 20 classes, notamment:

Sans étiquette (par exemple, arrière-plan) Route Trottoir Bâtiment Mur Clôture Clôture Circulation Légère CirculationSigne Végétation Terrain Ciel Personne Rider Voiture Camion Bus Train Moto Vélo


NB : This is based on a post for Dr Adrian from pyimagesearch !
