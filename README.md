<!--
Nota bene: ce README est automatiquement généré par https://github.com/YunoHost/apps/tree/master/tools/readme_generator
Il ne doit pas être modifié à la main.
-->

# FreeScout pour YunoHost

[![Niveau d'intégration ](https://dash.yunohost.org/integration/freescout.svg)](https://dash.yunohost.org/appci/app/freescout) ![Status du fonctionnement](https://ci-apps.yunohost.org/ci/badges/freescout.status.svg) ![Statut demaintenance](https://ci-apps.yunohost.org/ci/badges/freescout.maintain.svg)

[![Installer FreeScout avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer FreeScout rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d'ensemble

FreeScout is the super lightweight and powerful free open source help desk and shared inbox built with PHP (Laravel framework). Now you can enjoy free Zendesk & Help Scout without giving up privacy or locking yourself into a service you don't control.
**Version incluse :** 1.8.128~ynh1

**Démo:** <https://demo.freescout.net/login>

## Captures d'écran

![Capture d'écran de FreeScout](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Not totally free upstream**: The packaged app is under an overall free licence, but with clauses that restrict its use.

## Documentations et ressources

- Site officiel de l’app : <https://freescout.net/>
- Documentation officielle de l'admin <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- Dépôt de code officiel de l’app : <https://github.com/freescout-helpdesk/freescout>
- YunoHost Store : <https://apps.yunohost.org/app/freescout>
- Signaler un bug : <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche branch](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing),


Pour essayer la branche testing, procédez comme suit.

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
or
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>
