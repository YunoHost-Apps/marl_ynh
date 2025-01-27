<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# MARL pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/marl)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/marl)

[![Installer MARL avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer MARL rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Mastodon Archive Reader Lite (MARL) est une application légère tenant sur une page qui fournit une interface attrayante pour explorer le contenu d'une archive Mastodon: données de compte, posts, pièces jointes, etc.

Elle s'execute dans le navigateur du visiteur et aucune donnée utilisateur n'est stockée sur le serveur (hormis les logs d'accès selon votre configuration YNH).


**Version incluse :** 2.3~ynh1

**Démo :** <https://s427.github.io/MARL>

## Captures d’écran

![Capture d’écran de MARL](./doc/screenshots/marl_ynh.png)

## Documentations et ressources

- Documentation officielle utilisateur : <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- Dépôt de code officiel de l’app : <https://github.com/s427/MARL>
- YunoHost Store : <https://apps.yunohost.org/app/marl>
- Signaler un bug : <https://github.com/YunoHost-Apps/marl_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/marl_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
ou
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
