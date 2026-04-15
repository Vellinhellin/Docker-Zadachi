## PostgreSQL

Запуск **PostgreSQL** с паролем

в **Windows Powershell**
```shell
docker run -d `
  --name my-postgres `
  -p 5432:5432 `
  -e POSTGRES_PASSWORD=mysecretpassword `
  postgres:alpine
```

> Если эта команда в Powershell не работает, то удалите из кода апострофы `

в **Git-Bash/Linux/WSL 2.0/Mac**
```shell
docker run -d \
  --name my-postgres \
  -p 5432:5432 \
  -e POSTGRES_PASSWORD=mysecretpassword \
  postgres:alpine
```
![](./img/apachi/PostgreSQL/postPerv.png)

Подключиться через `psql`
```shell
docker exec -it my-postgres psql -U postgres
```
![](./img/apachi/PostgreSQL/postVtor.png)
- Выполнить несколько демонстрационных команд, например:

Получить список баз данных:
```sql
\l
```
![](./img/apachi/PostgreSQL/postTret.png)
Получить версию:
```sql
SELECT version();
```
![](./img/apachi/PostgreSQL/postChwetiri.png)
выйти из БД
```sql
exit
```
![](./img/apachi/PostgreSQL/postPyat.png)