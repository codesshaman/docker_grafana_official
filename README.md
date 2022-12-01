# Official grafana image

Your need make, docker and docker-compose in your operation system.

CLONE:

``git clone https://github.com/codesshaman/docker_grafana_official.git``

GO TO FOLDER:

``cd docker_grafana_official``

MAKE ENV FILE:

``mv .env_sample .env``

BUILD (first start):

``make build``

RUN:

``make``

STOP:

``make down``

CONNECT:

``docker exec -it grafana sh``

OPEN (if port is 3000):
http://your-host:3000/