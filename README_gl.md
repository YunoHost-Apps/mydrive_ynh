<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# MyDrive para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/mydrive)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/mydrive)

[![Instalar MyDrive con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar MyDrive de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 4.0.2~ynh1

**Demo:** <http://143.244.181.219:3000/>

## Capturas de pantalla

![Captura de pantalla de MyDrive](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://mydrive-storage.com/>
- Documentación oficial para admin: <https://mydrive-storage.com/download>
- Repositorio de orixe do código: <https://github.com/subnub/myDrive>
- Tenda YunoHost: <https://apps.yunohost.org/app/mydrive>
- Informar dun problema: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
