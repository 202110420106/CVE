# CVE-2025-44077
# Analysis Report:

filename: \SeaCMS_13\Upload\o09sqn\admin_tempvideo.php

![img](./images/tempvideo1.png)

Variables are simply concatenated directly into sql statements resulting in sql injection

# Verification

![img](./images/rce4.png)

Sending a request triggers sql injection

![img](./images/tempvideo2.png)
