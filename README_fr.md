# MineWeb pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/mineweb.svg)](https://dash.yunohost.org/appci/app/mineweb) ![](https://ci-apps.yunohost.org/ci/badges/mineweb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mineweb.maintain.svg)  
[![Installer MineWeb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mineweb)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer MineWeb rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
MineWeb est un CMS (c'est-à-dire un système de gestion de contenu), en plus simple, un site complètement personnalisable et intuitif, qui s'adaptera parfaitement à vos serveurs Minecraft !

**Version incluse :** 1.13.0

## Captures d'écran

![](https://mineweb.org/assets/img/features1_mb.png)

## Configuration

Comment configurer cette application : via le panneau d'administration

## Documentation

* Documentation officielle : https://docs.mineweb.org/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mineweb%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mineweb/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/minewebP%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mineweb/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/mineweb_ynh/issues
 * Site de l'application : https://mineweb.org/
 * Dépôt de l'application principale :  https://github.com/MineWeb/MineWebCMS/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mineweb -u https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
```
