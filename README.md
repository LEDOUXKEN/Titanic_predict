# Prédiction de la Survie sur le Titanic

Ce projet vise à prédire la survie des passagers du Titanic en utilisant des techniques de machine learning. Il inclut le nettoyage des données, l'exploration, la modélisation et l'optimisation des performances des modèles.

## Auteur
- **Fidèle Ledoux**

## Résumé du Projet
L'objectif de ce projet est d'analyser les données des passagers du Titanic et de prédire leur survie en fonction de leurs caractéristiques personnelles et socio-économiques. Plusieurs modèles de machine learning sont testés, notamment la régression logistique, la forêt aléatoire (Random Forest) et le SVM. Les résultats sont interprétés pour identifier les facteurs les plus déterminants dans la survie des passagers.

## Fonctionnalités
- Nettoyage et préparation des données.
- Exploration des données avec visualisations.
- Création de nouvelles variables explicatives.
- Entraînement et évaluation de plusieurs modèles de machine learning.
- Optimisation des hyperparamètres pour améliorer les performances.
- Analyse de l'importance des caractéristiques.

## Technologies Utilisées
- **Python** : Langage de programmation principal.
- **Pandas** : Manipulation des données.
- **NumPy** : Calculs numériques.
- **Matplotlib/Seaborn** : Visualisation des données.
- **Scikit-learn** : Implémentation des modèles de machine learning.

## Structure du Projet
- **Titanic_predict.ipynb** : Notebook Jupyter contenant l'analyse complète et le code.
- **test.csv** : Fichier de données utilisé pour l'analyse.

## Résultats Clés
- Le modèle Random Forest a obtenu la meilleure précision (100% sur les données de test après optimisation).
- Les variables les plus importantes pour prédire la survie sont :
  - `Sex_male` et `Title_Mr` (négativement corrélées avec la survie).
  - `Fare` (positivement corrélée avec la survie).
  - `Pclass` (la classe du billet).

## Comment Utiliser ce Projet
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre_utilisateur/titanic-survival-prediction.git

2.Installez les dépendances :
pip install pandas numpy matplotlib seaborn scikit-learn

3.Exécutez le notebook Titanic_predict.ipynb avec Jupyter Notebook ou Jupyter Lab.

Contributions
Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet, ouvrez une issue ou soumettez une pull request.

Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

