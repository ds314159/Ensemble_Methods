# 🔄 Ensemble Methods Final Project

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

## 📋 Description du projet

Ce projet explore l'utilisation de méthodes d'ensemble en apprentissage automatique, sur une varieté de datasets dont des très déséquilibrés. Il comprend une analyse détaillée, du code expérimental et des résultats visualisés.

## 📁 Structure du projet

### 📊 Rapport
- `rapport.html` - Format recommandé pour une lecture confortable
 > Nécessite le dossier /graphiques pour un affichage correct
- `rapport.pdf` - Version portable du rapport

### 💻 Code source
- `Tools.py` - Fonctions utilitaires implémentées pour le projet
- `Steps_and_Results.ipynb` - Notebook Jupyter détaillant:
   - Prétraitement des données
   - Protocole expérimental
   - Analyses des résultats

### 📈 Résultats
- Fichiers `.pkl` contenant les données expérimentales
> Note: `global_models.pkl` non inclus (taille excessive). Disponible sur demande.

### 📚 Ressources
- `/graphiques` - Visualisations générées pour le rapport
- `/datasets` - Jeux de données utilisés dans l'étude

## 🚀 Installation et utilisation

```bash
# Cloner le repositoire
git clone https://github.com/ds314159/ensemble_methods_final.git

# Accéder au projet
cd ensemble_methods_final

# Lancer le notebook
jupyter notebook Steps_and_Results.ipynb
