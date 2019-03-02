# PluXml package for Yunohost

[![Integration level](https://dash.yunohost.org/integration/pluxml.svg)](https://dash.yunohost.org/appci/app/pluxml)  
[![Install PluXml with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=pluxml)


*[Lire ce readme en français.](./README_fr.md)* 

![Logo_Pluxml](sources/images/PluXml-logo_transparent.png)

> *This package allow you to install PluXml quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

[PluXml](https://www.pluxml.org/) : Blog or CMS storing data in XML.

**Shipped version:** 5.7

## Screenshots

![Screenshot_Pluxml](sources/images/screenshot.jpg)

## Demo

* [Official demo](https://demo.pluxml.org/)

## Configuration

The admin panel is in https://domain.tld/path/core/admin

## Documentation

 * Official documentation: https://wiki.pluxml.org/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported? : no  
Can the app be used by multiple users? : yes

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/pluxml%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/pluxml/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/pluxml%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/pluxml/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/pluxml%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/pluxml/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**  

https://yunohost.org/packaging_apps

## Links

 * Report a bug about pluxml_ynh: https://github.com/YunoHost-Apps/pluxml_ynh/issues
 * Report a bug about PluXml: https://github.com/pluxml/PluXml/issues
 * App website: https://www.pluxml.org/
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://framagit.org/toitoinebzh/pluxml_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing --debug
or
sudo yunohost app upgrade pluxml -u https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing  --debug
```
