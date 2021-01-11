# PluXml for YunoHost

[![Integration level](https://dash.yunohost.org/integration/pluxml.svg)](https://dash.yunohost.org/appci/app/pluxml) ![](https://ci-apps.yunohost.org/ci/badges/pluxml.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pluxml.maintain.svg)  
[![Install PluXml with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=pluxml)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PluXml quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
PluXml is a content management system (CMS) developed in PHP. The data is stored in XML files. It is therefore not necessary to have the database management system. PluXml is customizable through themes and/or plugins.

**Shipped version:** 5.8.5

## Screenshots

![Screenshot_Pluxml](sources/images/screenshot.png)

## Demo

* [Official demo](https://demo.pluxml.org/)

## Configuration

The admin panel is in https://domain.tld/path/core/admin

## Documentation

 * Official documentation: https://wiki.pluxml.org/
 * YunoHost documentation: https://yunohost.org/#/app_pluxml

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? **No**  
Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/pluxml%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/pluxml/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/pluxml%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/pluxml/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

## Links

 * Report a bug: https://github.com/YunoHost-Apps/pluxml_ynh/issues
 * App website: https://www.pluxml.org/
 * Upstream app repository: https://github.com/pluxml/PluXml
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing --debug
or
sudo yunohost app upgrade pluxml -u https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing --debug
```
