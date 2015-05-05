# node-grunt

Projet de test grunt avec node

## install

### Global dependencies

Les dépendances qui ne dépendent pas du projet

node.js >= 0.8.0
grunt-cli 0.4.X

Installion :

installer node.js à dl sur le site de node
installer le client en ligne de commande

> npm install grunt-cli

### Project dependencies

Les dépendances dépendant du projet à installer à la racine du projet.

grunt.js 0.4.X
grunt-contrib-clean 0.6.X
grunt-contrib-concat 0.5.X
grunt-contrib-uglify 0.5.X
grunt-contrib-cssmin 0.12.X
grunt-contrib-copy 0.8.X

Installation à la racine du project :

Créer un package.json et Gruntfile.js
installer grunt

> npm install grunt


installer grunt-contrib-clean 

> npm install grunt-contrib-clean --save-dev

installer grunt-contrib-concat

>npm install grunt-contrib-concat --save-dev

installer grunt-contrib-uglify

> npm install grunt-contrib-uglify --save-dev

installer grunt-contrib-cssmin

> npm install grunt-contrib-cssmin --save-dev

installer grunt-processhtml

> npm install grunt-processhtml --save-dev

**Ne pas commiter** ces fichiers, seuls les fichiers package.json et Gruntfile sont à commiter

## run tasks

### Task global :

en dev mode

> grunt build_dev

en prod mode

> grunt build_prod

### Lancer les task unitairement

Supprimer les fichiers du repertoire build

> grunt clean

Concatener les fichiers js

> grunt concat:js

Concatener les fichiers css

> grunt concat:css

Minifier les fichiers js

> dev mode : grunt uglify:build_dev
> prod mode : grunt uglify:build_prod

Minifier les fichiers css

> grunt cssmin

Construire les ressources statiques à partir de template

> grunt htmlbuild





