# Analyse Auto-MPG : Régression et Clustering

Ce projet analyse le dataset Auto-MPG pour explorer les relations entre les caractéristiques des véhicules et leur efficacité énergétique (miles per gallon - MPG). Il combine prétraitement des données, analyse exploratoire, modélisation en régression et clustering.

---

## Étapes principales

### 1. **Prétraitement des données**
- Identification et traitement des valeurs manquantes.
- Normalisation et standardisation des données pour une meilleure performance des modèles.
- Encodage des variables catégoriques comme l'origine des véhicules.

### 2. **Analyse exploratoire (EDA)**
- Étude statistique des caractéristiques des véhicules (distributions, moyenne, etc.).
- Visualisation des relations entre les variables et leur impact sur le MPG (scatter plots, heatmaps, etc.).

### 3. **Régression**
- Construction d’un modèle de régression linéaire pour prédire le MPG en fonction des autres attributs (cylindrée, poids, puissance, etc.).
- Évaluation du modèle avec des métriques comme :
  - L'erreur quadratique moyenne (MSE).
  - Le coefficient de détermination (R²).

### 4. **Analyse en Composantes Principales (ACP)**
- Réduction de dimension pour mieux comprendre la structure des données.
- Visualisation des axes principaux qui expliquent la majorité de la variance.

### 5. **Clustering**
- Application de l’algorithme K-means pour regrouper les véhicules en clusters homogènes.
- Interprétation des clusters pour identifier les segments de véhicules similaires.

---

## Prérequis

Pour exécuter ce projet, assurez-vous d’avoir Python 3.8+ et les bibliothèques suivantes installées :
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Si vous ne les avez pas encore, vous pouvez les installer avec :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
