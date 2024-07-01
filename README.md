# Kafka Node.js Twitter Docker

Ce projet utilise Apache Kafka pour collecter des données en temps réel de Twitter à l'aide de Node.js et Docker. Il inclut la configuration pour un producteur Kafka qui lit les tweets en temps réel via l'API de streaming de Twitter et un consommateur Kafka qui lit les messages des topics Kafka.

## Prérequis

- Docker et Docker Compose installés
- Clés API Twitter (Consumer Key, Consumer Secret, Access Token, Access Token Secret)

## Configuration

### 1. Cloner le dépôt

```bash
git clone https://github.com/ridha-boughediri/apache-kafka.git
cd apache-kafka

2. Créer un fichier .env
Créez un fichier .env à la racine du projet avec vos clés API Twitter :

CONSUMER_KEY=your_consumer_key
CONSUMER_SECRET=your_consumer_secret
ACCESS_TOKEN_KEY=your_access_token_key
ACCESS_TOKEN_SECRET=your_access_token_secret


