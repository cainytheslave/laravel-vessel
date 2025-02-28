# Laravel Vessel

[![Latest Version on Packagist](https://img.shields.io/packagist/v/cainytheslave/laravel-oci.svg?style=flat-square)](https://packagist.org/packages/cainytheslave/laravel-oci)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/cainytheslave/laravel-oci/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/cainytheslave/laravel-oci/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/cainytheslave/laravel-oci/fix-php-code-style-issues.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/cainytheslave/laravel-oci/actions?query=workflow%3A"Fix+PHP+code+style+issues"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/cainytheslave/laravel-oci.svg?style=flat-square)](https://packagist.org/packages/cainytheslave/laravel-oci)

A Laravel Package for interacting with registries following the Open Container Initiative Distribution Specification.

## Installation

You can install the package via composer:

```bash
composer require cainytheslave/laravel-oci
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="laravel-oci-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="laravel-oci-config"
```

This is the contents of the published config file:

```php
return [
];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="laravel-oci-views"
```

## Usage

```php
$laravelOci = new Wajo\LaravelOci();
echo $laravelOci->echoPhrase('Hello, Wajo!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [John Wagner](https://github.com/cainytheslave)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
