<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# MyDrive dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Status działania](https://apps.yunohost.org/badge/state/mydrive)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/mydrive)

[![Zainstaluj MyDrive z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację MyDrive na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 4.0.2~ynh1

**Demo:** <http://143.244.181.219:3000/>

## Zrzuty ekranu

![Zrzut ekranu z MyDrive](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://mydrive-storage.com/>
- Oficjalna dokumentacja dla administratora: <https://mydrive-storage.com/download>
- Repozytorium z kodem źródłowym: <https://github.com/subnub/myDrive>
- Sklep YunoHost: <https://apps.yunohost.org/app/mydrive>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
lub
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
