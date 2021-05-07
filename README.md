# Jenkins
Ref:
- https://hub.docker.com/_/jenkins

## Build jenkins
```shell
$ docker pull jenkins
```
## Run 
```shell
$ docker run -p 8080:8080 -p 50000:50000 -v /var/jenkins_home jenkins/jenkins:lts
```

## ngrok

Ref: https://ngrok.com/product

Ngrok exposes local servers behind NATs and firewalls to the public internet over secure tunnels.
```shell
$ ngrok http 8080 
```
