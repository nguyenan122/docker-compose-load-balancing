# docker-compose-load-balancing
# 1. Download code

  $git clone https://github.com/nguyenan122/docker-compose-load-balancing.git



# 2. Start service

  $docker-compose up

  Test:

  $ curl 127.0.0.1 | grep "SERVER_ADDR"




# 3. Start service with scale

  $ docker-compose scale web1=3 web2=5

  $ docker-compose restart

  Test:

  $ curl 127.0.0.1 | grep "SERVER_ADDR"

