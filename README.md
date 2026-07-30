# Data_Warehouse_et_Analytics
# Mis en place d'un Data Warehouse et analyse de donnees 

Bienvenue à ce projet qui a pour but de mettre en place un Data Warehouse permettant d'intégrer les données venues de plusieurs sources, et enfin construire une source de données fiable pour les data analystes et les data scientists.

\---

## 🏗️ Architecture de données utitilsé

vue globale de l'architecture en medaillon
!\[Data Architecture](img/DWH.png)

1. La Partie **BRONZE**: On Stocke les données brutes sans les modifier. Les données sont ingérées à partir de fichiers excel dans la base de données SQL Server.

2. La Partie **SILVER**: c'est ici que nous allons stocker les données transformées, nettoyées, normalisées et prêtes pour l'analyse 

3. La Partie **GOLD**: Nous Stockons les données prêtes à l'emploi modélisées en un schéma en étoile requis pour le reporting et l’analyse.

\---

## 📖 Notion abordées dans ce projet 

1. **Architecture de Données** : garantir une gouvernance robuste, une traçabilité complète et une scalabilité 
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: creation du schemas en etoile pour une meilleur performance en data analyste.
4. **Analytics \& Reporting**: analyse de donnees avec Sql et production de rapport avec PowerBI


