# Apprentissage automatique et prétraitement des données

Projet de fin de module EMSI (2025-2026) consacré à l’exploration, au prétraitement et à la classification de données tabulaires et textuelles avec Python et scikit-learn.

## Contenu du projet

- [`Projet_EMSI_2025_2026.ipynb`](./Projet_EMSI_2025_2026.ipynb) — notebook Jupyter présentant les analyses, les pipelines, les évaluations et les visualisations.
- [`RAPPORT_ACADÉMIQUE___PROJET_DE_FIN_DE_MODULE.pdf`](./RAPPORT_ACAD%C3%89MIQUE___PROJET_DE_FIN_DE_MODULE.pdf) — rapport académique du projet.

## Travaux réalisés

### Classification de données tabulaires : Titanic

- Exploration et analyse des variables.
- Prétraitement des variables numériques et catégorielles et ingénierie des caractéristiques.
- Comparaison de modèles de classification avec validation croisée stratifiée.
- Recherche d’hyperparamètres pour une forêt aléatoire et évaluation sur un jeu de test.

Le jeu de données Titanic est chargé depuis le dépôt public [datasciencedojo/datasets](https://github.com/datasciencedojo/datasets).

### Classification de textes : 20 Newsgroups

- Classification de messages appartenant aux catégories `sci.med`, `sci.space`, `rec.sport.baseball` et `talk.politics.guns`.
- Comparaison des représentations Count, TF-IDF (unigrammes et bigrammes) et Hashing.
- Évaluation de pipelines utilisant notamment Naive Bayes, la régression logistique et LinearSVC.
- Analyse des performances et des termes les plus discriminants.

Le corpus est chargé avec `fetch_20newsgroups` de scikit-learn. Le notebook prévoit également un corpus synthétique illustratif si le jeu de données n’est pas accessible.

## Exécution

Python 3 et Jupyter sont nécessaires. Depuis la racine du dépôt, installez les bibliothèques utilisées par le notebook :

```bash
python -m pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Puis lancez Jupyter et ouvrez le notebook :

```bash
jupyter notebook Projet_EMSI_2025_2026.ipynb
```

L’accès à Internet est nécessaire au premier chargement des jeux de données distants.
