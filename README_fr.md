# PluXml pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/pluxml.svg)](https://dash.yunohost.org/appci/app/pluxml) ![](https://ci-apps.yunohost.org/ci/badges/pluxml.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pluxml.maintain.svg)   
[![Install PluXml with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=pluxml)


*[Read this readme in english.](./README.md)* 

![Logo_Pluxml](sources/images/PluXml-logo_transparent.png)

> *Ce package vous permet d'installer PluXml rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

[PluXml](https://www.pluxml.org/) : Blog ou CMS à l'Xml.

**Version incluse:** 5.7

## Captures d'écran

![Screenshot_Pluxml](sources/images/screenshot.jpg)

## Démo

* [Official demo](https://demo.pluxml.org/)

## Configuration

Le panneau d'administration est accessible via https://domain.tld/path/core/admin

## Documentation

 * Documentation officielle : https://wiki.pluxml.org/
 * Documentation YunoHost : https://yunohost.org/#/app_pluxml_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge ? **Non**  
L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/pluxml%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/pluxml/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/pluxml%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/pluxml/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

## Links

 * Signaler un bug sur pluxml_ynh : https://github.com/YunoHost-Apps/pluxml_ynh/issues
 * Signaler un bug sur PluXml : https://github.com/pluxml/PluXml/issues
 * Site de l'application : https://www.pluxml.org/
 * Site web YunoHost : https://yunohost.org/

---

Informations pour les développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pluxml_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pluxml -u https://github.com/YunoHost-Apps/pluxml_ynhtree/testing  --debug
```
