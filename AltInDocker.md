## Alt Linux в Docker

#### Использовать контейнер с Alt

##### Загрузить готовый образ Alt
```shell
docker pull alt:sisyphus
```
![](./img/apachi/AltInDocker/AltPerv.png)

##### Запустить и использовать
```shell
docker run -ti --rm --name alt alt:sisyphus /bin/bash
```
![](./img/apachi/AltInDocker/AltVtor.png)

#### Установить приложение Fastfetch в контейнере
```shell
apt-get update && apt-get install fastfetch
```
![](./img/apachi/AltInDocker/AltTret.png)

#### Запустить Fastfetch
```shell
fastfetch
```
![](./img/apachi/AltInDocker/AltChetv.png)

##### Выйти из контейнера с Alt
```shell
exit
```
![](./img/apachi/AltInDocker/AltPyat.png)