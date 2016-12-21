Magento 2 Install Script
---
 
Welcome.
 
Usage
---

Make sure you having PHP 7.0 FPM, Nginx, MySQL >=5.6, NodeJS latest.

Create database:

```
CREATE DATABASE `magento2` CHARACTER SET utf8 COLLATE utf8_general_ci;
```

Place install.sh to the root your project.

Edit setup.sh to change configuration according your mind.

Replace the content of nginx.conf.sample in root project by the file conf in this repository, uncomment **upstream fastcgi_backend** if you haven't never used it in any nginx conf file before yet, edit nginx.conf.sample follow your configuration.
 
Setup
---

Navigate to root folder:
 
```
chmod u+x install.sh
bash install.sh
```

All done!