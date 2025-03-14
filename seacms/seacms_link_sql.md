# Analysis Report:

filename: \SeaCMS_13\Upload\o09sqn\admin_link.php

![](./images/link3.png)

Variables are simply concatenated directly into sql statements resulting in sql injection

# Verification

![](./images/rce4.png)

Sending a request triggers sql injection

![](./images/link4.png)

