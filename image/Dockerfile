FROM nginx:1.20.0-alpine

LABEL Maintainer="Zero<tobewhatwewant@outlook.com>"

ENV TZ=Asia/Shanghai

COPY config/nginx.conf /etc/nginx

COPY config/default.conf /etc/nginx/conf.d

CMD nginx -g "daemon off;"
