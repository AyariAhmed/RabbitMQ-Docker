## RabbitMQ - Docker container config

Start the container using the command :
```console
docker-compose up
```

### Management Web Interface :
```text
localhost:15672/
```

### login Credential
```text
Admin user : admin / admin
Guest user : guest / guest
```


### To save configuration : 
At the end of the session , after user/exchange/queue creation(or deletion,modification) export Broker definitions (can be found at the end of the overview page) to /rabbitmq/etc/definitions.json (those exported definitions will be loaded at container startup)