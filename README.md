# linkerd as side car
LinkerSideCar shows an implementation of linkerd in a side car mode allowing to delegate some task to the infrastructure and add feature to our microservice.

In this project, a trace of each call is visible in zipkin and everything works through a docker-compose.

#Howto

```
docker-compose up --build
curl -s 127.1:8001/run
```

