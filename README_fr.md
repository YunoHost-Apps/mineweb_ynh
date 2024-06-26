<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# MineWeb pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/mineweb.svg)](https://dash.yunohost.org/appci/app/mineweb) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/mineweb.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/mineweb.maintain.svg)

[![Installer MineWeb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mineweb)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer MineWeb rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

MineWeb est un CMS (c'est-à-dire un système de gestion de contenu), en plus simple, un site complètement personnalisable et intuitif, qui s'adaptera parfaitement à vos serveurs Minecraft !

Vous pourrez tenir vos joueurs au courant des actualités, leur faire acheter des articles sur la boutique... Vous pourrez personnaliser le CMS avec toutes sortes de thèmes ou plugins ! Ceux-ci sont disponibles sur le market ou peuvent être développés par vous-même.


**Version incluse :** 1.15.2~ynh2

## Captures d’écran

![Capture d’écran de MineWeb](./doc/screenshots/features1_mb.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://mineweb.org/>
- Documentation officielle de l’admin : <https://docs.mineweb.org/>
- Dépôt de code officiel de l’app : <https://github.com/MineWeb/MineWebCMS/>
- YunoHost Store : <https://apps.yunohost.org/app/mineweb>
- Signaler un bug : <https://github.com/YunoHost-Apps/mineweb_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mineweb -u https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
