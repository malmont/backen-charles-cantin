# PROJET Charles Cantin
Site vitrine Charles Cantin
<br/>
Ce document est un guide de déploiement et un manuel d'utilisation 
pour l'application TRT-CONSEIL dévéloppé dans le cadre de l'ECF d'entrainement ayant pour titre:
<br/>
**Développer la partie front-end d’une application web**
de l'école STUDI.
<br/>
Selon le cahier des charges l'application demandée devra être un site
 vitrine pour un photographe qui veut dévelloper son activité.
 <br/>
 ce site représente la partie back-end du projet.

------

# Fonctionnalités de l'application

1. ## Une page d’accueil :


* Charles aimerait qu’une image prenne toute la taille de l’écran.
* Le texte “Charles Cantin - Photographe” devra être centré verticalement et
horizontalement.

2. ## Une page galerie : 

* Ici, nous retrouverons les photographies que Charles souhaiterait mettre en valeur.
* Chaque image fera partie d’une catégorie (voir annexes en fin de document).
horizontalement.
* Un système de filtre dynamique doit permettre d’afficher les photos d’une catégorie en
particulier sans avoir à recharger la page.

3. ## Une page “tarifs et prestations” :
* Chaque prestation possède un titre, une petite description et un tarif (voir annexes en fin
de document).

4. ## Une page “contact” :
* Un formulaire fonctionnel doit permettre de le contacter. Vous pouvez utiliser un service
gratuit comme le plan starter de https://formspree.io/, ou profiter de netlify forms si vous choisissez cet hébergeur.

5. ## Fonctionnalités générales :
* Depuis chacune des pages, une barre de navigation devra être disponible avec le menu ainsi que les icônes Facebook et Instagram (pour un lien vers son profil sur les réseaux sociaux à l’avenir).

