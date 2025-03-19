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

Serveur de stockage de fichiers en nuage Open Source (similaire à Google Drive). Hébergez myDrive sur votre propre serveur ou plateforme de confiance, puis accédez à myDrive via votre navigateur web. MyDrive utilise mongoDB pour stocker les métadonnées des fichiers/dossiers et prend en charge plusieurs bases de données pour stocker les morceaux de fichiers, comme Amazon S3 ou le système de fichiers.

### Caractéristiques

- Téléchargement de fichiers
- Téléchargement de fichiers
- Téléchargement de dossiers
- Téléchargement de dossiers (conversion automatique en zip)
- Prise en charge de plusieurs bases de données (Amazon S3, système de fichiers)
- Visionneuse de photos et de vidéos et galerie de médias
- Vignettes de photos et de vidéos générées
- Partage de fichiers
- Support PWA
- Chiffrement AES256
- Support mobile
- Vérification des courriels
- JWT (jetons d'accès et de rafraîchissement)


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
