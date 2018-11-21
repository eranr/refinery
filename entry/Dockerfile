FROM alpine

RUN apk add --update \
    nginx

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 8081

CMD nginx -g 'pid /tmp/nginx.pid;'
