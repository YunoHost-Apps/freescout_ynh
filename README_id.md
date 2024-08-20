<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# FreeScout untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/freescout.svg)](https://ci-apps.yunohost.org/ci/apps/freescout/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/freescout.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/freescout.maintain.svg)

[![Pasang FreeScout dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang FreeScout secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

FreeScout is the super lightweight and powerful free open source help desk and shared inbox built with PHP (Laravel framework). Now you can enjoy free Zendesk & Help Scout without giving up privacy or locking yourself into a service you don't control.

**Versi terkirim:** 1.8.150~ynh1

**Demo:** <https://demo.freescout.net/login>

## Tangkapan Layar

![Tangkapan Layar pada FreeScout](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://freescout.net/>
- Dokumentasi admin resmi: <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- Depot kode aplikasi hulu: <https://github.com/freescout-helpdesk/freescout>
- Gudang YunoHost: <https://apps.yunohost.org/app/freescout>
- Laporkan bug: <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
atau
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
