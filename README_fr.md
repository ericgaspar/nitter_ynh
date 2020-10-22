# Nitter pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/codimd.svg)](https://dash.yunohost.org/appci/app/codimd) ![](https://ci-apps.yunohost.org/ci/badges/codimd.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/codimd.maintain.svg)  
[![Installer Nitter avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=codimd)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Nitter rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
CodiMD est un service web de traitement de texte collaboratif en temps réel. Il utilise le langage Markdown.

**Version incluse :** 1.6.0

## Captures d'écran

![](https://demo.codimd.org/screenshot.png)

## Démo

* [Démo officielle](https://demo.codimd.org/)

## Configuration

Vous pouvez configurer CodiMD en modifiant le fichier `/var/www/codimd/config.json` et en vous aidant de la [documentation](https://github.com/codimd/server/blob/master/docs/configuration.md)

## Documentation

 * Documentation officielle : 
 * Documentation YunoHost : https://yunohost.org/#/app_nitter_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/nitter%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/nitter/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/nitter%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/nitter/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/nitter_ynh/issues
 https://nitter.net/
 * Dépôt de l'application principale : https://github.com/zedeus/nitter
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/nitter_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/nitter_ynh/tree/testing --debug
ou
sudo yunohost app upgrade nitter -u https://github.com/YunoHost-Apps/nitter_ynh/tree/testing --debug
```
