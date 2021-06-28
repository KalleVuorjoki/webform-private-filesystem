## Installation

For local development use [DDEV](https://github.com/drud/ddev)

Requirements on local machine:
- Docker
- mkcert [Installation quite](https://ddev.readthedocs.io/en/stable/#installationupgrade-script-linux-and-macos)

```sh
composer install
ddev start
ddev exec drush site-install --existing-config --account-pass=123 -y
```

Drupal: https://webform-private-files.ddev.site
Contact form: https://webform-private-files.ddev.site/form/contact
Mailhog: http://webform-private-files.ddev.site:8025
