<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Mastodon Archive Reader Lite for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![Working status](https://apps.yunohost.org/badge/state/marl)
![Maintenance status](https://apps.yunohost.org/badge/maintained/marl)

[![Install Mastodon Archive Reader Lite with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Mastodon Archive Reader Lite quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Mastodon Archive Reader Lite (MARL) is a lightweight, single-page app that provides a user-friendly interface to explore the content of a Mastodon archive file: account data, posts, attachments, etc.

It runs in-browser and does not store any user data on the server (apart from the access log as per your YNH configuration).


**Shipped version:** 1.0~ynh1

**Demo:** <https://s427.github.io/MARL>

## Screenshots

![Screenshot of Mastodon Archive Reader Lite](./doc/screenshots/marl_ynh.png)

## Documentation and resources

- Official user documentation: <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- Upstream app code repository: <https://github.com/s427/MARL>
- YunoHost Store: <https://apps.yunohost.org/app/marl>
- Report a bug: <https://github.com/YunoHost-Apps/marl_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/marl_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
or
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
