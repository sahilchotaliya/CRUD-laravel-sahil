



```

```
    cd laravel-8-image-crud
```

```

    composer install

```


```

    cp .env.example .env

```


Put your credentils .env file.

```.env

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=Laravel8CrudImage
    DB_USERNAME=root
    DB_PASSWORD=root@123

```
``` Run Server
    
    php artisan storage:link
    
```

Step second: Run server
```
    php artisan serve

```
Check from this url
```
    http://127.0.0.1:8000/posts
```
