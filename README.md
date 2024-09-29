# todo-app

# DB

### DB 起動

```
docker compose up -d db
```

### DB 作業

```shell
docker exec -it mysql-container bash
## rootでログインする場合
mysql -u root -p
## アプリユーザーでログインする場合
mysql -u todo_app -p
```

```SQL
use todo_app;
```
