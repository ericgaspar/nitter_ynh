# Nitter for YunoHost

[![Integration level](https://dash.yunohost.org/integration/nitter.svg)](https://dash.yunohost.org/appci/app/nitter) ![](https://ci-apps.yunohost.org/ci/badges/nitter.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/nitter.maintain.svg)  
[![Install Nitter with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=nitter)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Nitter quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
A free and open source alternative Twitter front-end focused on privacy. Inspired by the Invidious project.

**Shipped version:** 1.6.0

## Screenshots

![](https://raw.githubusercontent.com/zedeus/nitter/master/screenshot.png)

## Demo

* [Official demo](https://nitter.net/)

## Configuration

You can configure CodiMD by editing this file `/var/www/codimd/config.json` using this the [documentation](https://github.com/codimd/server/blob/master/docs/configuration.md)

## Documentation

 * Official documentation: https://github.com/codimd/server/tree/master/docs/
 * YunoHost documentation: https://yunohost.org/#/app_nitter

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/nitter%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/nitter/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/nitter%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/nitter/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/nitter_ynh/issues
 * App website: https://nitter.net/
 * Upstream app repository: https://github.com/zedeus/nitter
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/nitter_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/nitter_ynh/tree/testing --debug
or
sudo yunohost app upgrade nitter -u https://github.com/YunoHost-Apps/nitter_ynh/tree/testing --debug
```
