# CVE-2025-44072
# Analysis Report:

filename: \SeaCMS_13\Upload\o09sqn\admin_manager.php

![](./images/sql1.png)

Variables are simply concatenated directly into sql statements resulting in sql injection

# Verification

![](.\images\rce4.png)

Sending a request triggers sql injection

![](./images/sql2.png)

