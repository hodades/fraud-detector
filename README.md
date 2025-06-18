# Banking Fraud Detection Powered by AI – Une Solution Smart et Agile :


##  Objectif du Projet
Développer un système de détection automatique de fraudes sur des transactions bancaires, en combinant des techniques de machine learning, de réduction de dimensionnalité et de rééchantillonnage afin d’optimiser la précision sur un jeu de données fortement déséquilibré.

##  Technologies Utilisées
- Python
- Scikit-learn
- Pandas, NumPy
- SMOTE & Random Undersampling
- PCA (Analyse en Composantes Principales)
- Flask (API REST)
- Streamlit (Interface Web)
- Google Colab & VS Code


## 🔍 Démarche et Étapes Clés
1. **Exploration des données** : analyse du dataset, visualisation des déséquilibres de classes, et premiers nettoyages.
2. **Prétraitement** : normalisation, transformation de la variable temporelle, encodage si nécessaire.
3. **Réduction de dimensionnalité** : application de la PCA pour faciliter la visualisation et réduire la complexité.
4. **Traitement du déséquilibre** : combinaison de SMOTE pour augmenter les fraudes et d’undersampling pour réduire les transactions normales.
5. **Modélisation** : test de plusieurs modèles (Régression Logistique, Arbre de Décision, Random Forest) et sélection du modèle optimal selon le Recall et la précision.
6. **Déploiement** : création d’une API avec Flask et d’une interface web intuitive avec Streamlit pour tester des transactions en direct.

## Résultats
Le modèle final atteint un bon compromis entre détection des fraudes (Recall) et limitation des faux positifs (Precision), grâce à l'équilibrage des classes et à la bonne sélection des variables explicatives. Il est prêt à être utilisé dans un environnement de production grâce à son intégration via Flask et Streamlit.

## 🚀 Lancement rapide
```bash
# Lancer l'API Flask
python app.py

