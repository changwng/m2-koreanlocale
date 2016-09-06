changwng Magento 2 Korean Language Pack (ko_KR)

https://github.com/changwng/m2-koreanlocale
 


1. Manual Install
   1.1 copy to app\i18n\changwng\ko_kr 에 압축 해제
   1.2 php bin/magento setup:upgrade
   1.3 php bin/magento cache:clean
   1.4 rm -r pub/static
   1.5 php bin/magento setup:static-content:deploy ko_KR
2. Composer 
composer create-project changwng/m2-koreanlocale -s dev

composer require changwng/m2-koreanlocale

php bin/magento setup:upgrade
php bin/magento cache:clean


rm -r pub/static
php bin/magento setup:static-content:deploy ko_KR

php bin/magento setup:static-content:deploy en_US
php bin/magento setup:static-content:deploy ko_KR
php bin/magento setup:static-content:deploy ja_JP


3. locale setting
Activate language (backend): Account > Settings > Account information > Interface Locale
Activate language (frontend): Stores > Settings > Configuration > [storeview] > Locale options > Locale


4. copy right changwng@gmail.com  (c) 2016.
