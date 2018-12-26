certbot certonly -d dr.putech.app
certbot certonly --webroot -w /var/www/html/ -d metrics.putech.app -d sentry.putech.app -d dr.putech.app
which certbot 
