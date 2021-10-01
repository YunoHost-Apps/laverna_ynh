# Laverna pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/laverna.svg)](https://dash.yunohost.org/appci/app/laverna) ![](https://ci-apps.yunohost.org/ci/badges/laverna.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/laverna.maintain.svg)  
[![Installer Laverna avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=laverna)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Laverna rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Laverna est un système anonyme, crypté et sans inscription requise, il est accessible via un navigateur web (sans installation de logiciel).
Les données sont privées, car stockées par défaut sur votre machine (InnoDB et localstorage), c’est un réglage dans les paramètres qui vous permettra de les synchroniser via le cloud sur vos différents périphériques.


**Version incluse :** 0.7.51~ynh5

**Démo :** https://laverna.cc/app/

## Captures d'écran

![](./doc/screenshots/laverna.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : https://laverna.cc/index.html
* Documentation officielle de l'admin : https://github.com/Laverna/laverna/wiki
* Dépôt de code officiel de l'app : https://github.com/Laverna/laverna
* Documentation YunoHost pour cette app : https://yunohost.org/app_laverna
* Signaler un bug : https://github.com/YunoHost-Apps/laverna_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/laverna_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
ou
sudo yunohost app upgrade laverna -u https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps