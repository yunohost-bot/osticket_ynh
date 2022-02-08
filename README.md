<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# osTicket for YunoHost

[![Integration level](https://dash.yunohost.org/integration/osticket.svg)](https://dash.yunohost.org/appci/app/osticket) ![](https://ci-apps.yunohost.org/ci/badges/osticket.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/osticket.maintain.svg)  
[![Install osTicket with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osticket)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install osTicket quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

osTicket is a widely-used open source support ticket system. It seamlessly integrates inquiries created via email, phone and web-based forms into a simple easy-to-use multi-user web interface. Manage, organize and archive all your support requests and responses in one place while providing your customers with accountability and responsiveness they deserve.

**Shipped version:** 1.16~ynh1

**Demo:** http://www.ostickethacks.com/demo/demo_info.php

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

* LDAP and HTTP auth are supported through plugins

## Documentation and resources

* Official app website: https://osticket.com
* Official user documentation: https://docs.osticket.com
* Upstream app code repository: https://github.com/osTicket/osTicket
* YunoHost documentation for this app: https://yunohost.org/app_osticket
* Report a bug: https://github.com/YunoHost-Apps/osticket_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/osticket_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/osticket_ynh/tree/testing --debug
or
sudo yunohost app upgrade osticket -u https://github.com/YunoHost-Apps/osticket_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps