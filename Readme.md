# Mon Projet Docker Compose

Bienvenue dans mon projet Docker Compose ! Ce projet est une application full-stack utilisant Docker Compose pour l'orchestration des services.

## Instructions pour démarrer l'application en mode développement

1. Assurez-vous d'avoir Docker et Docker Compose installés sur votre machine.

2. Clonez le dépôt GitHub et placez vous à l'intérieur du répertoire :
```bash
git clone https://github.com/kjarret/docker-compose.git && cd docker-compose
```


3. Lancez les containers avec Docker Compose :
```bash
docker-compose -f docker-compose.dev.yml up --build
```


5. Accédez à l'application React :
Ouvrez votre navigateur et allez à http://localhost:3000

6. Profitez du hot reload :
Modifiez du texte dans le fichier local `/client/src/App.js` et observez les changements en temps réel dans votre navigateur.

## Structure du Projet

- Le dossier `client` contient l'application React.
- Le dossier `server` contient le serveur Node.js avec MongoDB.
- Le dossier `data` est utilisé pour persister les données de MongoDB.

## Contributions

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

## Auteur

Kenny JARRET
