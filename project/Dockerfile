FROM richarvey/nginx-php-fpm:1.10.3
RUN rm -Rf /etc/nginx/sites-enabled/*
COPY site.conf /etc/nginx/sites-available/site.conf
RUN ln -s /etc/nginx/sites-available/site.conf /etc/nginx/sites-enabled/site.conf
