# Groupomania

> Créez un réseau social d’entreprise.

Dans le cadre de la
[formation de Développeur Web](https://openclassrooms.com/fr/paths/185-developpeur-web)
proposée par [OpenClassRooms](https://openclassrooms.com/),
ce dépôt met à disposition les livrables qui seront mis en avant
lors de la soutenance du projet n°7.

## Utilisation

> Note: Vous pouvez remplacer `yarn` par `npm`.

- Clonez le dépôt avec ses sous-modules "backend" et "frontend"

  ```bash
  git clone --recurse-submodules https://github.com/freddy38510/FreddyEscobar_7_25012021.git && cd FreddyEscobar_7_25012021
  ```

- Depuis le dossier backend, installer les dépendances, puis faites les migrations vers la base de données configurée à l'aide du fichier `src/config/knexConfig.js`

  ```bash
  cd backend

  yarn

  yarn knex:prod
  ```

  Enfin, lancez le serveur

  ```bash
  yarn start
  ```

  L'api du backend écoute maintenant les requêtes entrantes
  à l'adresse suivante [http://localhost:3000](http://localhost:3000).

- Depuis le dossier frontend, installer les dépendances, construisez l'application puis lancez le serveur

  ```bash
  cd frontend

  yarn

  yarn build

  yarn serve
  ```

  L'application est maintenant disponible
  à l'adresse suivante [http://localhost:4000](http://localhost:4000).
