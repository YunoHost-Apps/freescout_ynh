<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 FreeScout

[![集成程度](https://apps.yunohost.org/badge/integration/freescout)](https://ci-apps.yunohost.org/ci/apps/freescout/)
![工作状态](https://apps.yunohost.org/badge/state/freescout)
![维护状态](https://apps.yunohost.org/badge/maintained/freescout)

[![使用 YunoHost 安装 FreeScout](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 FreeScout。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

FreeScout is the super lightweight and powerful free open source help desk and shared inbox built with PHP (Laravel framework). Now you can enjoy free Zendesk & Help Scout without giving up privacy or locking yourself into a service you don't control.

**分发版本：** 1.8.173~ynh1

**演示：** <https://demo.freescout.net/login>

## 截图

![FreeScout 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## 文档与资源

- 官方应用网站： <https://freescout.net/>
- 官方管理文档： <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- 上游应用代码库： <https://github.com/freescout-helpdesk/freescout>
- YunoHost 商店： <https://apps.yunohost.org/app/freescout>
- 报告 bug： <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
或
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
