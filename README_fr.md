# `mygpo` (gPodder.net) pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mygpo.svg)](https://dash.yunohost.org/appci/app/mygpo) ![](https://ci-apps.yunohost.org/ci/badges/mygpo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mygpo.maintain.svg)  
[![Installer mygpo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mygpo)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer mygpo rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Ceci est le service derrière https://gpodder.net. Il peut servir pour synchronizer vos flux balado entre [clients compatibles](https://gpoddernet.readthedocs.io/en/latest/user/clients.html).

**Version incluse :** f9a89d37ad53eb688c7d7256f32fe230f95b9046

## Captures d'écran

![](https://github.com/YunoHost-Apps/mygpo_ynh/raw/master/screenshot.png)

## Démo

* [Démo officielle](https://gpodder.net)

## Configuration

Modifiez les fichiers sous `/opt/yunohost/APPDIR/envs/prod` pour configurer les variables d'environment.

## Documentation

 * Documentation officielle : https://gpoddernet.readthedocs.io/

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Seulement LDAP**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mygpo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mygpo/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mygpo%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mygpo/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

**Plus d'informations sur la page de documentation :**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/mygpo_ynh/issues
 * Site de l'application : https://gpodder.net
 * Dépôt de l'application principale : https://github.com/gpodder/mygpo
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mygpo_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mygpo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mygpo -u https://github.com/YunoHost-Apps/mygpo_ynh/tree/testing --debug
```
