﻿<!-- https://www.itzgeek.com/how-tos/linux/centos-how-tos/install-nginx-on-centos-7-rhel-7.html -->
<!-- https://docs.nginx.com/nginx/admin-guide/installing-nginx/installing-nginx-open-source/ (alternative) -->
<!-- http://johanlouwers.blogspot.com/2016/01/install-nginx-on-oracle-linux.html (alternative) -->

```sh
rpm -Uvh http://nginx.org/packages/rhel/7/noarch/RPMS/nginx-release-rhel-7-0.el7.ngx.noarch.rpm
yum install nginx
systemctl enable nginx.service
systemctl start nginx.service
``` 
