
### Run on the development environment

- Open terminal window with your dev area
- Then run this below comments

```sh
$ git clone https://github.com/vorsurm/LaravelEcommerce.git

$ cd LaravelEcommerce
$ composer install
$ cp .env.example .env
$ php artisan key:generate
$ config .env file, below description
$ php artisan migrate
$ php artisan serve
$ php artisan db:seed



$ It`s open a browser window with http://localhost:8000/login

Admin credential:

email:admin@admin.com
password:123456789


```

### Configure environment variables

- Add the .env variable name of the following below information.

```

MySQL Config:
==============
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=LaravelEcommerce
DB_USERNAME=username
DB_PASSWORD=password

