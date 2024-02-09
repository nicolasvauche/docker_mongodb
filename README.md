# Docker & MongoDB + Mongo Express

Installation d'un environnement MongoDB avec Mongo Express.

## Installation

1. **Cloner le dépôt :**

    ```bash
    cd [YOUR_WORKING_DIRECTORY]
    git clone https://github.com/nicolasvauche/docker_mongodb.git
    ```


2. **Créer le fichier `.env` :**

    ```bash
    cd docker_mongodb
    cp .env.example .env
    ```

   Modifier les variables d'environnement si besoin.


3. **Monter les conteneurs Docker :**

    ```bash
    docker-compose up -d --build
    ```

   Les conteneurs sont montés et les services sont accessibles.

## Utilisation

- MongoDB Host : `127.0.0.1:27017`
- Mongo Express : http://127.0.0.1:8081
