FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
RUN apt-get update && apt-get install -y vim

# COPY /appimg/test/envoyKeycloak/nginx/default.conf /etc/nginx/conf.d/default.conf
# COPY /appimg/test/envoyKeycloak/nginx/nginx.conf /etc/nginx/nginx.conf

EXPOSE 31011

# container 실행 시 자동으로 실행할 command. nginx 시작함
CMD ["nginx", "-g", "daemon off;"]