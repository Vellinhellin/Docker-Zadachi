## Node.js для JavaScript

Запустить **Node.js REPL**
```shell
docker run -it --rm node:alpine node
```
![](./img/apachi/Node.jsForJS/nodePerv.png)

И запустить скрипт
```shell
console.log('Hello from Docker!');
```
![](./img/apachi/Node.jsForJS/nodeVtor.png)

Для выхода из консоли
```shell
.exit
```


или
```shell
docker run --rm node:alpine node -e "console.log('Hello')"
```

![](./img/apachi/Node.jsForJS/nodeTret.png)