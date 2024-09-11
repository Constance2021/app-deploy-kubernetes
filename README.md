
---

# Application ToDo List - Déploiement Kubernetes

Ce projet est une simple application web de gestion de tâches (ToDo List) déployée sur un cluster Kubernetes. Elle se compose de services frontend et backend, tous deux containerisés et orchestrés avec Kubernetes. L'application permet aux utilisateurs d'ajouter et de consulter des tâches.

## Composants

- **Frontend** : Une application simple en HTML/JavaScript pour afficher et ajouter des tâches.
- **Backend** : Une API Flask avec SQLite pour la gestion des tâches.
- **Kubernetes** : Manifests pour déployer l'application, les services (ClusterIP) et un Ingress pour l'accès externe.

## Fonctionnalités

- Ajouter et consulter les tâches.
- Déploiement basé sur Kubernetes avec routage via Ingress.
- API Flask côté backend avec une base de données SQLite persistante.

## Installation

1. Cloner le dépôt.
2. Déployer l'application à l'aide des manifests Kubernetes fournis :
   - `kubectl apply -f <fichiers_manifestes>`
3. Accéder à l'application via l'IP de l'Ingress.

## Technologies

- Flask (Python)
- SQLite
- Kubernetes
- Docker
