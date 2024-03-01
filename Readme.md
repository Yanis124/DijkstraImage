## Projet - trouver le chemin le plus court entre deux pixels dans une image

**Commandes :**
- vous pouvez l'éxecuter depuis n'importe quel répertoire : `cd ~/ALGO/Projet && python3 main.py`

**Fonctionnement :**
Le programme permet à l'utilisateur de trouver le chemin le plus court entre deux pixels d'une image en utilisant l'algorithme dijkstra .Pour trouver la distance entre deux pixels on calcule la norme euclidi-enne de la différence entre les valeurs RGB des deux pixels.

1. Il y a un dossier `Image` ou vous pouvez inserer une image sinon vous pouvez travailler sur l'image existante par défaut. 
2. Le programme demande à l'utilisateur de sélectionner deux points en cliquant sur l'image
3. Un boutton `trouver le chemin` s'affichera à l'utilisateur 
4. Une fois que l'utilisateur clique sur le boutton, l'algorithme dijkstra s'éxecute et trace le chemin le plus court en le marquant en vert
5. l'utilisateur pourra recommencer cette opération en cliquant sur le boutton `recommencer`.
