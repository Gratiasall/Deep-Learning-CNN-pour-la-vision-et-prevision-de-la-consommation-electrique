🎯 ***Objectif du repo***

Ce repository rassemble cinq notebooks structurés autour de deux axes complémentaires du machine learning :

**Vision par ordinateur :** conception et entraînement de réseaux de neurones convolutifs (CNN) pour la classification d’images, avec une mise en œuvre moderne en PyTorch Lightning, suivi des métriques, exploration des canaux, convolutions et pooling.

**Séries temporelles :** prévision de la consommation électrique à partir de données calendaires et historiques, incluant prétraitement, agrégations, visualisations, features temporelles et évaluation des performances.

Le dépôt contient à la fois les énoncés (TP_2_2_énoncé, TP_2_3_énoncé) et les solutions (TP_2_2_solution, TP_2_3_solution), ainsi qu’un notebook d’introduction aux CNN (TP_2_1) qui pose les bases théoriques et pratiques (convolutions, noyaux/filtre, pooling, canaux).

📂 ***Contenu***

**TP_2_1.ipynb** — Introduction aux réseaux de neurones convolutifs
Bases : canaux (channels), noyaux de convolution, couches de pooling, intuition des filtres (rehaussement de contours, lissage…), premières visualisations.

**TP_2_2_énoncé.ipynb** — Classification d’images par réseau de neurones convolutif (énoncé)
Cahier des charges guidé : préparation des données, architecture CNN, entraînement, suivi des métriques et visualisations.

**TP_2_2_solution.ipynb** — Classification d’images par réseau de neurones convolutif (solution)
Implémentation complète avec PyTorch Lightning, utilisation de torchmetrics pour l’évaluation et torchinfo pour le résumé de modèle, tracés des courbes d’apprentissage.

**TP_2_3_énoncé.ipynb** — Prévision de la future consommation électrique (énoncé)
Énoncé structuré : lecture et resampling des données, création de variables temporelles, séparation temporelle train/val/test, définition des objectifs de prévision, visualisations.

**TP_2_3_solution.ipynb** — Prévision de la future consommation électrique (solution)
Pipeline complet : pandas pour l’ingénierie des features (ex. agrégations journalières, gestion de colonnes comme Holiday_ID, variables calendaires), visualisations matplotlib, préparation des jeux temporels et évaluation.

🧰 ***Stack & bibliothèques***

- Python 3 (Jupyter Notebooks)

- PyTorch & PyTorch Lightning (entraînement structuré, boucles propres)

- torchmetrics (suivi des performances)

- torchinfo (résumé de l’architecture)

- pandas, numpy (prétraitement, time series)

- matplotlib (visualisations)

📊 ***Résultats & insights*** 

**CNN :** amélioration progressive de l’accuracy au fil des époques, impact des hyperparamètres (nombre de filtres, taille des kernels, learning rate), diagnostic via courbes.

**Time series :** importance des features calendaires (jour/semaine/mois/jours fériés), stabilité de la tendance vs. variabilité intra-semaine, rôle du resampling.