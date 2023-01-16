# magento2.4-infra-docker

`bin/magento setup:install \
--base-url=http://magexto.local \
--db-host=mysql \
--db-name=magento \
--db-user=root \
--db-password=root \
--admin-firstname=admin \
--admin-lastname=admin \
--admin-email=admin@admin.com \
--admin-user=admin \
--admin-password=admin123 \
--language=en_US \
--currency=USD \
--timezone=America/Chicago \
--use-rewrites=1 \
--use-sample-data \
--search-engine=elasticsearch7 \
--elasticsearch-host=elasticsearch \
--elasticsearch-port=9200 \
--elasticsearch-index-prefix=magento2 \
--elasticsearch-timeout=15`

