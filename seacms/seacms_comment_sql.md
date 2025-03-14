# Analysis Report:

filename: \SeaCMS_13\Upload\o09sqn\admin_comment.php

![img](./images/comment1.png)

Variables are simply concatenated directly into sql statements resulting in sql injection

# Verification

![img](./images/rce4.png)

Sending a request triggers sql injection

![img](./images/comment2.png)