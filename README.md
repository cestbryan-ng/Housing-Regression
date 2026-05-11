# California Housing

Pipeline de régression supervisée pour prédire la valeur médiane des maisons en Californie : feature engineering (pièces par ménage, chambres par pièce, population par ménage), comparaison des performances entre Régression Linéaire et Forêt Aléatoire via le RMSE, analyse et visualisation de l'importance des features pour identifier les variables les plus déterminantes dans la prédiction du prix immobilier.


## Données

- **Source** : `fetch_california_housing` (scikit-learn)
- **Cible** : Valeur médiane des maisons en centaines de milliers de dollars


## Modèles entraînés

L'étude s'est concentrée sur la comparaison entre un modèle de Régression Linéaire classique et une approche par Forêt Aléatoire. Ces modèles ont été évalués en mesurant l'erreur quadratique moyenne (RMSE) sur un jeu de test afin de valider leur capacité à prédire précisément les valeurs cibles.


## Meilleur modèle

Le meilleur modèle choisi pour la suite de l'étude est la Forêt Aléatoire suite à son meilleur score d'erreur quadratique.


## SetUp

```bash
git clone https://github.com/cestbryan-ng/Housing-Regression.git
cd Housing-Regression

pip install -r requirements.txt
```