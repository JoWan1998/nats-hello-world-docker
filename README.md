## Start by...

- `git clone https://github.com/abhirockzz/nats-hello-world-docker.git`
- `cd nats-hello-world-docker/java-publisher`
- `mvn clean install`
- `cd ..`

## To run

`docker-compose build --no-cache` //build containers

Give it a few seconds

![](https://simplydistributed.files.wordpress.com/2018/03/docker-compose-up.jpg)

`docker-compose up` //start containers

## check

### check NATS console

`http://<docker_host_ip>:8222`

![](https://simplydistributed.files.wordpress.com/2018/03/nats-console.jpg)

`http://<docker_host_ip>:8222/connz`

![](https://simplydistributed.files.wordpress.com/2018/03/nats-connz.jpg)

### check `docker-compose` logs

Pub and sub... the usual stuff

![](https://simplydistributed.files.wordpress.com/2018/03/app-logs.jpg)

## .. clean up using

`docker-compose down`

