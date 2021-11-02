# Model Selection Sklearn

Dans le cours Initiez-vous au machine learning, vous avez découvert les fondements de l'analyse de donnée automatisée. Dans ce deuxième cours, vous apprendrez à évaluer vos algorithmes pour les rendre plus performants. 

## Comprenez ce qui fait un bon modèle d’apprentissage

* En apprentissage supervisé, le but est de produire des modèles qui **généralisent**, c’est-à-dire qui sont capables de faire de bonnes prédictions sur de nouvelles données.
  
* De bonnes performances sur le jeu d’entraînement **ne garantissent pas** que le modèle sera capable de généraliser !
  
* On cherche à développer un modèle qui soit suffisamment complexe pour bien capturer la nature des données (et éviter ainsi le sous-apprentissage), mais suffisamment simple pour éviter le **sur-apprentissage**.
  
* Attention aux **contraintes de temps de calcul** et aux **ressources en mémoire** !