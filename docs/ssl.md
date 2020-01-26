---
layout: default
title: SSL/TLS
nav_order: 6
---

### SSL/TLS
Switch to SSL tab and select the PKCS12 file which is needed to establish a secure connection: 

![ssl tab](/assets/images/ssl/ssl-tab.png)

### PKCS12 File
You can use the following command to generate a PKCS12 file:

```openssl pkcs12 -export -in redislabs_user.crt -inkey redislabs_user_private.key -out redisclient.p12 -passout pass:your_password```