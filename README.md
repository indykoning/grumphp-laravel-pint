# GrumPHP Laravel Pint

A [Laravel Pint](https://laravel.com/docs/9.x/pint) task for [GrumPHP](https://github.com/phpro/grumphp).

[![Latest Version](https://img.shields.io/github/release/indykoning/grumphp-laravel-pint?style=flat-square)](https://github.com/indykoning/grumphp-laravel-pint/releases)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/indykoning/grumphp-laravel-pint/tests?style=flat-square)](https://github.com/indykoning/grumphp-laravel-pint/actions/workflows/tests.yml)
[![Total Downloads](https://img.shields.io/packagist/dt/indykoning/grumphp-laravel-pint?style=flat-square)](https://packagist.org/packages/indykoning/grumphp-laravel-pint)

## Installation

	composer require indykoning/grumphp-laravel-pint

## Usage

In your grumphp.yml : 

```yaml
grumphp:
  extensions:
    - Indykoning\GrumPHPLaravelPint\ExtensionLoader
  tasks:
    laravel_pint:
      config: pint.json
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Credits

- [James Hemery](https://github.com/jameshemery)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

