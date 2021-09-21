Laravel CRUD API

how to run:

php artisan serve
php artisan migrate

using:


list - http://127.0.0.1:8000/api/products
create - http://127.0.0.1:8000/api/products   (JSON name, description, price)
delete -  http://127.0.0.1:8000/api/products/
update -  http://127.0.0.1:8000/api/products/
search - http://127.0.0.1:8000/api/search-data/

Http/Controller/ProductController.php
Helpers/APIHelpers.php
routes/api.php


validation
Http/Requests/SaveProductRequest.php