* Tout contenu devra être modifiable facilement par Charles à l’aide d’un CMS.
Pour qu’il puisse apprécier le rendu du site avant de pouvoir le personnaliser, vous pouvez récupérer les images sur Pixabay (https://pixabay.com/fr/).

------

# Tech Stack

**Client:** Css, Html, Bootstrap, react js, nodeJs

**Server:** Strapi,

**Sql:** MongoDb

------

# Installation de l'environement

## Les pré-requis 

### L'installation nécessite que les logiciels suivants soient déjà installés sur votre ordinateur :

* [Node.js](https://nodejs.org/en/) (ouvre une nouvelle fenêtre): seules les versions LTS sont supportées (v14 et v16). D'autres versions de Node.js peuvent ne pas être compatibles avec la dernière version de Strapi. La version 16.x est la plus recommandée par Strapi.
* npm [npm](https://docs.npmjs.com/cli/v6/commands/npm-install)(ouvre une nouvelle fenêtre)(v6 uniquement) ou fil (ouvre une nouvelle fenêtre)pour exécuter les scripts d'installation CLI.

###  Créer un nouveau projet avec Strapi:
Exécutez le script d'installation

```Terminal 
$ npx create-strapi-app@latest my-project --quickstart
$ cd my-project
$ npm run develop

```

Le panneau d'administration de Strapi s'exécute sur http://localhost:1337/admin (ouvre une nouvelle fenêtre). C'est là que vous passerez le plus clair de votre temps à créer et mettre à jour du contenu.

------

# 🚀 Démarrer avec Strapi

Strapi est livré avec une fonctionnalité complète [Command Line Interface](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html) (CLI) qui vous permet d'échafauder et de gérer votre projet en quelques secondes.

### `develop`

Démarrez votre application Strapi avec autoReload activé. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Démarrez votre application Strapi avec autoReload désactivé.[Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Créez votre panneau d'administration.[Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Déploiement

Strapi vous offre de nombreuses options de déploiement possibles pour votre projet. Trouvez celui qui vous convient sur le [section déploiement de la documentation](https://docs.strapi.io/developer-docs/latest/setup-deployment-guides/deployment.html).

## 📚 Apprendre encore plus

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://docs.strapi.io) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

N'hésitez pas à consulter le [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>



# Installation de  l'environnement GIT

Se connecter sur le serveur GITHUB et créer un repositories.

## Initialiser votre dépot et créer votre premier commit
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/NOA-FASHION/backend-charles-cantin.git

## Synchroniser le sur votre serveur GITHUB.
git push -u origin main

------

# Déploiement de l'application
Le déploiement à été effectué sur un serveur VPS Ubuntu, le choix du provider est Hostinger.

# Installation de l'environement

## Les pré-requis 

### L'installation nécessite que les logiciels suivants soient déjà installés sur votre ordinateur :

* [Node.js](https://nodejs.org/en/) (ouvre une nouvelle fenêtre): seules les versions LTS sont supportées (v14 et v16). D'autres versions de Node.js peuvent ne pas être compatibles avec la dernière version de Strapi. La version 16.x est la plus recommandée par Strapi.
* npm [npm](https://docs.npmjs.com/cli/v6/commands/npm-install)(ouvre une nouvelle fenêtre)(v6 uniquement) ou fil (ouvre une nouvelle fenêtre)pour exécuter les scripts d'installation CLI.
* installation de MongoDB

La description des procédures d'installation suivantes sont destinées à l'OS Linux Ubuntu, pour les autres systèmes 
d'exploitaions vous pouvez vous référez à la documentation officielle.


### Mise à jour des paquets d'installation
```Terminal 
$ sudo apt-get update && apt-get upgrade
```
### Installation de Node.js
```Terminal 
$ curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Installation de MongoDB
Strapi utilise MongoDB comme système de base de données par défaut. Sauf si vous avez décidé d'utiliser un autre système de base de données ou d'héberger la base de données MongoDB sur un autre serveur ou service (ce que nous recommandons fortement), vous devez installer MongoDB sur le serveur Ubuntu.

### Importez la clé publique :
```Terminal 
$ sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6
```
### Créez un fichier de liste :
```Terminal 
$ echo "deb [ arch=amd64,arm64 ] http://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list

```
### Rechargez la base de données de packages locales :
```Terminal 
$ sudo apt-get updat
```

### Installez les packages MongoDB : :
```Terminal 
$ sudo apt-get install -y mongodb-org

```

### Démarrez MongoDB :


```Terminal 
$ sudo service mongod start

```

## installez GIT
```Terminal 
$ sudo apt install git
```

## initialisez Git
```Terminal 
$ git config --global user.name "Your Name"
$ git config --global user.email "youremail@domain.com"
```
## Clonez votre projet :

```Terminal 
$ git clone https://github.com/malmont/backend-charle-cantin

```
# déploiement du projet

## Installez les dépendances :

```Terminal
$ cd backend-charle-cantin
$ npm install --production
```

## Installation de packages

### Installer PM2
Comme vous l'avez peut-être vu, si vous quittez le npm startscript ou quittez la connexion SSH, le processus Node.js est arrêté. C'est assez ennuyeux. De plus, nous voulons nous assurer que l'application sera automatiquement redémarrée si elle plante.

C'est là que PM2 , le gestionnaire de processus de facto pour Node.js , vient à la rescousse.

```Terminal
$ npm i pm2 -g
```
## Démarrez votre serveur Strapi :
```Terminal
$ pm2 start npm --name my-app -- run start
```

Votre API Strapi doit être accessible à l'URL suivante : http://yourIP:1337.

## Installez nginx

Votre application est maintenant opérationnelle sur le port 1337. Pour le rendre accessible sur le port web (80) vous devez installer un reverse proxy. nginx est le serveur HTTP et reverse proxy le plus connu.
```Terminal
$ sudo apt-get update
$ sudo apt-get install -y nginx
```

### configurez nginx
Ouvrez le fichier de configuration principal :
```Terminal
$ sudo nano /etc/nginx/sites-available/default
```

### Ensuite, remplacez le contenu de la location /directive par ce qui suit :

```Nano
proxy_pass http://localhost:1337;
proxy_http_version 1.1;
proxy_set_header Upgrade $http_upgrade;
proxy_set_header Connection 'upgrade';
proxy_set_header Host $host;
proxy_cache_bypass $http_upgrade;
```

### Redémarrez nginx :
```Terminal
$ sudo systemctl restart nginx
```


À ce stade, votre API Strapi devrait être accessible à l'URL suivante  http://yourIP.

# sécuriser le projet

il est maintenant temps de mettre en place un pare-feu. Un pare-feu est essentiel lors de la configuration du VPS pour limiter le trafic indésirable sortant ou entrant dans votre VPS. Installez ufw et configurez un pare-feu pour autoriser les opérations SSH en faisant .

## Installation du parefeu ufw
```Terminal
$ sudo apt install ufw -y
```
## configuration du parefeu

```Terminal
$ sudo ufw allow OpenSSH
$ sudo ufw allow 443
$ sudo ufw allow OpenSSH
$ sudo ufw enable -y 
```
## Installation du fail2ban

fail2ban est un logiciel qui se charge d'analyser les logs de divers services installés sur la machine, pour bannir automatiquement un hôte via iptables pour une durée déterminée, en cas d'échec après X tentatives.
C'est un élément essentiel pour sécuriser son système, et éviter des intrusions via brute-force.

```Terminal
$ sudo apt install fail2ban
```


