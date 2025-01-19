<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Gokapi YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/gokapi)](https://ci-apps.yunohost.org/ci/apps/gokapi/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/gokapi)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/gokapi)

[![Instalatu Gokapi YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gokapi)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Gokapi YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Gokapi is a lightweight server to share files, which expire after a set amount of downloads or days. It is similar to the discontinued Firefox Send, with the difference that only the admin is allowed to upload files.

**Paketatutako bertsioa:** 1.9.6~ynh2

## Pantaila-argazkiak

![Gokapi(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://gokapi.readthedocs.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Forceu/Gokapi>
- YunoHost Denda: <https://apps.yunohost.org/app/gokapi>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/gokapi_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
edo
sudo yunohost app upgrade gokapi -u https://github.com/YunoHost-Apps/gokapi_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
