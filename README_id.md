<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Mastodon Archive Reader Lite untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/marl)](https://ci-apps.yunohost.org/ci/apps/marl/)
![Status kerja](https://apps.yunohost.org/badge/state/marl)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/marl)

[![Pasang Mastodon Archive Reader Lite dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=marl)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Mastodon Archive Reader Lite secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Mastodon Archive Reader Lite (MARL) is a lightweight, single-page app that provides a user-friendly interface to explore the content of a Mastodon archive file: account data, posts, attachments, etc.

It runs in-browser and does not store any user data on the server (apart from the access log as per your YNH configuration).


**Versi terkirim:** 1.0~ynh1

**Demo:** <https://s427.github.io/MARL>

## Tangkapan Layar

![Tangkapan Layar pada Mastodon Archive Reader Lite](./doc/screenshots/marl_ynh.png)

## Dokumentasi dan sumber daya

- Dokumentasi pengguna resmi: <https://github.com/s427/MARL?tab=readme-ov-file#usage>
- Depot kode aplikasi hulu: <https://github.com/s427/MARL>
- Gudang YunoHost: <https://apps.yunohost.org/app/marl>
- Laporkan bug: <https://github.com/YunoHost-Apps/marl_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/marl_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
atau
sudo yunohost app upgrade marl -u https://github.com/YunoHost-Apps/marl_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
