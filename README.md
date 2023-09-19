# The_max_flow_algorithm
L'algorithme de flux maximum est un projet open source qui propose une implémentation d'un algorithme permettant de résoudre des problèmes liés aux transports de flux dans un réseau donné (ou graphe orienté et pondéré). Son but est de calculer le flux maximum d'un élément à partir d'une source A vers une destination B tout en respectant les capacités des chemins du réseau.

## Prérequis
Cet algortithme est implémenté avec la bibiliothèque NetworkX. Vous pouvez installer cette dernière avec la commande suivante : 
pip install networkx
Assurez-vous d'avoir la même version de python installée sur votre pc.

## Utilisation
- Vous pouvez cloner ce réferentiel : https://github.com/sidyjames/The_max_flow_algorithm.git.
- Executez le script "maxflow.py".

## Test
- Saisissez les arcs et leurs capacités. Saisir quitter pour terminer et afficher le flux maximal.
- Le script affichera le flux maximal.

## Exemple de test
source,A,5
source,B,10
A,C,12
A,D,10
B,D,8
C,sink,10
D,sink,10
quitter

