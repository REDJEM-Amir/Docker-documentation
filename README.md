# Documentation Docker

Ce projet GitHub fournit une documentation Docker concise et conviviale visant à simplifier la gestion et le déploiement des conteneurs.

## Installation Docker (Ubuntu)
Consultez la documentation officielle pour installer Docker sur Ubuntu :
[Installation Docker sur Ubuntu](https://docs.docker.com/engine/install/ubuntu/)

## Commandes de Base

| Action               | Commande                    |
|----------------------|-----------------------------|
| Démarrer Docker      | `sudo service docker start` |
| Arrêter Docker       | `sudo service docker stop`  |
| Afficher les Conteneurs Actifs | `docker ps`          |
| Afficher les Journaux des Conteneurs | `docker logs [idConteneur]` |

## Nettoyage de la Machine

| Action               | Commande                                        |
|----------------------|-------------------------------------------------|
| Arrêter tous les Conteneurs | `docker stop $(docker ps -aq)`       |
| Supprimer tous les Conteneurs | `docker rm $(docker ps -aq)`         |
| Supprimer toutes les Images | `docker rmi $(docker images -q)`      |
| Supprimer tous les Volumes | `docker volume rm $(docker volume ls -q)` |
| Supprimer tous les Réseaux | `docker network rm $(docker network ls -q)` |
