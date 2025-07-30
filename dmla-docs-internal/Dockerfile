FROM nginx:latest AS base
COPY ./site /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
#ENTRYPOINT [ "node","build/index.js" ]