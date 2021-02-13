# bitfertig/laravel-options

A package for Laravel with a single function for a shorter and fast way to work with Carbon.

## Install

## Install directly

Setup from GitHub directly in composer.json:
```json
{
    ...
    "repositories": [
        {
            "type": "git",
            "url": "https://github.com/Bitfertig/laravel-carbon-function.git"
        }
    ],
    "require": {
        "bitfertig/laravel-carbon-function": "dev-main"
    }
    ...
}
```


## Usage

```php
carbon('2021-02-13')->format('d.m.Y'); // 13.02.2021
```


## Author

Aurelian "dipser" Hermand