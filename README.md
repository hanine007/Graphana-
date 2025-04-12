# Monitoring avec Prometheus, Grafana et Node Exporter

Ce projet configure un environnement de surveillance pour collecter des métriques sur l'infrastructure à l'aide de **Prometheus**, **Grafana**, et **Node Exporter**.

## Prérequis

Avant de commencer, assurez-vous que vous avez les éléments suivants installés sur votre machine :


- **Docker** - [Télécharger Docker](https://www.docker.com/get-started)
- **Docker Compose** - [Télécharger Docker Compose](https://docs.docker.com/compose/install/)
## Architecture du Projet

- **Prometheus** : Sert à collecter et stocker les métriques des services.
- **Grafana** : Permet de visualiser les données collectées par Prometheus.
- **Node Exporter** : Collecte des métriques système (CPU, RAM, Disque, etc.) du système hôte.

## Lancer le Projet avec Docker Compose
```bash
docker compose up



