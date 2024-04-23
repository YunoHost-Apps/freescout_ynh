<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# FreeScout YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/freescout.svg)](https://dash.yunohost.org/appci/app/freescout) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/freescout.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/freescout.maintain.svg)

[![Instalatu FreeScout YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek FreeScout YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

FreeScout is the super lightweight and powerful free open source help desk and shared inbox built with PHP (Laravel framework). Now you can enjoy free Zendesk & Help Scout without giving up privacy or locking yourself into a service you don't control.

**Paketatutako bertsioa:** 1.8.137~ynh1

**Demoa:** <https://demo.freescout.net/login>

## Pantaila-argazkiak

![FreeScout(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizkoa ez da erabat librea**: Aplikazioak lizentzia librea du orokorrean, baina bere erabilera mugatzen duten klausulekin.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://freescout.net/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/freescout-helpdesk/freescout>
- YunoHost Denda: <https://apps.yunohost.org/app/freescout>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
edo
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
