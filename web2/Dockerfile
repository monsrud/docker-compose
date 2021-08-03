FROM nginx:stable
ADD ./default.conf /etc/nginx/conf.d/default.conf 
ADD ./fastcgi.conf /etc/nginx/fastcgi.conf 
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
