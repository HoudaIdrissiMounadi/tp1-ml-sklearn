# TP 1 - Apprentissage supervisé avec Scikit-learn

**Module** : Technologies IA - ENSA Fès (ILIA2) - Prof. Youness IDRISSI KHAMLICHI

## Contenu

| Notebook | Sujet | Type |
|---|---|---|
| `notebooks/01_uber_regression.ipynb` | Prédiction du tarif d'un trajet Uber (Linear Regression vs Random Forest) | Régression |
| `notebooks/02_titanic_classification.ipynb` | Prédiction de la survie sur le Titanic (Logistic Regression vs Random Forest) | Classification |
| `notebooks/03_mini_projet.ipynb` | Mini-projet en binôme (à compléter) | Au choix |

## Données

Les CSV ne sont pas versionnés (voir `data/README.md`) :

- `data/uber.csv` : https://www.kaggle.com/datasets/yasserh/uber-fares-dataset
- `data/titanic.csv` : `train.csv` de https://www.kaggle.com/competitions/titanic (renommé)

## Installation

```bash
python -m venv .venv
source .venv/bin/activate        # Windows : .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Workflow appliqué

1. Chargement et exploration -> 2. Nettoyage / feature engineering -> 3. Train/test split
-> 4. Entraînement -> 5. Évaluation (MAE, RMSE, R² / accuracy, F1, matrice de confusion)
-> 6. Comparaison de modèles -> 7. Interprétation.

## Auteurs

- [Nom Prénom 1]
- [Nom Prénom 2]
