FROM nginxinc/nginx-unprivileged:1.22-alpine

WORKDIR /app
COPY /app .
COPY nginx.conf /etc/nginx/conf.d/default.conf

USER 101

EXPOSE 8001
