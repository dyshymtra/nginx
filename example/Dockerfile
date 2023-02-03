FROM registry.access.redhat.com/ubi8/nginx-120

EXPOSE 8081

COPY nginx.conf /etc/nginx/nginx.conf

COPY /app/ /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
