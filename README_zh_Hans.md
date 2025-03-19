<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 MyDrive

[![集成程度](https://apps.yunohost.org/badge/integration/mydrive)](https://ci-apps.yunohost.org/ci/apps/mydrive/)
![工作状态](https://apps.yunohost.org/badge/state/mydrive)
![维护状态](https://apps.yunohost.org/badge/maintained/mydrive)

[![使用 YunoHost 安装 MyDrive](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mydrive)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 MyDrive。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 4.0.2~ynh1

**演示：** <http://143.244.181.219:3000/>

## 截图

![MyDrive 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://mydrive-storage.com/>
- 官方管理文档： <https://mydrive-storage.com/download>
- 上游应用代码库： <https://github.com/subnub/myDrive>
- YunoHost 商店： <https://apps.yunohost.org/app/mydrive>
- 报告 bug： <https://github.com/YunoHost-Apps/mydrive_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
或
sudo yunohost app upgrade mydrive -u https://github.com/YunoHost-Apps/mydrive_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
