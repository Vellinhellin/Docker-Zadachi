# Adminer
## Запустите Adminer в Windows Powershell
```
docker run -d `
  --name adminer `
  -p 8084:8080 `
  adminer:latest
```

## Запустите Adminer в Git-Bash/Linux/WSL 2.0/Mac
```
docker run -d \
  --name adminer \
  -p 8084:8080 \
  adminer:latest
```
![](./img/apachi/Adminer/pervoe.png)

![](./img/apachi/Adminer/RezPerv.png)


[Откройте: http://localhost:8084](http://localhost:8084)
![](./img/apachi/Adminer/sait.png)


(можно создать еще один, главное поменять порт и название)
например:

```
docker run -d `
  --name adminer_2 `
  -p 8085:8080 `
  adminer:latest
```

[Откройте: http://localhost:8085](http://localhost:8085)

> Без отдельно запущенного контейнера с БД PostgreSQL и связи с ним админ-панель работаеть не будет!

> Заполнять данные админ-панели не нужно!

Система:
- PostgreSQL
- сервер: host.docker.internal
- логин: postgres
- пароль: mysecretpassword