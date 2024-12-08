<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# MARL для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![Состояние работы](https://apps.yunohost.org/badge/state/marl)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/marl)

[![Установите MARL с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить MARL быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Mastodon Archive Reader Lite (MARL) is a lightweight, single-page app that provides a user-friendly interface to explore the content of a Mastodon archive file: account data, posts, attachments, etc.

It runs in-browser and does not store any user data on the server (apart from the access log as per your YNH configuration).


**Поставляемая версия:** 1.0~ynh1

**Демо-версия:** <https://s427.github.io/MARL>

## Снимки экрана

![Снимок экрана MARL](./doc/screenshots/marl_ynh.png)

## Документация и ресурсы

- Официальная документация пользователя: <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- Репозиторий кода главной ветки приложения: <https://github.com/s427/MARL>
- Магазин YunoHost: <https://apps.yunohost.org/app/marl>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/marl_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/marl_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
или
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
