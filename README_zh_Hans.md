<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 MARL

[![集成程度](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![工作状态](https://apps.yunohost.org/badge/state/marl)
![维护状态](https://apps.yunohost.org/badge/maintained/marl)

[![使用 YunoHost 安装 MARL](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 MARL。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Mastodon Archive Reader Lite (MARL) is a lightweight, single-page app that provides a user-friendly interface to explore the content of a Mastodon archive file: account data, posts, attachments, etc.

It runs in-browser and does not store any user data on the server (apart from the access log as per your YNH configuration).


**分发版本：** 2.4~ynh1

**演示：** <https://s427.github.io/MARL>

## 截图

![MARL 的截图](./doc/screenshots/marl_ynh.png)

## 文档与资源

- 官方用户文档： <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- 上游应用代码库： <https://github.com/s427/MARL>
- YunoHost 商店： <https://apps.yunohost.org/app/marl>
- 报告 bug： <https://github.com/YunoHost-Apps/marl_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/marl_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
或
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
