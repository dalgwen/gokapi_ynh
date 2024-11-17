<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Gokapi untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/gokapi.svg)](https://ci-apps.yunohost.org/ci/apps/gokapi/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/gokapi.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/gokapi.maintain.svg)

[![Pasang Gokapi dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gokapi)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Gokapi secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Gokapi is a lightweight server to share files, which expire after a set amount of downloads or days. It is similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files.

**Versi terkirim:** 1.9.2~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Gokapi](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://gokapi.readthedocs.io/>
- Depot kode aplikasi hulu: <https://github.com/Forceu/Gokapi>
- Gudang YunoHost: <https://apps.yunohost.org/app/gokapi>
- Laporkan bug: <https://github.com/YunoHost-Apps/gokapi_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
atau
sudo yunohost app upgrade gokapi -u https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
