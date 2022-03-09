FROM nginx:latest

COPY ./default.conf /etc/nginx/conf.d/
COPY ./nginx.conf /etc/nginx/

CMD ["nginx-debug", "-g", "daemon off;"]
