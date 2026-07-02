# Projet_nlp

🧠 Analyse des émotions dans des textes – NLP, Deep Learning & Elasticsearch

📖 Présentation

Ce projet a été réalisé dans le cadre de ma formation en Data & Intelligence Artificielle.

L’objectif est de construire une application capable d’analyser automatiquement les émotions présentes dans un texte grâce aux techniques de Natural Language Processing (NLP) et de Deep Learning.

Le projet couvre l’ensemble de la chaîne de traitement :

* exploration et préparation des données ;
* analyse statistique des émotions ;
* prétraitement du texte ;
* expérimentation avec un modèle Transformer (DistilBERT) ;
* indexation et recherche des données avec Elasticsearch ;
* intégration dans une application Django.

⸻

🎯 Objectifs

* Comprendre la répartition des émotions dans un jeu de données textuel.
* Nettoyer et préparer les données textuelles.
* Identifier les mots les plus représentatifs de chaque émotion.
* Comparer les émotions grâce à des mesures de similarité.
* Tester un modèle de Deep Learning basé sur DistilBERT.
* Stocker et rechercher les données avec Elasticsearch.
* Préparer le déploiement de l’application avec Django.

⸻

🛠 Technologies utilisées

* Python
* Pandas
* NumPy
* NLTK
* Matplotlib
* Seaborn
* Scikit-learn
* Hugging Face Transformers
* PyTorch
* Elasticsearch
* Django
* Faker

⸻

📊 Analyse exploratoire

Le projet débute par une analyse du jeu de données afin de :

* observer la distribution des émotions ;
* visualiser les données ;
* identifier les classes majoritaires et minoritaires ;
* comprendre la composition du dataset.

Une analyse des mots les plus fréquents est ensuite réalisée pour chaque émotion après suppression des stopwords.

⸻

🧹 Prétraitement NLP

Les principales étapes sont :

* suppression des stopwords ;
* tokenisation ;
* calcul des fréquences de mots ;
* comparaison des émotions ;
* calcul de similarités entre émotions.

⸻

🤖 Modélisation

Une seconde partie du projet expérimente un modèle basé sur DistilBERT grâce à la bibliothèque Hugging Face.

Les textes sont :

* encodés avec le tokenizer DistilBERT ;
* séparés en ensembles d’entraînement et de test ;
* convertis en Dataset PyTorch afin de préparer l’entraînement du modèle.

⸻

🔍 Elasticsearch

Le projet utilise également Elasticsearch afin de :

* créer un index personnalisé ;
* définir un mapping ;
* importer les données ;
* effectuer des recherches textuelles ;
* analyser les émotions associées aux documents indexés.

⸻

🌐 Interface Django

Une structure Django est présente afin de préparer l’intégration du modèle NLP dans une application web.

Cette architecture permet de connecter les traitements de Machine Learning à une interface utilisateur.

⸻

📚 Compétences mises en œuvre

* Analyse de données
* Data Visualisation
* Natural Language Processing
* Machine Learning
* Deep Learning
* Transformers
* Elasticsearch
* Développement Django
* Python

⸻

🔮 Perspectives d’amélioration

* Optimiser les performances du modèle.
* Ajouter plusieurs modèles NLP pour comparaison.
* Déployer l’application.
* Ajouter une interface utilisateur plus complète.
* Mettre en production le modèle sous forme d’API.

⸻

👤 Auteur

Dylan Vanstavel

Projet réalisé dans le cadre de ma formation en Data & Intelligence Artificielle.
