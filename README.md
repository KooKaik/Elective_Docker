# Elective Docker

## Serveur Minecraft

### ¤ Serveur

Le serveur minecraft fonctionne en version 1.16.5 avec Forge.
Pour démarrer notre serveur minecraft, il faut:
  - S'assurer que docker et docker-compose soient bien installés
  - Lancer une fenêtre PowerShell
  - Se rendre à la racine du projet
  - Lancer la commande **docker-compose up**

<br/>

### ¤ Forge (Mods)

La gestion des mods fonctionne avec Forge.
Pour le bon fonctionnement, il faut donc s'assurer d'utiliser un client minecraft comptatible avec Forge

Pour installer un mod dans notre serveur, il faut:
  - S'assurer que le mod est comptatible avec la version de minecraft
  - Se rendre dans le dossier /minecraft-data/mods
  - Glisser le mod (.jar) à l'intérieur
  - Redemarrer le serveur s'il était deja actif

**ATTENTION:** Pour qu'un mod fonctionne correctement, il doit être installé coté serveur mais aussi coté client !
Pour cela, il faut de rendre dans %appdata%/.minecraft/mods et glisser le mod (.jar) à l'intérieur du dossier.

*Par défaut, le mod Twilight Forest est installé*

<br/>

### ¤ Bukkit (Plugins)

Pour installer un plugin dans notre serveur, il faut:
  - S'assurer que le plugin est comptatible avec la version de minecraft
  - Se rendre dans le dossier /minecraft-data/plugins
  - Glisser le plugin (.jar) à l'intérieur
  - Redemarrer le serveur s'il était deja actif

Contrairement au mods, aucune modification n'a besoin d'être apporté coté client pour que cela fonctionne

*Par défaut, le plugin WorldEdit est déjà installé*

<br/>

## Accès via VPN

Le serveur n'étant pas hébergé en ligne, devait trouver un moyen pour simuler un réseau local.
Pour cela de nombreuses solutions de VPN all in one existent.
Elles nous permettent de créer un réseau et à nos amis, de les rejoindre, le tout en nous fournissant une ip public afin que nos amis puissent rejoindre le serveur.

Exemple de VPN all in one :
- RadminVPN
- Hamachi

Nous avons faut de nombreux tests sur le VPN OpenVPN afin d'être autonome sur notre VPN et ainsi créé notre propre certificat d'authentification pour rendre le réseau plus sécurisé.
Malheureusement, après de nombreuses tentatives sur plusieurs plateformes différentes (Docker, Windows Serveur, Linux) nous n'avons pu aboutir à des résultats concluant.

**ATTENTION:** Il est nécessaire d'installer le VPN coté client ET serveur pour pouvoir se connecter au serveur.



<br/>

## Site Web WordPress

### ¤ WordPress

Il est possible de configurer un site web afin de promouvoir le serveur pour qu'il soit accessible depuis le WAN.
Le CMS WordPress permet de créer un site web de A à Z de en quelques clics grâce aux nombreuses templates pré-configurées qui sont disponibles.

Sur ces templates il nous suffit juste de modifier les éléments désirés.


Nous avons mis au point un site permettant aux joueurs du serveur d'être tenus au courant des nouveautés sur le serveur, mais aussi de passer des achat sur la boutique.

<br/>

### ¤ Base de Données MySQL

Le site web nécessite une base de données fonctionnelle.

Pour cela nous avons choisi de mettre en place une base de données MySQL qui est déjà préconfiguré pour fonctionner avec WordPress dés le 1er lancement

<br/>
