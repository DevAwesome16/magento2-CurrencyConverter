# Mage2 Module MageRahul CurrencyConverter

    ``composer require magerahul/module-currencyconverter``

 - [Main Functionalities](#user-content-main-functionalities)
 - [Installation](#user-content-installation)
 - [Configuration](#user-content-configuration)
 - [Specifications](#user-content-specifications)
 - [Attributes](#user-content-attributes)


## Main Functionalities
This is magento 2 module which provides integration of free currency converter(freecurrencyapi.net) API.

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/MageRahul`
 - Enable the module by running `php bin/magento module:enable MageRahul_CurrencyConverter`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require magerahul/module-currencyconverter`
 - enable the module by running `php bin/magento module:enable MageRahul_CurrencyConverter`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration

 - API Key (currency/freecurrencyapi/api_key)

 - Connection Timeout in Seconds (currency/freecurrencyapi/timeout)


## Specifications




## Attributes



