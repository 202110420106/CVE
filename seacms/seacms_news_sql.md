# Analysis Report:

filename: \SeaCMS_13\Upload\o09sqn\admin_news.php

![](.\images\news1.png)

Variables are simply concatenated directly into sql statements resulting in sql injection

# Verification

![img](./images/rce4.png)

Sending a request triggers sql injection

![](./images/news2.png)