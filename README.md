# k-nearest-neighbor-python

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiouaneAbdallah/k-nearest-neighbor-python/blob/main/KnnAvecPython.ipynb)

La méthode des “k plus proches voisins” fait partie des méthodes les plus simples d’apprentissage supervisé pouvant être utilisée pour les cas de régression et de classification.

Les ‘k plus proches voisins’ ou k-nearest neighbors en anglais (d’où l’appellation knn) est une méthode non paramétrique dans laquelle le modèle mémorise les observations de l’ensemble d’apprentissage pour la classification des données de l’ensemble de test.

En effet, cet algorithme est qualifiée comme paresseux (Lazy Learning) car il n’apprend rien pendant la phase d’entraînement. Pour prédire la classe d’une nouvelle donnée d’entrée, il va chercher ses K voisins les plus proches (en utilisant la distance euclidienne, ou autres) et choisira la classe des voisins majoritaires.
