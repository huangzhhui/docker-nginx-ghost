# docker-nginx-ghost
Docker composition of Ghost blog with Node, NGINX proxy
Base on official docker image

# Quickstart

[Install Docker](https://www.docker.io/gettingstarted/) and [Docker Compose](https://docs.docker.com/compose/install/), then:

1.Clone this project
```Shell
git clone https://github.com/huangzhhui/docker-nginx-ghost.git
```
2.Edit nginx config in `docker-nginx-ghost/nginx/conf.d/default.conf`, change `example.com` to your domain name
3.Start Nginx and Ghost
```Shell
cd docker-nginx-ghost && docker-compose up -d
```
4.In a browser, open `yourdomainname.com`
