## Файловый обменник

1. Запустить **simple-http-server** для раздачи файлов

в **Windows Powershell**
```shell
docker run -d `
  --name my-apache-server `
  -p 8084:80 `
  -v "$(PWD):/usr/local/apache2/htdocs/" `
  httpd:alpine
```
![alt text](./img/apachi/file-server/image.png)


в **Git-Bash/Linux/WSL 2.0/Mac**
```shell
docker run -d \
  --name my-apache-server \
  -p 8084:80 \
  -v "$(pwd):/usr/local/apache2/htdocs/" \
  httpd:alpine
```
2. [Откройте: http://localhost:8084](http://localhost:8084)
![alt text](./img/apachi/file-server/image2.png)
