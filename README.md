## Scripting4U Team coding standards
This repository contains the rule sets and the configuration files.

## Requrements

`"php": "^8.0"`

## What's in this

- `PHPCS` - https://github.com/squizlabs/PHP_CodeSniffer
- `PHPMD` - https://github.com/phpmd/phpmd
- `PHPSTAN` - https://github.com/nunomaduro/larastan
- `PHPCS Fixer` - https://github.com/PHP-CS-Fixer/PHP-CS-Fixer

## Setup

add to composer file:
```json
{
    "repositories": [
        {
            "type": "vcs",
            "url":  "https://github.com/scripting4u/coding-standards"
        }
    ]
}
```

```php
composer require --dev "scripting4u/coding-standards:^1.0.1"
```

- Check if your IDE needs extra configuration to use this

### Supported Laravel versions
| Laravel Version     | Larastan Version |
|---------------------|------------------|
| \> 10.0 && >= 11.16 | 1.0.0            |
| 11.16+              | 1.0.1            |

## Todo
We can expand this repository to contain configuration for Live Templates or any other configuration for phpstorm.

