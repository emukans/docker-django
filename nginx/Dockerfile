FROM nginx

ADD etc/conf/nginx.conf /etc/nginx/
ADD etc/conf/django.conf /etc/nginx/conf.d/default.conf

CMD ["nginx"]

EXPOSE 80
EXPOSE 443
