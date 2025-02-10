<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 mygpo (gPodder.net)

[![集成程度](https://apps.yunohost.org/badge/integration/mygpo)](https://ci-apps.yunohost.org/ci/apps/mygpo/)
![工作状态](https://apps.yunohost.org/badge/state/mygpo)
![维护状态](https://apps.yunohost.org/badge/maintained/mygpo)

[![使用 YunoHost 安装 mygpo (gPodder.net)](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mygpo)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 mygpo (gPodder.net)。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

This is the webservice powering the https://gpodder.net website. It can be used to sync podcast subscriptions with [supported clients](https://gpoddernet.readthedocs.io/en/latest/user/clients.html).


**分发版本：** 2025.02.08~ynh1

**演示：** <https://gpodder.net>

## 截图

![mygpo (gPodder.net) 的截图](./doc/screenshots/screenshot1.png)

## 文档与资源

- 官方应用网站： <https://gpodder.net>
- 官方管理文档： <https://gpoddernet.readthedocs.io/>
- 上游应用代码库： <https://github.com/gpodder/mygpo>
- YunoHost 商店： <https://apps.yunohost.org/app/mygpo>
- 报告 bug： <https://github.com/YunoHost-Apps/mygpo_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/mygpo_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mygpo_ynh/tree/testing --debug
或
sudo yunohost app upgrade mygpo -u https://github.com/YunoHost-Apps/mygpo_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
