<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# LibreTranslate for YunoHost

[![Integration level](https://dash.yunohost.org/integration/libretranslate.svg)](https://dash.yunohost.org/appci/app/libretranslate) ![Working status](https://ci-apps.yunohost.org/ci/badges/libretranslate.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/libretranslate.maintain.svg)

[![Install LibreTranslate with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libretranslate)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install LibreTranslate quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Free and Open Source Machine Translation API, entirely self-hosted. Unlike other APIs, it doesn't rely on proprietary providers such as Google or Azure to perform translations. Instead, its translation engine is powered by the open source Argos Translate library.


**Shipped version:** 1.3.10~ynh1

**Demo:** https://libretranslate.com/

## Screenshots

![Screenshot of LibreTranslate](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://libretranslate.com/>
* Official admin documentation: <https://libretranslate.com/docs/>
* Upstream app code repository: <https://github.com/LibreTranslate/LibreTranslate>
* YunoHost documentation for this app: <https://yunohost.org/app_libretranslate>
* Report a bug: <https://github.com/YunoHost-Apps/libretranslate_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/libretranslate_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/libretranslate_ynh/tree/testing --debug
or
sudo yunohost app upgrade libretranslate -u https://github.com/YunoHost-Apps/libretranslate_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
