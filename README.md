# web-php

`docker run --name nginx -p 80:80 -p 443:443 -v /data/nginx/conf.d:/etc/nginx/conf.d -d nginx:1.9.10`

`docker run --name www.keruikeji.com -v /data/wwwroot/www.keruikeji.com/:/var/www/html/ -d web-php`
