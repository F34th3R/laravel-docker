# laravel-docker
Just a template using docker container... setup for laravel 🐳

...under construction 🚧

## PORTS
- nginx: 8080
- php:   9091
- MySQL: 4306

## Starting Docker
```bash
docker-compose build
```

```bash
docker-compose up
```

## Laravel
Migrate
```bash
 $ docker-compose exec php php /var/www/html/artisan migrate
```

Enter to laravel bash
```bash
 $ docker-compose exec php php /var/www/html/artisan 
```


## Issues ⚠
### _check Internet connection and firewall_
[youtube tutorial](https://www.youtube.com/watch?v=TARiQdUf3S0)
