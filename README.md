# CLI

### Linux

```sh
/opt/lampp/htdocs
sudo mkdir demo-site
sudo chown -R $USER:$USER test-site
```

```sh
cd /opt/lampp
sudo ./xampp start
sudo ./xampp stop
```

```sh
sudo service apache2 stop
```

```sh
cd /opt/lampp
sudo ./manager-linux-x64.run
```

### PHP

```sh
php artisan serve
```

### Laravel

```sh
php artisan migrate
```

```sh
php artisan install:api
```

```sh
php artisan make:migration create_products_table
```

```sh
php artisan make:model Product
```
Inside API folder
```sh
php artisan make:controller Api/ProductController
```

Get all route methods list
```sh
php artisan route:list
```

```sh
php artisan make:resource ProductResource
```


