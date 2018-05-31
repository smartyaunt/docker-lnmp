FROM nginx:1.11

ENV TZ=Asia/Shanghai
COPY ./nginx.conf /etc/nginx/conf.d/default.conf
RUN chmod -R 777 /var/www/html