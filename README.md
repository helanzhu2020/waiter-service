# waiter-service

## build
```shell
mvn clean package
```

## run
```shell
java -jar target/waiter-service-xxx.jar
```

## run with docker
```shell
docker build . -t helanzhu/waiter-service-h2:1.0.0
docker run --name waiter-service-h2 -d -p 8080:8080 -p 8081:8081 helanzhu/waiter-service-h2:1.0.0
```