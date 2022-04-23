# react-learning

環境

Laravel 8

MySQL 8

React

node 16

php 7.4

nginx 1.20

コンテナ作成

```
$ make init
```

コンテナとイメージ破棄

```
$ make destory
```

各種コンテナに入る

laravel_appコンテナ：ここでlaravelやphpなどを動かしている
```
$ make laravel_app
```

react_appコンテナ：ここでnodeやreactなどを動かしている
```
$ make react_app
```
dbコンテナ：ここでmysqlを動かしている
```
$ make laravel_app
```

webコンテナ：ここでnginxを動かしている
```
$ make web
```

構築

```
$ make init
```

# 注意

.envファイルの ` DB_HOST ` の項目は ` db ` にする

mysqlのユーザやパスワードは ` mysql/Dockerfile ` に記述してある

詳細なコマンドは` Makefile`を確認
