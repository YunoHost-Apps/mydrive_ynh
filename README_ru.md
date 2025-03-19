<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# MyDrive для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![Состояние работы](https://apps.yunohost.org/badge/state/mydrive)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/mydrive)

[![Установите MyDrive с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить MyDrive быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 4.0.2~ynh1

**Демо-версия:** <http://143.244.181.219:3000/>

## Снимки экрана

![Снимок экрана MyDrive](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://mydrive-storage.com/>
- Официальная документация администратора: <https://mydrive-storage.com/download>
- Репозиторий кода главной ветки приложения: <https://github.com/subnub/myDrive>
- Магазин YunoHost: <https://apps.yunohost.org/app/mydrive>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
или
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
