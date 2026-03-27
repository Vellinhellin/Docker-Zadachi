# Apachi
```
    docker run -d --name my-apache -p 8081:80 httpd  
```
получить образ, создать образ и запустить контейнер

![получить образ, создать образ и запустить контейнер](./img/apachi/apachi/ggdfsfaa.jpeg)

## Редактирование веб-страницы
### Зайти в контейнер:
```
    docker exec -it my-apache bash  
```
![получить образ, создать образ и запустить контейнер](./img/apachi/apachi/llll.png)
![получить образ, создать образ и запустить контейнер](./img/apachi/apachi/hkhkhk.png)

## Открыть файл index.html для редактирования содержимого:
```
     micro /usr/local/apache2/htdocs/index.html    
```
## Отредактированный вариант:
![получить образ, создать образ и запуст](./img/apachi/apachi/hhhhh.png)