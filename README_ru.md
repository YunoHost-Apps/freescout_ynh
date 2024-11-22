<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# FreeScout для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/freescout.svg)](https://ci-apps.yunohost.org/ci/apps/freescout/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/freescout.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/freescout.maintain.svg)

[![Установите FreeScout с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить FreeScout быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

FreeScout is the super lightweight and powerful free open source help desk and shared inbox built with PHP (Laravel framework). Now you can enjoy free Zendesk & Help Scout without giving up privacy or locking yourself into a service you don't control.

**Поставляемая версия:** 1.8.158~ynh1

**Демо-версия:** <https://demo.freescout.net/login>

## Снимки экрана

![Снимок экрана FreeScout](./doc/screenshots/screenshot.png)

## :red_circle: Анти-функции

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://freescout.net/>
- Официальная документация администратора: <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- Репозиторий кода главной ветки приложения: <https://github.com/freescout-helpdesk/freescout>
- Магазин YunoHost: <https://apps.yunohost.org/app/freescout>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
или
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
