# Cloud Farm™

Cloud farm is mobile and web based platform that empowers the youths, workers and farmers, by providing them detailed information about farming categories and allows them to invest online and be able to earn interests and profits after a duration of 2 months. Their investments is put into farming ranches to boost the agriculture sector. Cloud farm is a complete framework in the sense that it puts the farmer above all by providing complete control and assistance regarding their farm, investments and expenses. Our users can also be able to obtain financial support through loans and incentives. The farmer can view detailed description of his investments, earnings, loan history and all farming categories available for investment. The farmer can keep track of what crops are grown in his/her farm. The app also aims to allow smart-farming by providing the farmer suggestions that will endanger the betterment of their business and thereby increasing the GDP of the nation.
Cloud Farm is built with modern technologies such as Laravel, Bootstrap, jQuery, RESTful API etc.

## Requirements

* PHP 5.6.4 or higher
* Database (eg: MySQL, PostgreSQL, SQLite)
* Web Server (eg: Apache, Nginx, IIS)

## Framework

Cloud Farm uses [Laravel](http://laravel.com), the best existing PHP framework, as the foundation framework and [Modules](https://nwidart.com/laravel-modules) package for Apps.

## Installation

  * Install [Composer](https://getcomposer.org/download)
  * Download the [repository](https://github.com/Monyancha/Cloud-Farm.git) and unzip into your server
  * Open and point your command line to the directory you unzipped Akaunting
  * Run the following command: `composer install`
  * Finally, launch the [installer](https://akaunting.com/docs/installation)

## Docker

It is possible to containerise Akaunting using the [`docker-compose`](docker-compose.yml) file. Here are a few commands:

```
# Build the app
docker build -t akaunting .

# Run the app
docker-compose up -d

# Make sure you the dependencies are installed
docker-compose exec web composer install

# Stream logs
docker-compose logs -f web

# Access the container
docker-compose exec web /bin/sh

# Stop & Delete everything
docker-compose down -v
```

## Contributing

Fork the repository, make the code changes then submit a pull request.

Please, be very clear on your commit messages and pull requests, empty pull request messages may be rejected without reason.

When contributing code to Akaunting, you must follow the PSR coding standards. The golden rule is: Imitate the existing Akaunting code.

By participating in this project you agree to abide by its terms.

## Credits

- [Enock Monyancha](https://github.com/Monyancha)
- [All Contributors](../../contributors)

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
[![Contributors]](../../contributors)

## License

Cloud Farm is released under the [MIT license](LICENSE.txt).
