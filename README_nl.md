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
