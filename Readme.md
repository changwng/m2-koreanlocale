Magento 2 Korean Language Pack (ko_KR)

https://github.com/changwng/m2-koreanlocale
 


1. Manual Install <br/>
   1.1 copy to app\i18n\changwng\ko_kr 에 압축 해제 <br/>
   1.2 php bin/magento setup:upgrade <br/>
   1.3 php bin/magento cache:clean <br/>
   1.4 rm -r pub/static <br/>
   1.5 php bin/magento setup:static-content:deploy ko_KR <br/>

2. Composer <br/>
composer create-project changwng/m2-koreanlocale -s dev<br/>

composer require changwng/m2-koreanlocale <br/>

php bin/magento setup:upgrade <br/>
php bin/magento cache:clean <br/>


rm -r pub/static <br/>
php bin/magento setup:static-content:deploy ko_KR <br/>

php bin/magento setup:static-content:deploy en_US <br/>
php bin/magento setup:static-content:deploy ko_KR <br/>
php bin/magento setup:static-content:deploy ja_JP <br/>


3. locale setting <br/>
Activate language (backend): Account > Settings > Account information > Interface Locale <br/>
Activate language (frontend): Stores > Settings > Configuration > [storeview] > Locale options > Locale <br/>


4. copy right changwng@gmail.com  (c) 2016.
