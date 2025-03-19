<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# MyDrive para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Estado funcional](https://apps.yunohost.org/badge/state/mydrive)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/mydrive)

[![Instalar MyDrive con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarMyDrive rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 4.0.2~ynh1

**Demo:** <http://143.244.181.219:3000/>

## Capturas

![Captura de MyDrive](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://mydrive-storage.com/>
- Documentación administrador oficial: <https://mydrive-storage.com/download>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/subnub/myDrive>
- Catálogo YunoHost: <https://apps.yunohost.org/app/mydrive>
- Reportar un error: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
o
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
