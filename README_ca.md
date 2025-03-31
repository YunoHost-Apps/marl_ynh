<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# MARL per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/marl)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/marl)

[![Instal·la MARL amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar MARL de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

Mastodon Archive Reader Lite (MARL) is a lightweight, single-page app that provides a user-friendly interface to explore the content of a Mastodon archive file: account data, posts, attachments, etc.

It runs by default in Local Mode, i.e. in-browser and does not store any user data on the server (apart from the access log as per your YNH configuration).
However you can also set it in Server Mode via the app configuration options, in order to display permanently one or several Mastodon archives stored online.


**Versió inclosa:** 2.7~ynh1

**Demo:** <https://s427.github.io/MARL>

## Captures de pantalla

![Captures de pantalla de MARL](./doc/screenshots/marl_ynh.png)

## Documentació i recursos

- Documentació oficial per l'usuari: <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- Repositori oficial del codi de l'aplicació: <https://github.com/s427/MARL>
- Botiga YunoHost: <https://apps.yunohost.org/app/marl>
- Reportar un error: <https://github.com/YunoHost-Apps/marl_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/marl_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
o
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
