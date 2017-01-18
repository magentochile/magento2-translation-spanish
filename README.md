# magento2-translation-spanish
# Magento 2 Spanish Language Pack Spanish version 1.0.0

Spanish translation for Magento 2. Translation es_ES (Spanish Chile).

Traduction de Magento 2 en Spanish.

See documentation: https://www.magentochile.cl/m2-spanish-language-pack.html


## Supported versions

* Magento v2.0.0
* Magento v2.0.1
* Magento v2.0.2
* Magento v2.0.3
* Magento v2.0.4
* Magento v2.0.5
* Magento v2.0.6
* Magento v2.0.7
* Magento v2.0.8
* Magento v2.1.0
* Magento v2.1.1
* Magento v2.1.2
* Magento v2.1.3

## Links

* Website: https://www.magentochile.cl/
* Packagist: https://packagist.org/packages/magentochile/magento2-translation-spanish
* Official version: https://www.magentochile.cl/m2-spanish-language-pack.html

## Important Note: 
This pack of languages, only contains the skeleton for translations, which you can install and once installed can translate the file es_CL respectively.

## Installation
composer require magentochile/magento2-translation-spanish dev-master
php -d memory_limit=-1 bin/magento setup:static-content:deploy es_ES
php bin/magento cache:clean
## End
