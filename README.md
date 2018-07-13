# docker-compose-load-balancing

$git clone https://github.com/nguyenan122/docker-compose-load-balancing.git

$docker-compose up

$ curl 127.0.0.1 | grep "SERVER_ADDR"

$ docker-compose scale web1=3 web2=5

$ docker-compose restart
