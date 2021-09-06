FROM nginx:1.19.9-alpine
ADD nginx.conf /etc/nginx/conf.d/default.conf
RUN set -x
ADD dist/ /usr/share/nginx/html/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
