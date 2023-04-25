# configserver

## build with buildpacks

## generate jar file
```$bash
mvn clean install
```

## build image
```$bash
mvn spring-boot:build-image
```

## push image
```$bash
docker push pblgllgs/gatewayserver-eb:latest
```

## rabbitMQ
```$bash
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
```