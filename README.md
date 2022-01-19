# Setup
1. .envをルートに作成し、.env.exampleの中身を貼付
2. 下記にdocker-compose.ymlの値を入力
- DB_HOST
- DB_DATABASE
- DB_USERNAME
- DB_PASSWORD
3. コマンド実行
```
$ docker-compose up -d
$ docker-compose exec php composer install
$ docker-compose exec php php artisan key:generate
```