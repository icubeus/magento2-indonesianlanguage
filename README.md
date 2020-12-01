## Magento 2 Indonesian Language

Instalation:

    composer config repositories.icubeus-indonesianlanguage git git@github.com:icubeus/magento2-indonesianlanguage.git
    
    For Swift Magento Version 2.3.x : composer require "icubeus/magento2-indonesianlanguage":"^3.5"
    
    For Swift Magento Version 2.4.x : composer require "icubeus/magento2-indonesianlanguage":"^4.1"

To update:

    composer update icubeus/magento2-indonesianlanguage

after instalation please
	
	php bin/magento cache:clean
	php bin/magento setup:static-content:deploy id_ID
	php bin/magento indexer:reindex
	php bin/magento cache:clean
	php bin/magento cache:flush
