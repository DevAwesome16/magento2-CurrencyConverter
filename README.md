# Mage2 Module RB CurrencyConverter

    ``rb/module-currencyconverter``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
This is magento 2 module which provides integration of free currency converter(freecurrencyapi.net) API.

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/RB`
 - Enable the module by running `php bin/magento module:enable RB_CurrencyConverter`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require rb/module-currencyconverter`
 - enable the module by running `php bin/magento module:enable RB_CurrencyConverter`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration

 - API Key (currency/freecurrencyapi/api_key)

 - Connection Timeout in Seconds (currency/freecurrencyapi/timeout)


## Specifications




## Attributes



