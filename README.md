# Nginx load balancer
**for docker containers, using consul template**

*this is a fork of [docker-loadbalancer](https://github.com/bellycard/docker-loadbalancer)*

You can find the image at [Docker Hub](https://hub.docker.com/r/princemaple/consul-template-nginx/)

    docker pull princemaple/consul-template-nginx:v3
    
mount your own nginx.conf into the container if you need more complex configuration

## See it working

    docker-compose build
    docker-compose up -d
    # play with it in your browser
    # ...when had enough fun
    docker-compose scale app=5
    # go have some more fun
