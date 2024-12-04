# TP-Bilan
# Déploiement d'Applications Web avec Docker

## Présentation

Ce projet offre une solution simple et rapide pour mettre en place plusieurs applications web à l'aide de Docker et Docker Compose. Le fichier `docker-compose.yml` est utilisé pour configurer et orchestrer les différents services.

## Conditions nécessaires

- Une plateforme de virtualisation fonctionnelle, comme VirtualBox ou VMware.
- Une machine virtuelle sous Linux (distribution minimale recommandée : Debian ou Ubuntu).
- Docker et Docker Compose préalablement installés.

## Procédure d'installation

1. Télécharger le projet depuis un dépôt Git en ligne.
2. Accéder au dossier du projet.
3. Lancer le script de configuration pour installer Docker et préparer l'environnement.
4. Démarrer les services en utilisant Docker Compose.
5. Une fois les services démarrés, vous pouvez accéder aux applications web via leur URL respective :
   - **Application 1** : accessible à l'adresse IP locale sur le port 8000.
   - **Application 2** : accessible à l'adresse IP locale sur le port 8001.

## Organisation des fichiers

- **setup_docker.sh** : Script permettant d'automatiser la configuration de Docker.
- **docker-compose.yml** : Fichier de configuration Docker Compose pour orchestrer les différents services.
