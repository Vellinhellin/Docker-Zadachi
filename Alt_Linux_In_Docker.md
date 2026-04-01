# Alt Linux в Docker
> Никогда в разработке не используйте русские имена файлов и каталогов!

> Никогда в разработке не используйте пробелы и спец.символы в именах файлов и каталогов!!

#### Использовать контейнер с Alt

##### Загрузить готовый образ Alt
```shell
docker pull alt:sisyphus
```
![](./img/apachi/Alt_Linux_In_Docker/pervv.png)

##### Запустить и использовать
```shell
docker run -ti --rm --name alt alt:sisyphus /bin/bash
```
![](./img/apachi/Alt_Linux_In_Docker/vtorr.png)

#### Установить приложение Fastfetch в контейнере
```shell
apt-get update && apt-get install fastfetch
```
![](./img/apachi/Alt_Linux_In_Docker/trett.png)

#### Запустить Fastfetch
```shell
fastfetch
```
![](./img/apachi/Alt_Linux_In_Docker/chertv.png)

##### Выйти из контейнера с Alt
```shell
exit
```
![](./img/apachi/Alt_Linux_In_Docker/pyatt.png)