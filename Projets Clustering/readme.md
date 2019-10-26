 Ce repository comporte deux projets de clustering utilisant les Kmeans et DBScan:
 
 1. Un premier exercice de clustering permettant d'identifier des catégories de clients et d'analyser leurs dépenses (Spending Score) en fonction de différentes features
 
 2. Une analyse graphique d'un jeu de données des courses Uber d'Avril 2014 à New York en utilisant d'abord les Kmeans puis DBScan.
 L'utilisation de 4 Kmeans permet d'identifier 4 zones correspondant à :
 - Downtown Manhattan
 - Uptown Manhattan
 - Brooklyn
 - Queens et JFKAirport
 
 L'utilisation de DBScan (avec un min_sample de 10) permet d'identifier, outre le bruit:
 - Manhattan
 - Le quartier de Williamsburg à Brooklyn
 - Le quartier autour de Brooklyn Park
 - Laguardia Airport
 - JFG Airport
 
 Ce modèle peut effectivement être réaffiné dans de prochains travaux.
