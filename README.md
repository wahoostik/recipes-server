# recipes-server

Lancer la commande yarn pour installer les dépendances nécessaires au fonctionnement du projet.
- install `yarn`

Lancer la commande yarn start pour lancer le projet. Le chat se lance sur le port 3200.
- start server `yarn start` : http://localhost:3001

Routes :
- `POST http://localhost:3001/login`

    => fournir un objet contenant email et password, par exemple 
    ```
    {
        email: 'rudy.gobert@nba.com',
        password: 'utahjazz'
    },
    {
        email: 'darksouls@fromsoftware.com',
        password: 'difficult'
    }
    ```

Identifiants :
    rudy.gobert@nba.com/utahjazz  -  darksouls@fromsoftware.com/difficult