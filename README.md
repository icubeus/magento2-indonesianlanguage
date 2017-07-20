## Magento 2 Indonesian Language

```
composer require icubeus/magento2-indonesianlanguage:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy id_ID
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


update 

```
composer update icubeus/magento2-indonesianlanguage:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy id_ID
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```