# California Housing

Pipeline de régression supervisée pour prédire la valeur médiane des maisons en Californie : feature engineering, comparaison Régression Linéaire vs Forêt Aléatoire, analyse de l'importance des features.


## Données

- **Source** : `fetch_california_housing` (scikit-learn)
- **Cible** : Valeur médiane des maisons en centaines de milliers de dollars


## Modèles entraînés

L'étude s'est concentrée sur la comparaison entre un modèle de Régression Linéaire classique et une approche par Forêt Aléatoire. Ces modèles ont été évalués en mesurant l'erreur quadratique moyenne (RMSE) sur un jeu de test afin de valider leur capacité à prédire précisément les valeurs cibles.


## SetUp

```bash
git clone https://github.com/cestbryan-ng/Random-Forest.git
cd Random-Forest

pip install -r requirements.txt
```