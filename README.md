# Elective_Docker

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

*Par défaut, le mod Twilight Forest*

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



## Site Web WordPress



### ¤ WordPress

Il est possible de configurer un site web afin de promouvoir le serveur.

Le CMS WordPress permettra de créer le site de A à Z de manière assez simple.

<br/>

### ¤ Base de Données MySQL

Un site web nécessite une base de données fonctionnelle.

Pour cela nous avons choisi de mettre en place une base de données MySQL qui est déjà préconfiguré pour fonctionner avec WordPress dés le 1er lancement

<br/>
