FROM nginx

COPY nginx.conf /etc/nginx/nginx.conf

COPY sites-enabled /etc/nginx/conf.d/sites-enabled
COPY static /www/data
COPY certs /etc/nginx/certs