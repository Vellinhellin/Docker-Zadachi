## База данных Redis

Запуск **Redis**
```shell
docker run -d --name my-redis -p 6379:6379 redis:alpine
```

![alt text](./img/apachi/Redis/perv.png)

Подключиться к **Redis CLI**
```shell
docker exec -it my-redis redis-cli
```
![alt text](./img/apachi/Redis/vtor.png)

Внутри Redis: ping → PONG, SET key value, GET key - ?

![alt text](./img/apachi/Redis/tret.png)

![alt text](./img/apachi/Redis/chetv.png)

![alt text](./img/apachi/Redis/pyat.png)