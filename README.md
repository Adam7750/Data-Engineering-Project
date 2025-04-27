# Projet : Knowledge Graph pour la Médecine Reproductive

## 📚 Description

Ce projet consiste à nettoyer, prétraiter et modéliser des fichiers JSON liés à la médecine reproductive sous forme de graphe de connaissances en utilisant Neo4j.

## 📂 Contenu du dépôt

- `notebooks/` : Jupyter Notebook contenant le nettoyage des données et la création du graphe.
- `queries/` : Fichier avec les principales requêtes Cypher utilisées.
- `README.md` : Ce fichier de documentation.

## 🛠️ Technologies utilisées

- Python (pandas, json)
- Jupyter Notebook
- Neo4j (Community Edition)
- Cypher (langage de requêtes pour Neo4j)

## 🗂️ Structure du dataset

Les fichiers JSON contiennent des informations sur :
- Les articles de recherche
- Les auteurs
- Les institutions
- Les mots-clés associés aux articles

## 🧹 Étapes principales

1. Chargement et nettoyage des fichiers JSON
2. Prétraitement pour extraction des entités (articles, auteurs, institutions, mots-clés)
3. Construction du Knowledge Graph dans Neo4j
4. Exécution de requêtes Cypher pour l'analyse

## 🚀 Lancer le projet

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/Adam7750/Data-Engineering-Project.git
   cd Data-Engineering-Project
