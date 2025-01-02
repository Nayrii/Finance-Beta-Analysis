# Analyse Beta Financière

## Contexte
Ce projet vise à analyser les données financières des principales entreprises du NASDAQ 100. Il inclut la collecte, le traitement et l'analyse des données historiques pour extraire des indicateurs clés tels que la beta, les rendements, et les corrélations entre actifs.

## Fonctionnalités principales

- **Construction de la base de données** :
  - Utilisation de la bibliothèque `yfinance` pour extraire des données financières actualisées.
  - Filtrage des titres du NASDAQ 100 pour constituer un ensemble représentatif.

- **Analyse quantitative** :
  - Calcul de la beta des actifs pour mesurer leur sensibilité aux fluctuations du marché.
  - Analyse des rendements et évaluation des risques.
  - Comparaison de la performance des actifs par secteur.

- **Visualisation des données** :
  - Graphiques pour représenter les rendements cumulés.
  - Heatmaps des corrélations entre actifs.

## Prérequis
- Python 3.9+
- Bibliothèques Python :
  - `pandas`
  - `numpy`
  - `yfinance`

## Structure

```plaintext
Finance_Beta_Analysis/
├── data/ # Dossiers contenant les données extraites et nettoyées.
├── notebook/ # Notebooks Jupyter pour l'analyse exploratoire et quantitative.
│   └── Finance_Beta_Analysis_Notebook.ipynb # Notebook principal.
├── README.md # Documentation du projet (vous y êtes).
