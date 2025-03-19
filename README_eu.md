<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# MyDrive YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/mydrive)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/mydrive)

[![Instalatu MyDrive YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek MyDrive YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Open Source cloud file storage server (similar to Google Drive). Host myDrive on your own trusted server or platform, then access myDrive via your web browser. MyDrive uses mongoDB to store file/folder metadata and supports multiple databases to store file chunks, such as Amazon S3 or the File System.

### Features

- File upload
- Folder upload (automatic conversion to zip)
- Support for multiple databases (Amazon S3, file system)
- Photo and video viewer and media gallery
- Generated thumbnails of photos and videos
- File sharing
- AES256 encryption
- Mobile support
- Email verification


**Paketatutako bertsioa:** 4.0.2~ynh1

**Demoa:** <http://143.244.181.219:3000/>

## Pantaila-argazkiak

![MyDrive(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://mydrive-storage.com/>
- Administratzaileen dokumentazio ofiziala: <https://mydrive-storage.com/download>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/subnub/myDrive>
- YunoHost Denda: <https://apps.yunohost.org/app/mydrive>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
edo
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
