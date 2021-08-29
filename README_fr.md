# MineWeb pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mineweb.svg)](https://dash.yunohost.org/appci/app/mineweb) ![](https://ci-apps.yunohost.org/ci/badges/mineweb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mineweb.maintain.svg)  
[![Installer MineWeb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mineweb)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer MineWeb rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

MineWeb est un CMS (c'est-à-dire un système de gestion de contenu), en plus simple, un site complètement personnalisable et intuitif, qui s'adaptera parfaitement à vos serveurs Minecraft !

Vous pourrez tenir vos joueurs au courant des actualités, leur faire acheter des articles sur la boutique... Vous pourrez personnaliser le CMS avec toutes sortes de thèmes ou plugins ! Ceux-ci sont disponibles sur le market ou peuvent être développés par vous-même.


**Version incluse :** 1.14.3~ynh1



## Captures d'écran

![](./doc/screenshots/features1_mb.png)

## Documentations et ressources

* Site officiel de l'app : https://mineweb.org/
* Documentation officielle de l'admin : https://docs.mineweb.org/
* Dépôt de code officiel de l'app : ttps://github.com/MineWeb/MineWebCMS/
* Documentation YunoHost pour cette app : https://yunohost.org/app_mineweb
* Signaler un bug : https://github.com/YunoHost-Apps/mineweb_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mineweb -u https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps