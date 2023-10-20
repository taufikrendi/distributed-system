FROM nginx:alpine
COPY sec-nginx/nginx.conf /etc/nginx
COPY sec-nginx/default.conf /etc/nginx/conf.d
COPY sec-nginx/www/index.html /usr/share/nginx/html
WORKDIR /etc/nginx