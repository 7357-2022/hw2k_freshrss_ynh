<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# FreshRSS for YunoHost (forked for the HW2K website)

[![Integration level](https://dash.yunohost.org/integration/freshrss.svg)](https://dash.yunohost.org/appci/app/freshrss) ![](https://ci-apps.yunohost.org/ci/badges/freshrss.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/freshrss.maintain.svg)  
[![Install FreshRSS with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freshrss)

> *This package allows you to install FreshRSS quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

RSS aggregator with a nice and mobile-friendly design

**Shipped version:** 1.20.2~ynh1

**Demo:** https://demo.freshrss.org

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

API (mini) How To:
* Into your user profile: Settings > profil
* Setup an API password
* Check that the API is working: https://example.net/rss/api/greader.php
* Setup your client with: username: ynh user, password: the password you just setup, URL https://example.tld/rss/api/greader.php

## Documentation and resources

* YunoHost app: <https://github.com/YunoHost-Apps/freshrss_ynh>
* Official app website: http://freshrss.org/
* Official admin documentation: https://freshrss.github.io/FreshRSS/
* Upstream app code repository: https://github.com/FreshRSS/FreshRSS
* YunoHost documentation for this app: https://yunohost.org/app_freshrss
* Report a bug: https://github.com/YunoHost-Apps/freshrss_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/7357-2022/hw2k_freshrss_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/7357-2022/hw2k_freshrss_ynh/tree/testing --debug
```
or
```
sudo yunohost app upgrade freshrss -u https://github.com/7357-2022/hw2k_freshrss_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps
