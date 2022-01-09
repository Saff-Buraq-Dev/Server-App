# Server App


## Description
Sur cette application vous pouvez enregistrer une liste de serveurs et voir leur statut.
## Technologies utilisées

Cette application a été conçue en utilisant les technologies suivantes:

1. Backend:
- SpringBoot
- MySQL

1. Frontend:
- Angular

## Utilisation

1. Changez les informations de connexion à votre base de données `MySQL` [ici](Server-App-Backend/src/main/resources/application.yml).
2. Changez le chemin vers le dossier images [ici](Server-App-Backend/src/main/java/com/example/server/resource/ServerResource.java).
3. Démarrez l'application `Java` dans [Server-App-Backend](Server-App-Backend/src/main/java/com/example/server/ServerApplication.java).
4. Allez dans le répertoire `Server-App-Frontend` et tapez dans le terminal:
```sh
npm install
```
Et puis démarrez le serveur angular pour commencer à utiliser l'application:
```sh
ng serve -o
```