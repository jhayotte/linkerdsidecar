# linkerd as side car
LinkerSideCar shows an implementation of linkerd in a side car mode allowing to delegate some task to the infrastructure and add feature to our microservice.

In this project, a trace of each call is visible in zipkin and everything works through a docker-compose.

This project is mainly base on the sample of code of **openzipkin**!

![alt tag](https://raw.githubusercontent.com/jhayotte/linkerdsidecar/master/doc/zipkin.png)

# Howto

```
docker-compose up --build
curl -s 127.1:8001/run
```


