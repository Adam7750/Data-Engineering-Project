# Documentation du Projet : Knowledge Graph pour la Médecine Reproductive

## Description du Projet
Ce projet consiste à créer un graphe de connaissances à partir de données JSON liées à la médecine reproductive. Le processus inclut le nettoyage des données, la modélisation d'un graphe dans Neo4j, et l'exécution de requêtes Cypher pour analyser le graphe.

## Étapes du Projet

1. **Chargement et nettoyage des données** :
   - Chargement des fichiers JSON contenant des articles de recherche, auteurs, institutions et mots-clés.
   - Nettoyage et transformation des données pour qu'elles soient prêtes à être intégrées dans un graphe.

2. **Création du Knowledge Graph** :
   - Utilisation de Neo4j pour modéliser les entités (articles, auteurs, institutions) et leurs relations (auteur écrit un article, article appartient à une institution, etc.).

3. **Requêtes Cypher** :
   - Exécution de requêtes Cypher pour explorer et analyser les données dans le graphe.

## Technologies Utilisées
- **Python** (pandas, json)
- **Neo4j Community Edition**
- **Cypher** (pour interroger le graphe)
- **Jupyter Notebook** (pour l'analyse des données)

## Challenges Rencontrés
- Problèmes de qualité des données (valeurs manquantes, formats inconsistants).
- Défis dans la modélisation du graphe, surtout pour les relations complexes entre les entités.

## Outils et Ressources
- [Neo4j](https://neo4j.com/)
- [Jupyter Notebook](https://jupyter.org/)
