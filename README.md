# composer-ddev-elasticsearch

A composer recipe to implement an elasticsearch service and elastichq as described in [ddev docs](https://ddev.readthedocs.io/en/stable/users/extend/additional-services/#elasticsearch)

Install with `ddev composer require rfay/composer-ddev-elasticsearch` or `composer require rfay/composer-ddev-elasticsearch`

You temporarily need to add two additional repositories into composer.json to use this, for example:

```json
    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.drupal.org/8"
        },
        {
            "type": "vcs",
            "url": "https://github.com/rfay/composer-ddev-elasticsearch"
        },
        {
            "type": "vcs",
            "url": "https://git.4viewture.eu/ddev/composer-ddev"
        }
    ],
```
