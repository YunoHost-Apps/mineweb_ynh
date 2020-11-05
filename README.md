# MineWeb for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mineweb.svg)](https://dash.yunohost.org/appci/app/mineweb) ![](https://ci-apps.yunohost.org/ci/badges/mineweb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mineweb.maintain.svg)  
[![Install MineWeb with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mineweb)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install MineWeb quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
MineWeb est un CMS (c'est-à-dire un système de gestion de contenu), en plus simple, un site complètement personnalisable et intuitif, qui s'adaptera parfaitement à vos serveurs Minecraft !

**Shipped version:** 1.10.3

## Screenshots

![](https://mineweb.org/assets/img/features1_mb.png)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://docs.mineweb.org/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported?
 * Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mineweb%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mineweb/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/minewebP%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mineweb/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/mineweb_ynh/issues
 * App website: https://mineweb.org/
 * Upstream app repository: https://github.com/MineWeb/MineWebCMS/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
or
sudo yunohost app upgrade mineweb -u https://github.com/YunoHost-Apps/mineweb_ynh/tree/testing --debug
```
