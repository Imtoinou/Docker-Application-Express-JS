# Docker-Application-Express-JS

# TP2

Antoine Zachariades
Roy Sarkis

## 2 Compléter le Dockerfile afin de builder correctement l’application contenu dans src/

L'option est : `npm install --production`
L'option --production permet d'exclure les dépendances devDependencies de l'installation.
Cette option permet d'optimiser la tailles des images ainsi nous avons moins d'images.

## 3. A l’aide de la commande docker build, créer l’image ma_super_app

Build de l'image :  `docker build -t ma_super_app .`
![](https://i.imgur.com/3gygbTt.png)


## 4 Compléter le fichier docker-compose.yml

Avec la commande : `docker-compose up` nous lancons les conteneurs. 

![](https://i.imgur.com/hCCq86c.png)

Résultat `
![](https://i.imgur.com/UxV5bgC.png)


