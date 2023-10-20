FROM nginx:alpine
COPY fst-nginx/nginx.conf /etc/nginx
COPY fst-nginx/default.conf /etc/nginx/conf.d
COPY fst-nginx/www/index.html /usr/share/nginx/html
WORKDIR /etc/nginx