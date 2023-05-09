
# BlueRockTEL API Admin (public)

Une collection de routes permettant de communiquer avec l'API BlueRockTEL. 

### Installation

- Installer le client [Insomnia](https://insomnia.rest/download)
- Une fois le client installé, cliquer sur "+ Create" en haut à droite de l'écran
- Choisir l'option "Git clone"
- Dans l'onglet GitHub, renseigner l'URL de ce repository : https://github.com/bluerocktel/bluerockteladmin-api-public.git
- Ouvrir la collection cloné, puis dans l'onglet "Debug", en haut à gauche, cliquer sur "No environment" puis "Manage environments"
- Dupliquer l'environnement BlueRockTEL Demo et ajuster les paramètres `base_url`, `email` et `password` (utiliser l'URL de votre instance, ainsi que vos identifiants)
- Selectionner l'environnement, puis tester la connexion en exécutant la requête `/login` située dans le dossier Auth