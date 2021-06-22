# docker_compose_demos

Example of:

Communication between two docker compose networks

Use of different redis port than default: 6379

Use of different redis service name than usual: redis



## Bringup redis via one compose
```cd service2```\
```docker-compose up```

## Bringup flask app via another compose
```cd service1```\
```docker-compose up```

## Access url
[http://127.0.0.1:5000/](http://127.0.0.1:5000/)
