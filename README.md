# VeriTAI - Fake News Detection System

## Description

VeriTAI est une application web basée sur l'intelligence artificielle permettant de détecter automatiquement les fausses informations (Fake News) à partir d'un texte saisi par l'utilisateur.

Le projet combine les techniques de Traitement Automatique du Langage Naturel (NLP) et de Machine Learning afin de classifier les actualités comme réelles ou fausses.

---

## Fonctionnalités

- Détection automatique des Fake News
- Prétraitement et nettoyage du texte
- Vectorisation TF-IDF
- Prédiction en temps réel
- Interface Web intuitive
- API Flask pour les prédictions
- Modèle de Machine Learning entraîné sur un dataset d'actualités

---

## Technologies Utilisées

- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy
- NLTK
- HTML/CSS
- Bootstrap
- Joblib

---

## Structure du Projet

```text
veritai_app_real/
│
├── app.py
├── requirements.txt
├── README.md
│
├── model/
│   ├── model.pkl
│   └── vectorizer.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   └── images/
│
├── data/
│   └── dataset.csv
│
└── notebooks/
    └── fake_news_detection.ipynb
```

---

## Installation

### 1. Cloner le dépôt

```bash
git clone https://github.com/votre-utilisateur/veritai.git
cd veritai
```

### 2. Créer un environnement virtuel

```bash
python -m venv venv
```

### 3. Activer l'environnement

Sous Windows :

```bash
venv\Scripts\activate
```

Sous Linux/Mac :

```bash
source venv/bin/activate
```

### 4. Installer les dépendances

```bash
pip install -r requirements.txt
```

---

## Exécution

Lancer l'application :

```bash
python app.py
```

Puis ouvrir dans le navigateur :

```text
http://127.0.0.1:5000
```

---

## Pipeline de Machine Learning

### Prétraitement des données

- Conversion en minuscules
- Suppression de la ponctuation
- Suppression des caractères spéciaux
- Suppression des stopwords
- Tokenisation
- Stemming ou Lemmatisation

### Extraction des caractéristiques

- TF-IDF Vectorizer

### Modèles évalués

- Logistic Regression
- Random Forest
- Naive Bayes
- XGBoost
- Support Vector Machine (SVM)

### Métriques d'évaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Utilisation

1. Ouvrir l'application web.
2. Saisir un texte ou un article.
3. Cliquer sur le bouton de prédiction.
4. Consulter le résultat de classification.

Résultats possibles :

- Real News
- Fake News

---

## Objectifs du Projet

- Détecter automatiquement les fausses informations.
- Appliquer les techniques de NLP et de Machine Learning.
- Développer une application web basée sur l'intelligence artificielle.
- Sensibiliser à la lutte contre la désinformation.

---

## Équipe

Projet réalisé dans le cadre d'un projet académique.

- Rihab Laarabi
- Sara Azzam
- Meriem Cherkaoui
- Ibtisaam bellihy
- Membres de l'équipe VeriTAI

---

## Licence

Ce projet est destiné à des fins académiques et éducatives.
