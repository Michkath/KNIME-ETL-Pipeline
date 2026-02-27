# KNIME-ETL-Pipeline

Présentation du Projet
Ce projet consiste en la mise en place d'un pipeline ETL (Extract, Transform, Load) automatisé via KNIME. L'objectif est de collecter, nettoyer et structurer des données de veille concurrentielle pour faciliter l'analyse décisionnelle.

Fonctionnalités
Extraction : Récupération automatisée de données provenant de sources hétérogènes (APIs, fichiers CSV/Excel).

Transformation : Nettoyage des données, gestion des doublons, et normalisation des formats via des nœuds KNIME optimisés.

Chargement : Exportation des données structurées vers une base de données PostgreSQL pour exploitation BI.

Automatisation : Workflow conçu pour être exécuté de manière périodique afin de garantir la fraîcheur des données.

Stack Technique
Outil ETL : KNIME Analytics Platform.

Base de Données : PostgreSQL / SQL.

Format de données : JSON, CSV, XLSX.

Structure du Workflow
Le workflow KNIME est organisé en plusieurs sections logiques :

Data Ingestion : Connecteurs de fichiers et requêtes API.

Data Cleaning : Filtrage, renommage de colonnes et typage des données.

Business Logic : Calcul de KPIs et agrégations.

Data Output : Écriture dans la base de données cible.

Résultats
Réduction du temps de traitement manuel des données.

Fiabilisation de la collecte avec un taux d'erreur quasi nul.

Données prêtes à l'emploi pour des dashboards (Power BI / Tableau).
