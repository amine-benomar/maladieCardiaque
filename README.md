# Prédiction des maladies cardiaques à l'aide de l'apprentissage automatique

## Aperçu du projet
Ce dépôt contient un projet d'apprentissage automatique visant à prédire les maladies cardiaques. En utilisant divers algorithmes d'apprentissage automatique et un ensemble de données contenant des dossiers de patients atteints de maladies cardiaques, ce projet cherche à identifier avec précision la présence d'une maladie cardiaque sur la base de paramètres cliniques.

## Dataset
L'ensemble de données utilisé dans ce projet contient plusieurs caractéristiques telles que l'âge, le sexe, le type de douleur thoracique, la pression artérielle au repos, le taux de cholestérol, la glycémie à jeun, etc. La source de l'ensemble de données est [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease) (ou spécifier une autre source si elle est différente).

## Features
- `age` : Âge du patient
- `sex` : Sexe du patient
- `cp` : Type de douleur thoracique
- `trestbps` : Pression artérielle au repos
- `chol` : Cholestérol sérique
- ... (liste des autres caractéristiques)
- `target` : Diagnostic des maladies cardiaques

## Installation
Instructions pour la mise en place de l'environnement du projet :
```bash
git clone https://github.com/[your-username]/heart-disease-ml.git
cd heart-disease-ml
pip install -r requirements.txt
