<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# MyDrive voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/mydrive)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/mydrive)

[![MyDrive met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je MyDrive snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 4.0.2~ynh1

**Demo:** <http://143.244.181.219:3000/>

## Schermafdrukken

![Schermafdrukken van MyDrive](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://mydrive-storage.com/>
- Officiele beheerdersdocumentatie: <https://mydrive-storage.com/download>
- Upstream app codedepot: <https://github.com/subnub/myDrive>
- YunoHost-store: <https://apps.yunohost.org/app/mydrive>
- Meld een bug: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
of
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
