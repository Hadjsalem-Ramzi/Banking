# DigitalBankingWeb

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# DigitalBankingAPI

Ce projet est une application backend développée avec Spring Boot pour la gestion des opérations bancaires numériques.

## Pré-requis

- **Java** : 17 ou plus
- **Maven** : 3.8.1 ou plus
- **Base de données** : PostgreSQL ou une autre base compatible

---

## Démarrage du serveur de développement

Pour démarrer le serveur de développement, exécutez la commande suivante dans le terminal :

`mvn spring-boot:run`

Le serveur sera disponible à l'adresse suivante : [http://localhost:8080/](http://localhost:8080/).

---

## Structure du projet

- **`src/main/java`** : Contient le code source Java, y compris les **contrôleurs**, **services**, **entités**, et **dépôts**.
- **`src/main/resources`** : Contient les fichiers de configuration tels que **application.yml** ou **application.properties**.

---

## Création de nouvelles classes ou composants

Pour générer de nouveaux composants, suivez ces étapes :

1. **Entité** : Créez une classe dans le package `entities`.
2. **Service** : Implémentez les services métier dans le package `services`.
3. **Contrôleur** : Ajoutez un contrôleur REST dans le package `controllers`.
4. **Dépôt** : Ajoutez un repository JPA dans le package `repositories`.

---

## Construction du projet

Pour compiler et construire le projet, exécutez :

`mvn clean install`

Les artefacts générés seront disponibles dans le répertoire `target/`.

---

## Lancement des tests unitaires

Pour exécuter les tests unitaires, utilisez :

`mvn test`

Les rapports des tests seront disponibles dans le dossier `target/surefire-reports`.

---

## Lancement des tests d'intégration

Pour exécuter des tests d'intégration spécifiques :

`mvn verify`

---

## Documentation de l'API

L'API est documentée avec **Swagger**. Après le démarrage du serveur, accédez à l'URL suivante pour consulter la documentation interactive :

[http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)


