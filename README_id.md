<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# MyDrive untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Status kerja](https://apps.yunohost.org/badge/state/mydrive)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/mydrive)

[![Pasang MyDrive dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang MyDrive secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 4.0.2~ynh1

**Demo:** <http://143.244.181.219:3000/>

## Tangkapan Layar

![Tangkapan Layar pada MyDrive](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://mydrive-storage.com/>
- Dokumentasi admin resmi: <https://mydrive-storage.com/download>
- Depot kode aplikasi hulu: <https://github.com/subnub/myDrive>
- Gudang YunoHost: <https://apps.yunohost.org/app/mydrive>
- Laporkan bug: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
atau
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
