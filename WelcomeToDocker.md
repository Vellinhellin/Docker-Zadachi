## Проверить порт 8088 для Linux/Mac/WSL:
```
netstat -tuln | grep :8088
```
![](./img/apachi/welkomToDocker/pervoe.png)
## Загрузить образ и запустить контейнера
```
docker run -d -p 8088:80 --name welcome-to-docker docker/welcome-to-docker
```
[открыть в браузере локальный хост](http://localhost:8088/)
![](./img/apachi/welkomToDocker/vtoroe.png)
![](./img/apachi/welkomToDocker/vtorot.png)
![](./img/apachi/welkomToDocker/vtoyoyoy.jpeg)
## Зайти в контейнер
```
docker exec -it welcome-to-docker /bin/sh
```
![](./img/apachi/welkomToDocker/trete.png)
# Повыполнять разные команды:
## Показать ин-фу по ОС
```
uname -a
```
![](./img/apachi/welkomToDocker/pervKom.png)
## Диспетчер ресурсов
```
top
```
![](./img/apachi/welkomToDocker/vtorKom.png)
## Обновить источники приложений
```
apk update && apk upgrade
```
![](./img/apachi/welkomToDocker/tretKom.png)
## Установить приложение
```
apk add fastfetch
```
![](./img/apachi/welkomToDocker/chetvKom.png)
## Запустить приложение
```
fastfetch
```
![](./img/apachi/welkomToDocker/pyatKom.png)