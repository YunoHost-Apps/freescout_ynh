<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# FreeScout pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/freescout.svg)](https://ci-apps.yunohost.org/ci/apps/freescout/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/freescout.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/freescout.maintain.svg)

[![Installer FreeScout avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer FreeScout rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

FreeScout est un service d'assistance open source gratuit ultra léger et puissant et une boîte de réception partagée construite avec PHP (framework Laravel). Vous pouvez désormais profiter gratuitement de Zendesk et Help Scout sans renoncer à votre confidentialité ni vous enfermer dans un service que vous ne contrôlez pas.

**Version incluse :** 1.8.148~ynh1

**Démo :** <https://demo.freescout.net/login>

## Captures d’écran

![Capture d’écran de FreeScout](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application sous licence libre restreinte **: L'application packagée est sous une licence globalement libre, mais avec des clauses qui pourraient restreindre son utilisation.

## Documentations et ressources

- Site officiel de l’app : <https://freescout.net/>
- Documentation officielle de l’admin : <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- Dépôt de code officiel de l’app : <https://github.com/freescout-helpdesk/freescout>
- YunoHost Store : <https://apps.yunohost.org/app/freescout>
- Signaler un bug : <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
ou
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
