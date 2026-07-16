# Data_Warehouse_et_Analytics
# Mis en place d'un Data Warehouse et analyse de donnees 

Bienvenue à ce projet qui a pour but de mettre en place un Data Warehouse permettant d'intégrer les données venues de plusieurs sources, et enfin construire une source de données fiable pour les data analystes et les data scientists.

\---

## 🏗️ Architecture de données utitilsé

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
!\[Data Architecture](docs/data\_architecture.png)

1. La Partie **BRONZE**: On Stocke les données brutes sans les modifier. Les données sont ingérées à partir de fichiers excel dans la base de données SQL Server.

2. La Partie **SILVER**: c'est ici que nous allons stocker les données transformées, nettoyées, normalisées et prêtes pour l'analyse 

3. La Partie **GOLD**: Nous Stockons les données prêtes à l'emploi modélisées en un schéma en étoile requis pour le reporting et l’analyse.

\---

## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics \& Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

* SQL Development
* Data Architect
* Data Engineering
* ETL Pipeline Developer
* Data Modeling
* Data Analytics

\---
