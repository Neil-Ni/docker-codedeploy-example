FROM gliderlabs/alpine

RUN apk-install nginx \
  && mkdir -p /tmp/nginx

EXPOSE 8000

COPY nginx.conf /etc/nginx/nginx.conf

ADD build.tar.gz /app/

CMD nginx
