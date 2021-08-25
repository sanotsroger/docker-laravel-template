# Template Docker + Laravel

Construindos os Containeres
```
$ docker-compose build
```

Rodando os containers
```
$ docker-compose up -d
```

Na primeira vez que os containeres forem criados executar o seguinte comando
```
$ docker exec -it laravel-app bash 
$ php artisan key:generate
```

Fazendo os updates com o composer
```
$ composer update
```