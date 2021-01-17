FROM nginx:latest

RUN apt-get -y update && apt-get -y install procps

RUN usermod -u 1001 nginx

COPY nginx.conf /etc/nginx/

EXPOSE 8000 8000

ENTRYPOINT ["nginx", "-g", "daemon off;"]
