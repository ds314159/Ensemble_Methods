# Ensemble Methods Final Project

## Description du projet
Ce projet explore l'utilisation de méthodes d'ensemble en apprentissage automatique, sur une varieté de datasets dont des très déséquilibrés. Il comprend une analyse détaillée, du code expérimental et des résultats visualisés.

## Structure du projet
- **Rapport**
  - `rapport.html` (recommandé pour une lecture confortable)
  - `rapport.pdf`

- **Code**
  - `Tools.py`: Fonctions utilitaires implémentées pour le projet
  - `Steps_and_Results.ipynb`: Notebook Jupyter détaillant le prétraitement des données et les étapes du protocole expérimental

  - Résultats
    - Fichiers `.pkl` contenant les résultats des expériences
    - Note : `global_models.pkl` n'est pas inclus en raison de sa taille. Disponible sur demande.

  - Ressources
    - `/graphiques`: Dossier contenant les graphiques générés
    - `/datasets`: Dossier contenant les jeux de données utilisés

## Installation et utilisation

Vous pouvez simplement télécharger le projet, ou :
```bash
git clone https://github.com/ds314159/ensemble_methods_final.git
cd ensemble_methods_final
jupyter notebook Steps_and_Results.ipynb
