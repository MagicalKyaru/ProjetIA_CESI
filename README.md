# Projet IA CESI A4

Projet scolaire basé sur le  Kaggle [HR Analytics Case Study](https://www.kaggle.com/vjchoudhary7/hr-analytics-case-study).

Ce projet contient plusieurs dossiers et notebooks jupyters.

Liste des dossiers : 

    Base Data : 
    - Données fournies par l'école
    Datasets :
    - Données traitées
    Models : 
    - Modèles créés
    
Les fichiers notebook contiennent les requirements nécessaires à leur fonctionnement.

Ils sont à exécuter dans l'ordre afin d'obtenir les résultats complets.

Trois librairies sont utilisées pour créer les modèles : 
- [Tensorflow](https://www.tensorflow.org/guide)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [XGBoost](https://www.google.com/search?client=opera&q=XGBoost&sourceid=opera&ie=UTF-8&oe=UTF-8)

Chaque librairie fournit des résultats concluants. Certains modèles ont été travaillés avec un [SMOTE-NC](https://medium.com/analytics-vidhya/smote-nc-in-ml-categorization-models-fo-imbalanced-datasets-8adbdcf08c25) afin d'augmenter artificiellement la taille du dataset, celui-ci étant déséquilibré.

La représentation des données via des graphiques se fait grâce à la librairie [ipyvizzu](https://github.com/vizzuhq/ipyvizzu). Les graphiques étant tous animés, il se peut que les notebooks soient lents sur votre machine.

Le fichier `1.1 Clustering.ipynb` est un essai de différentes technologies telles que :
-  [PCA](https://fr.wikipedia.org/wiki/Analyse_en_composantes_principales)
- [t-SNE](https://fr.wikipedia.org/wiki/Algorithme_t-SNE)
- [UMAP](https://en.wikipedia.org/wiki/Nonlinear_dimensionality_reduction)
- [MCA](https://en.wikipedia.org/wiki/Multiple_correspondence_analysis)
