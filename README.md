# docker-lamp
apache mysql php with docker

```
git clone https://github.com/culmat/docker-lamp.git
cd docker-lamp
docker-compose up
```
Point your browser to http://localhost/ or http://localhost/info.php

You may overide [default settings](https://github.com/culmat/docker-lamp/blob/master/.env) by simply setting corresponding environment variables e.g.

```
export WWW_ROOT=~/git/myCoolProject/
docker-compose up
```
