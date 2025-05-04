# CVE-2025-44073
# Analysis Report:

filename: \SeaCMS_13\Upload\o09sqn\admin_comment_news.php

![img](./images/comment_news1.png)

Variables are simply concatenated directly into sql statements resulting in sql injection

# Verification

![img](./images/rce4.png)

Sending a request triggers sql injection

![img](./images/comment_news2.png)
