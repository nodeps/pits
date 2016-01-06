# pits
一些坑，留下印记

启动Apache

启动：sudo apachectl start

停止：sudo apachectl stop

重启：sudo apachectl restart

<Directory "/Library/WebServer/Documents">
将 Options FollowSymLinks Multiviews 修改为 Options Indexes FollowSymLinks Multiviews
查看是否有如下配置

Options Indexes MultiViews FollowSymLinks

AllowOverride All

Order allow,deny

Allow from all

Require all granted


如果权限不够

cd 你的文件夹路径的上一级目录。

sudo chmod -R 777 你的文件夹名

