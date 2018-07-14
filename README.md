# magento2-installation
install magento 2 by command line

php bin/magento setup:install \
  --admin-firstname=firstname \
  --admin-lastname=lastname \
  --admin-email=admin@gmail.com \
  --admin-user=admin \
  --admin-password=admin123 \
  --base-url=http://m2.local/ \
  --db-host=localhost \
  --db-name=mage2 \
  --db-user=mage2 \
  --db-password=pass123 \
  --currency=AUD \
  --timezone=Australia/Sydney \
  --language=en_AU \
  --use-rewrites=1
  
  php bin/magento admin:user:create --admin-user='admin' --admin-password='admin123' --admin-email='admin@gmail.com' --admin-firstname='Jon' --admin-lastname='Doe'
