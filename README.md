
# Classification du Cancer du Sein avec K-Nearest Neighbors (KNN)

## Description du Projet

Ce projet utilise un algorithme de classification K-Nearest Neighbors (KNN) pour prédire le diagnostic du cancer du sein (étiquettes : Malin ou Bénin) à partir de caractéristiques biologiques. Le modèle a été évalué à l'aide de métriques standards de classification et vise à illustrer une application pratique de l'apprentissage supervisé.

## Données Utilisées

Les données proviennent du jeu de données [Breast Cancer Wisconsin (Diagnostic)] disponible sur UCI Machine Learning Repository.

- **Caractéristiques** : 30 mesures biologiques telles que la taille de la tumeur, la texture, et la symétrie.
- **Label** : “Malignant” (Malin) ou “Benign” (Bénin).

## Structure du Projet

1. **Exploration des Données** :
   - Visualisations initiales et statistiques descriptives.

2. **Prétraitement des Données** :
   - Encodage des labels.
   - Normalisation des caractéristiques pour améliorer les performances du KNN.

3. **Construction du Modèle** :
   - Séparation des données en ensembles d'entraînement et de test.
   - Implémentation du modèle KNN avec choix du paramètre \( k \).

4. **Évaluation** :
   - Calcul des métriques : Précision.

## Instructions pour Exécuter le Code

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/Eyub4k/Knn-Breast-Cancer.git
   ```

2. Lancez le notebook Jupyter :
   ```bash
   jupyter notebook knn_breast_cancer_pred.ipynb
   ```
4. Suivez les cellules du notebook pour répliquer les résultats.

## Dépendances

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## Résultats

Le modèle KNN a obtenu les résultats suivants :
- **Précision** : 91%

## Améliorations Futures

- Optimisation du paramètre \( k \) avec GridSearchCV.
- Test d'autres algorithmes comme SVM ou Random Forest pour comparer les performances.
- Intégration de pipelines pour automatiser le flux de travail.
