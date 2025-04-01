<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# MARL voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/marl)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/marl)

[![MARL met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je MARL snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Mastodon Archive Reader Lite (MARL) is a lightweight, single-page app that provides a user-friendly interface to explore the content of a Mastodon archive file: account data, posts, attachments, etc.

It runs by default in Local Mode, i.e. in-browser and does not store any user data on the server (apart from the access log as per your YNH configuration).
However you can also set it in Server Mode via the app configuration options, in order to display permanently one or several Mastodon archives stored online.


**Geleverde versie:** 2.7~ynh1

**Demo:** <https://s427.github.io/MARL>

## Schermafdrukken

![Schermafdrukken van MARL](./doc/screenshots/marl_ynh.png)

## Documentatie en bronnen

- Officiele gebruikersdocumentatie: <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- Upstream app codedepot: <https://github.com/s427/MARL>
- YunoHost-store: <https://apps.yunohost.org/app/marl>
- Meld een bug: <https://github.com/YunoHost-Apps/marl_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/marl_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
of
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
